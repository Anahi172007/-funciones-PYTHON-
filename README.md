# Función del cálculo de descuento
def calcular_descuentos(subtotal, porcentaje):
    descuento = (subtotal * porcentaje) / 100  # Cambié el divisor a 100
    return descuento

# Función del cálculo del IVA
def calcular_iva(subtotal, porcentaje_iva):
    iva = (subtotal * porcentaje_iva) / 100  # Cambié el divisor a 100
    return iva

# Valores
valor_subtotal = 450
valor_descuento = calcular_descuentos(valor_subtotal, 25)  # 25% de descuento
valor_iva = calcular_iva(valor_subtotal, 15)  # 15% de IVA

# Cálculo del total
total = valor_subtotal - valor_descuento + valor_iva

# Imprimir resultados
print(f'valor_subtotal: {valor_subtotal}')
print(f'valor_descuento: {valor_descuento}')
print(f'valor_iva: {valor_iva}')
print(f'valor_total: {total}')
