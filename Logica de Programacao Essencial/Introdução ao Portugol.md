## **Linguagens de Programação**

<br>

- **Compilada:** É uma linguagem de programação em que o código fonte é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação.

- **Interpretadas:** É uma linguagem de programação em que o código fonte é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador.

<br>

### _O Portugol é uma pseudolinguagem que permite ao leitor desenvolver algoritimos estruturados em português de forma simples e intuitiva, independente de linguagem de programação, fazendo com que o programador pense no problema em si e não no equipamento que irá executar o algoritimo._

<br>

## _Utilizaçãpo do Se e Senao_

<br>

    programa 
    {
        função inicio() 
        {
            real nota1,nota2,nota3,nota4,media
            cadeia aluno

    escreva("Digite o seu nome:")
    leia(aluno)
    escreva("Digite a nota 1:")
    leia(nota1)
    escreva("Digite a nota 2:")
    leia(nota2)
    escreva("Digite a nota 3:")
    leia(nota3)
    escreva("Digite a nota 4:")
    leia(nota4)

    media = (nota1+nota2+nota3+nota4)/4

    escreva ("Sua média é: + media)

    se(media>=6) {
        escreva("\n" + "Você foi aprovado")
            }
        
        senao {
            escreva("\n" + "Você foi reprovado)
            }
        }
    }

## _Utilização de Laços de Repetição_

<br>

    programa 
    {
        função inicio() 
        {
            inteiro contador,limite,resultado,tabuada

            contador = 0
            limite = 10

            escreva("Qual tabuada você quer que eu resolva?:")
            leia(tabuada)

            faca{

                resultado = tabuada * contador
                escreva(tabuada + " x " + contador + " =" + resultado + "\n")
                contador ++

            }enquanto (contador<=limite>)
        }
    }

## **Matriz**

<br>

É uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados continuamente na memória.

    EX: 
    cadeia frutas [4];
    frutas[0]="Maçã"
    frutas[1]="Pera"
    frutas[2]="Uva"
    frutas[3]="Melão"
    escreva(frutas[2])

<br>

## **Vetores**

<br>

São matrizes de uma só dimensão
<br>

    EX:
    cadeia cesta [][] = {{"Maçã","100},{"Pera","200}{"Uva","300"}{"Melão","400"}}


