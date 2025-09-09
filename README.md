# Meu-primeiro-projeto
class Pessoa:
    def __init__(self, nome):
        self.nome = nome
    
    def saudar(self):
        print(f"Olá,{self.nome}.")
        
pessoa1= Pessoa("Elisa")
pessoa1.saudar()
