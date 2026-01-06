# Ficha de Avaliação - Folha de Cálculo - Turno 2

## Instruções

* Esta avaliação é individual.

* Podes rever os exercícios previamente realizados.

* Faz um ***fork*** deste repositório.

![alt text](img/image.png)

* No teu ***fork***, edita o ficheiro **README.md**

![alt text](img/image-1.png)

* Utiliza os espaços indicados para responderes às questões.

* Não desformates o ficheiro.

* Quando terminares, realiza um ***Commit***

![alt text](img/image-2.png)

## Exercícios

1. Explica para que serve o sinal = numa folha de cálculo.
Indica duas situações em que se deve usar uma fórmula.
(3 valores)

        Resposta: O sinal = indica que a célula contém uma fórmula. Usa-se uma fórmula quando: Queres que o cálculo seja automático. Precisas repetir o mesmo cálculo em várias células....

2. O que acontece a uma fórmula quando é copiada para outra célula?
Explica a tua resposta usando o conceito de referências de células.
(3 valores)

        Resposta: Quando copias uma fórmula para outra célula, ela adapta-se à nova posição. Isto acontece porque as referências usadas são, normalmente, referências relativas. Exemplo: Se escreves =A1+B1 e copias para a linha de baixo, a fórmula passa a =A2+B2. Só não muda quando usas referências absolutas com $, como $A$1, que ficam sempre iguais onde quer que as coles....

3. Observa a seguinte fórmula, escrita na célula E4:

        =C4*$A$1

    a) Que tipo de referência é usada em A1? (1 valor)

        Resposta: É uma referência absoluta, porque usa os símbolos $ antes da coluna e da linha....

    b) O que acontece à referência C4 se a fórmula for copiada para E5? (1 valor)

        Resposta: A referência C4 passa para C5, porque é uma referência relativa e ajusta-se quando a fórmula desce uma linha....

4. Explica o que é a formatação condicional e indica duas regras que podem ser aplicadas a uma tabela.
(3 valores)

        Resposta: A formatação condicional serve para mudar automaticamente o aspecto das células (cor, texto, ícones) consoante o valor que nelas aparece, facilitando a leitura dos dados. Duas regras possíveis: Destacar valores acima ou abaixo de um limite (ex.: pintar a vermelho valores menores que 10). Aplicar barras de dados ou escalas de cores para mostrar visualmente diferenças entre valores....

5. Para que serve um filtro automático numa folha de cálculo?
Dá um exemplo prático relacionado com um inventário ou lista de dados.
(2 valores)

        Resposta: Um filtro automático serve para organizar e visualizar apenas os dados que nos interessam, sem apagar os restantes. Exemplo: numa lista de inventário, podes usar um filtro para mostrar apenas os produtos em falta ou apenas os de uma determinada categoria, tornando mais fácil a gestão do stock....

6. Completa a frase corretamente (2 valores):

    Ordenar dados serve para ____________, enquanto filtrar dados serve para _____________.

        Resposta 1: organizar os dados por ordem Resposta 
        Resposta 2: mostrar apenas os dados que cumprem certos critérios......

7. Para que serve um gráfico numa folha de cálculo?
Escolhe um tipo de gráfico e refere uma situação concreta em que possa ser usado.
(3 valores)

        Resposta: Um gráfico numa folha de cálculo serve para transformar números em imagens que contam uma história sobre os dados. Ajuda a perceber padrões ou comparações sem ter de ler dezenas de linhas. Exemplo: um gráfico de colunas coloridas com emojis pode mostrar quantos livros cada aluno leu num mês, tornando a tabela mais divertida e fácil de analisar para uma apresentação na escola....

8. Escreve a fórmula necessária para calcular a prestação mensal de um empréstimo de 1000 €, a pagar em 24 meses, com taxa anual de 4%.
Não é necessário calcular o valor final.
(2 valores)

        Resposta: A fórmula no Excel ou Google Sheets é: =PGTO(4%/12; 24; -1000) Explicação : 4%/12 é a taxa mensal, 24 é o número de meses, -1000 é o valor do empréstimo....
