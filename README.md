# pythonaulas
# saque,depósito, estrato, tranferência.
#POO
class Conta:
   def __init__(self,saldo,numeroconta, usuario,cpf):
      self.saldo= saldo
      self.numeroConta = numeroconta
      self.titular = usuario
      self.cpf = cpf
      
conta1 = Conta( '0', '1234', 'Elaine', '987')

print(conta1.titular, conta1.saldo , conta1.cpf , conta1.numeroConta)


