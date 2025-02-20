import time

perguntas = {
    "Qual o seu nome?": "Eu sou Bard.",
    "Que dia é hoje?": "Hoje é um dia lindo!",
    "Qual a capital do Brasil?": "Brasília."
}

while True:
    pergunta = input("Você: ")
    if pergunta in perguntas:
        print("Bard:", perguntas[pergunta])
    else:
        "quando não encontrar a pergunta"
        print("Bard: A sim voce quer saber sobre o mercado de trabalho e o mercado de investimentos , espere um pouco para eu te ajudar.")
        break
else:

    time.sleep(5)

    print("Bard: A você uma educadora financeiro vou te ajudar so espre só um momento")

time.sleep(10)
print("Bard: sim você quer saber como  ser tornar uma ou um educadora/o  financeiro vou de ensinar você"
       "entre no google e pesquisar sobre o que você quer saber sobre o mercado financeiro e o mercado de trabalho"
       "e o mercado de investimentos" "é uma boa ideia para aprender o mercado de trabalho e o mercado de investimentos"
       "e também pesquisar programa eleve que é um curso 100% online que você pde fatura 7mil reais em 3 anos e 3 messes "
       "é o valor é de ..... para fazer o curso")

time.sleep(20)
print("se ajudou você pode fazer mais perguntas")
