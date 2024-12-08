def calcular_area(figura):
    return figura.area()

circulo = Circulo(5, "rojo")
cuadrado = Cuadrado(4, "azul")  # Suponiendo que existe una clase Cuadrado

print(calcular_area(circulo))
print(calcular_area(cuadrado))
