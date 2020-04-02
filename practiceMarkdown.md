```
# Título 

# Título 2 

O título e os níveis de título podem ser definidos com **(#)**.

### Título 3

### Título 4

#### Título 5

# Parágrafo


Parágrafo no markdown se constrói com a inserção de **_dois espaços em branco no final do parágrafo_**.

Basta apertar o Enter duas vezes para inserir um espaçamento entre parágrafos.

Para pular de linha, basta aberta a tecla espaço duas vezes


# Ênfase

## Negrito

**Para colocar a palavra em negitro utilizo 2(**) asterisco no ínicio e no fim da palvra** 

__Posso também__ acrescentar 2 underlines

## Italico

*Para trnsormar uma palavra MARKDOWN em itálico posso inserir um asterisco*  
_Posso também_ utilizar **_apenas um underline._**

## Riscado

~~Para escrever riscado, utilizo o sinal da grmática tio~~

## Citação

> Apenas utilizo um sinal de maior

## Citação com negrito e itálico

> Para trabalhar com os demas recursos _**posso utilizar as demais marcações**_.

# Linhas Horizontais no Markdown  

## Exemplo 1
***
---

## Exemplo 2
* * * 
- - -

## Exemplo 3
***********
-----------  

# Listas não ordenada 


## Lista não ordenada 1

* Item 01
* Item 02
* Item 03
* Item 04
* Item 05

## Lista não ordenada 2

- Item 01
- Item 02
- Item 03
- Item 04
- Item 05


## Lista não ordenada 3

+ Item 01
    + Item 02
    + Item 03
+ Item 04
+ Item 05

## Lista não ordenada 4

* Item 01

* Item 02
* Item 03
* Item 04
* Item 05




# Listas Ordenadas

 Listas não ordenada 


## Lista ordenada 1

9. Item 01
6. Item 02
10. Item 03

## Lista ordenada 2

1. Item 01
1. Item 02
1. Item 03
1. Item 04
1. Item 05


## Lista ordenada 3

1994\. Brasil   
1998\. França  
2002\. Brasil


# Links

## Link 1

[Click Aqui](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell)

## Link 2

[Click Aqui](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell, "Cypress")


## Link 3

Mais informções: [Click Aqui][site-url]

[site-url]:
https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell


# Imagens com Markdown  

## Imagem  1

![Markdown](https://secure.meetupstatic.com/photos/event/8/f/9/2/600_470376754.jpeg)


## Imagem  2

![Maardown][image]

[image]:https://secure.meetupstatic.com/photos/event/8/f/9/2/600_470376754.jpeg


## Imagem  3 - Com link

[![Markdown](https://secure.meetupstatic.com/photos/event/8/f/9/2/600_470376754.jpeg)](https://robotframework.org/, "See More")


## Imagem  4 - Com link

[![Mardowon][image]][link]

[image]:https://secure.meetupstatic.com/photos/event/8/f/9/2/600_470376754.jpeg
[link]:https://robotframework.org/


# Tabelas

## Exemplo 1

Nome | Idade | Profissão|
-----|-------|----------|
Nome A | 35 |  Desenvolvedor |  
Nome B | 30 | Quality Anssurance |  
Nome C | 22 |Designer |


## Exemplo 2

Nome | Idade | Profissão|
:-----:|:-------:|:----------|
Nome A | 35 |  Desenvolvedor |  
Nome B | 30 | Quality Anssurance |  
Nome C | 22 |Designer |

**OBS:** **_O alinhamento pode ser feito utilizando os ':' centralizado, esquerda ou para a direita. Pipe separa as colunas e as linhas as colunas._**


# Enfase em Código

## Enfase em Linha de Código 1


Chama a função:  `def somar(a)`


## Enfase em Bloco de Código 2



        *** Test Case ***

        Scenario Selecting combo box options 
        
            Given the user are in page with combo box  
            When he select the box  
            Then the option list should be displayed  
            And an option should be selected by Label  
            And other option should be selected by Value 

**obs: Para dar ênfase no bloco, selecioná-lo e digitar TAB duas vezes.**



## Enfase em Bloco de Código 3



```
describe ('Istagram interation', () => {

  beforeEach(() => {
    cy.visit("https://www.instagram.com")
  })

 it ('contain "Instagram"', () => {
   cy.title()
    .should('contain', 'Instagram')
    cy.wait(3000) 
  })
  ```  
  **OBS: Para formatar assim, devemos inserir 3 crases no início e mais três ao fim**

  # Sintax Hightlighting


  ```javascript
describe ('Istagram interation', () => {

  beforeEach(() => {
    cy.visit("https://www.instagram.com")
  })

 it ('contain "Instagram"', () => {
   cy.title()
    .should('contain', 'Instagram')
    cy.wait(3000) 
  })
  ```

  **OBS: Para dar destaque à linnguagem do códico, basta declarar a linguagem logo após as primeiras crases.**
  ```
