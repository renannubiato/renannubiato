def verificar_paridade(numero):
    if numero % 2 == 0:
        return "Par"
    else:
        return "Ímpar"

def main():
    try:
        numero = int(input("Digite um número inteiro: "))
        resultado = verificar_paridade(numero)
        print(f"O número {numero} é {resultado}.")
    except ValueError:
        print("Por favor, digite um número inteiro válido.")

if __name__ == "__main__":
    main() - 
    -👋 Hi, I’m @renannubiato
    -📫 Para me achar (https://www.linkedin.com/in/renan-nubiato)

<!---
renannubiato/renannubiato is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
