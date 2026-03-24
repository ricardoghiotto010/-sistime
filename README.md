nome=input("qual e o seu nome: ")
idade=int(input("qual sua idade: "))
racas = ["pitbuul", "pincher","vira-lata","labrador","pastor alemão","husky","salsicha",]

while True :
    if idade < 14 :
        print("chame alguem com mais de 14 anos para conseguir adotar: ")
        break
    else :
        print("RACAS DISPONIVEIS:")
        for i, raca in enumerate(racas) :
            print(f"{i+1} - {racas[i]}")
        escolha = input("\nEscolha qual cachorro voce quer adotar: ")
        print(f"Parabens,{nome}! Voce adotou um {escolha}")
        break
