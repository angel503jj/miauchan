# miauchan
miaumiaumiau
def mostrar_mensagem_amor():
    print("Eu te amo")


def fazer_pedido_de_casamento():
    resposta = input("Você aceita se casar comigo? (Digite sim ou não ou óbvio): ")
    if resposta.lower() == 'sim':
        print("Eu te amo meu neném, mas tá mais pra óbvio...")
    if resposta.lower() == 'não':
        print("Vai toma no teu cu então fudido")
    if resposta.lower() == 'óbvio':
        print("OLD NÉ, eu te amo")


while True:
    escolha = input("Escreve A de angel se me ama, C de casamento, ou T de término")

    if escolha.upper() == 'A':
        mostrar_mensagem_amor()
    elif escolha.upper() == 'C':
        fazer_pedido_de_casamento()
    elif escolha.upper() == 'T':
        print(
            "Espero que você vai bem tomar no seu cu seu vagabunda atoa lixo nojenta cuzão eu hein, coloquei essa opção de meme ainda só pra testar sua FORÇA DE VONTADE NESSA BOSTA")
        break
    else:
        print("Escolha inválida. Tente novamente.")
