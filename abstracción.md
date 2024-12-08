from abc import ABC, abstractmethod

class Vehiculo(ABC):
    @abstractmethod
    def arrancar(self):
        pass

    @abstractmethod
    def acelerar(self):
        pass

class Coche(Vehiculo):
    def arrancar(self):
        print("El coche ha arrancado.")

    def acelerar(self):
        print("El coche está acelerando.")

class Bicicleta(Vehiculo):
    def arrancar(self):
        print("La bicicleta ha comenzado a pedalear.")

    def acelerar(self):
        print("La bicicleta está pedaleando más rápido.")
