from random import randint
from time import sleep

itens = ("CARA", "COROA")
computador = " "
cair = randint(0, 1)
jogador = " "
res = " "

print("Olá, estou aqui para jogar cara ou coroa")
print("-="*12)
sleep(2)

print("Vamos começar! Primeiro escolha:")
print('''CARA   

      ▓▓▓▓▓▓▓▓▓▓      
    ▓▓          ▓▓    
  ▓▓  ░░░░░░░░░░░░▓▓  
▓▓  ░░░░  ░░░░░░░░░░▓▓
▓▓  ░░  ░░░░░░░░░░░░▓▓
▓▓  ░░░░░░░░░░░░░░░░▓▓
▓▓  ░░░░░░░░░░░░░░░░▓▓
▓▓  ░░░░░░░░░░░░░░░░▓▓
  ▓▓  ░░░░░░░░░░░░▓▓  
    ▓▓░░░░░░░░░░▓▓    
      ▓▓▓▓▓▓▓▓▓▓
   ''')
print(" ")
sleep(2)
print("==========OU==========")
sleep(2)
print(" ")
print(''' COROA

      ▓▓▓▓▓▓▓▓▓▓      
    ▓▓          ▓▓    
  ▓▓    ░░▓▓░░░░░░▓▓  
▓▓    ░░▓▓▓▓▓▓░░░░░░▓▓
▓▓  ░░░░▓▓░░░░░░░░░░▓▓
▓▓  ░░░░░░▓▓░░░░░░░░▓▓
▓▓  ░░░░░░░░▓▓░░░░░░▓▓
▓▓  ░░░░▓▓▓▓▓▓░░░░░░▓▓
  ▓▓  ░░░░▓▓░░░░░░▓▓  
    ▓▓░░░░░░░░░░▓▓    
      ▓▓▓▓▓▓▓▓▓▓''')



while True:
  print("-="*12)
  jogador = str(input("Qual vai escolher?: ")).strip().upper()
  while jogador not in "CARACOROA":
    jogador = str(input("Qual vai escolher?: ")).strip().upper()

  if jogador == "CARA":
    print("Então eu escolho COROA")
    computador = "COROA"
  else:
    print("Então eu escolho CARA")
    computador = "CARA"
  print("-="*12)
  print('''Jogando a moeda...''')
  sleep(3)
  if cair == 0:
      print('''
        ▓▓▓▓▓▓▓▓▓▓      
      ▓▓          ▓▓    
    ▓▓  ░░░░░░░░░░░░▓▓  
  ▓▓  ░░░░  ░░░░░░░░░░▓▓
  ▓▓  ░░  ░░░░░░░░░░░░▓▓
  ▓▓  ░░░░░░░░░░░░░░░░▓▓
  ▓▓  ░░░░░░░░░░░░░░░░▓▓
  ▓▓  ░░░░░░░░░░░░░░░░▓▓
    ▓▓  ░░░░░░░░░░░░▓▓  
      ▓▓░░░░░░░░░░▓▓    
        ▓▓▓▓▓▓▓▓▓▓
    ''')

  else:
      print('''
      
        ▓▓▓▓▓▓▓▓▓▓      
      ▓▓          ▓▓    
    ▓▓    ░░▓▓░░░░░░▓▓  
  ▓▓    ░░▓▓▓▓▓▓░░░░░░▓▓
  ▓▓  ░░░░▓▓░░░░░░░░░░▓▓
  ▓▓  ░░░░░░▓▓░░░░░░░░▓▓
  ▓▓  ░░░░░░░░▓▓░░░░░░▓▓
  ▓▓  ░░░░▓▓▓▓▓▓░░░░░░▓▓
    ▓▓  ░░░░▓▓░░░░░░▓▓  
      ▓▓░░░░░░░░░░▓▓    
        ▓▓▓▓▓▓▓▓▓▓
  ''')

  print("-="*15)
  sleep(1)


  if cair == ss0:
    if jogador == "CARA" and computador ==  "COROA":
      print("JOGADOR VENCEU !!!")
      print("DEU CARA :(")
    else:
      print("EU GANHEI SEU OTARIO!")
      print("DEU CARA :)")
      break   

  else:
    if jogador == "COROA" and computador == "CARA":
      print("JOGADOR VENCEU!!!")
      print("DEU COROA :(")
      
    
    else:
      print("EU GANHEI SEU OTARIO!!!")
      print("DEU COROA :)")
      break
    

print("-="*15)
print("Obrigado por jogar foi muito divertido")

