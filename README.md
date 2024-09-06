# main.py
def saudacao_alura(nome):
    """
    Função simples para saudar o usuário como parte do trabalho da Alura.

    Parâmetros:
    nome (str): O nome do usuário para quem enviar a saudação.
    """
    print(f"Olá, {nome}! Este é o início do seu trabalho para a Alura. Vamos aprender juntos!")

if __name__ == "__main__":
    # Exemplo de uso da função
    seu_nome = input("Digite seu nome: ")
    saudacao_alura(seu_nome)
