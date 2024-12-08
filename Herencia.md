class Figura:
    def __init__(self, color):
        self.color = color

    def area(self):
        pass

class Circulo(Figura):
    def __init__(self, radio, color):
        super().__init__(color)
        self.radio = radio

    def area(self):
        return 3.14159 * self.radio**2
