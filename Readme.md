Algoritmo "Menu Lanchonete: Antônio José"

Var
opcao, total, valor_item: Real
Inicio

total <- 0

Escreval("Bem-vindo à Lanchonete Do Antônio!")
Escreval("Menu de Lanches:")
Escreval("1 – X-Salada: R$8,00")
Escreval("2 – X-Bacon: R$10,00")
Escreval("3 – X-Egg: R$9,00")
Escreval("4 – Refrigerante: R$6,50")
Escreval("5 – Finalizar pedido")

Repita
    Escreval("Digite a opção desejada (1 a 5): ")
    Leia(opcao)

    Se opcao = 1 Então
        valor_item <- 8.0
    Senão
     Se opcao = 2 Então
        valor_item <- 10.0
    Senão
     Se opcao = 3 Então
        valor_item <- 9.0
    Senão
     Se opcao = 4 Então
        valor_item <- 6.5
    Senão
     Se opcao = 5 Então
        Escreval("Pedido finalizado. Total a pagar: R$", total)
    Senão
        Escreval("Opção inválida. Escolha uma opção válida.")
    FimSe
    fimse
    fimse
    fimse
    fimse


        total <-(total + valor_item)


Ate opcao = 5
FimAlgoritmo
