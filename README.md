class Funcionario:
    def cadastrar_funcionario (self, no, ca, sa):
        self.nome = no
        self.cargo = ca
        self.salario = sa

    def exibir_informacoes (self):
        print ("nome: ", self.nome)
        print (" - cargo: ", self.cargo)
        print (" - salário: R$",self. salário)

    def aumentar_salario (self, porcentagem):
        aumento = self.salario * (porcentagem /100)
        self.salario += aumento
        print ("- novo salário: R$", self.salario)

class Funcionario:
    def cadastrar_funcionario (self, no, ca, sa):
        self.nome = no
        self.cargo = ca
        self.salario = sa
    
    def exibir_informacoes (self):
        print ("nome: ", self.nome)
        print (" - cargo: ", self.cargo)
        print (" - salário: R$", self.salario)
    
    def aumentar_salario (self, porcentagem):
        aumento = self.salario * (porcentagem /100)
        self.salario += aumento
        print (" -novo salário: R$", self.salario)

# Criando dois objetos da classe Funcionario
funcionario1 = Funcionario()
funcionario2 = Funcionario()
# Utilizando os métodos dos objetos
funcionario1.cadastrar_funcionario( "Alice", "Engenheira de Software", 8000)
funcionario1.exibir_informacoes()
funcionario1.aumentar_salario(10)
funcionario2.cadastrar_funcionario( "João", "Analista de Sistemas", 6000)
funcionario2.exibir_informacoes()
funcionario2.aumentar_salario(15)

class Funcionario:
    def __init__(self, nome, cargo, salario):
        self.nome = nome
        self.cargo = cargo
        self.salario = salario
    
    def cadastrar_funcionario(self, nome, cargo, salario):
        self.nome = nome
        self.cargo = cargo
        self.salario = salario
    
    def exibir_informacoes (self):
        print ("nome: ", self.nome)
        print (" - cargo: ", self.cargo)
        print (" - salário: R$", self.salario)

    def aumentar_salario (self, porcentagem):
        aumento = self.salario * (porcentagem /100)
        self.salario += aumento
        print ("- novo salário: R$", self.salario)

# Criando dois objetos da classe Funcionario e usando construtor
funcionario1 = Funcionario("Alice", "Engenheira de Software", 8000)
funcionario2 = Funcionario("João", "Analista de Sistemas", 6000)
# Utilizando os métodos dos objetos
funcionario1.exibir_informacoes()
funcionario1.aumentar_salario(10)
funcionario2.exibir_informacoes()
funcionario2.aumentar_salario(15)
