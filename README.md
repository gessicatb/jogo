# Jogo pra rodar no CMD
Joguinho em Python que fiz para jogar no CMD quando estiver entendiada 

_________________ by:https://github.com/gessicatb ___________________

Como jogar:

1. Adquira o Python de maneira segura pela Microsoft Store: https://apps.microsoft.com/detail/9PNRBTZXMB4Z?hl=neutral&gl=BR&ocid=pdpshare (Python 3.13) 
2. Após a instalação: aperte Windows + r
3. Digite cmd e aperte a tecla ENTER
4. Com o terminal aberto, chame o Python, com o seguinte comando:   Python
5. Cole o seguinte trecho de código (do 'import....'  ao '...break'):

import random

numero_secreto = random.randint(1, 100)
tentativas = 0

print("Adivinhe o número (1 a 100)")

while True:
    tentativa = int(input("Seu palpite: "))
    tentativas += 1
    
    if tentativa < numero_secreto:
        print("⬆️ Mais alto!")
    elif tentativa > numero_secreto:
        print("⬇️ Mais baixo!")
    else:
        print(f" Acertou em {tentativas} tentativas!")
        break

6. Aperte a tecla ENTER duas vezes e comece a joga pelo terminal :)

________________ by:https://github.com/gessicatb ___________________
