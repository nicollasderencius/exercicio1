class Animal():
    def __init__(self, nome, cor, porte):
        self._nome = nome
        self._cor = cor
        self._porte = porte
    def comer(self):
        print(f"O {self._nome} está comendo")

    def dormir(self):
        print(f"O {self._nome} está dormindo")


class gato(Animal):
    def __init__(self, nome, cor, porte):
        super().__init__(nome, cor, porte)


class cachorro(Animal):
    def __init__(self, nome, cor, porte):
        super().__init__(nome, cor, porte)


class coelho(Animal):
    def __init__(self, nome, cor, porte):
        super().__init__(nome, cor, porte)


choquito = gato("Percia", "amarelo", "medio")

choquito.comer()

thor = cachorro("viralata", "caramelo", "grande")

thor.comer()

pipoca = coelho("mini rex", "branco", "pequeno")

pipoca.comer()

print(f"depois dos animais comerem eles foram dormir")

choquito.dormir()

thor.dormir()

pipoca.dormir()
