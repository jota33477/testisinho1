# testisinho1
meme_dict = {
    "CRINGE": "Algo vergonhoso ou constrangedor",
    "STALKEAR": "Investigar a vida de alguém online",
    "VDD": "Abreviação da palavra verdade",
    "BISCOITAR": "Postar algo apenas para chamar a atenção",
    "HATER": "Pessoa que está constantemente criticando os outros",
    "VLW": "Abreviação da palavra valeu",
    "FLopar": "Quando algo não faz sucesso",
    "SHIPPAR": "Torcer para duas pessoas ficarem juntas",
    "VLW": "agradecer algo",
    "POV": "Ponto de vista de alguém"
}


for i in range(1):
    word = input("Digite uma palavra: ").upper()

    if word in meme_dict:
        print("Significado:", meme_dict[word])
    else:
        print("Essa palavra não está no dicionário!")



print("Obrigado por utilizar ")
