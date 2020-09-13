# Guide-Markdown


Este guia é resultado de: [Aprenda Markdown](https://www.udemy.com/course/aprenda-markdown/learn/lecture/12217264?start=30#overview)

---

### Índice:
<a name="links"></a>
* [Títulos e seus níveis](#link1)
* [Parágrafos](#link2)
* [Destacar palavras com *itálico* e __bold__ ](#link3)
* [Citações e Riscar a Palavra](#link4)
* [Linhas de Seções](#link5)
* [Links](#link6)
* [Imagens Markdown](#link7)
* [Imagens com Links](#link8)
* [Tabelas](#link9)
* [Listas](#link10)
* [Highlight - Destacar trechos de códigos](#link11)

***

<a id="link1"></a>
## Títulos e Seus Níveis
Eles são definidos com '#' e devemos colocar um espaço no fim da última '#':

```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```  
Exemplo:

# Título 1
## Título 2
### Título 3
#### Título 4   
##### Título 5
###### Título 6

<a id="link2"></a>
## Parágrafos  

Parágrafo no markdown se constrói com 
a inserção de **_dois espaços em branco no final da linha_**. 


<a id="link3"></a>

## Destacar palavras com *itálico* e __bold__

```
*itálico*
__bold__
```
<a id="link4"></a>

## Citações e Riscar Palavra


Citações, utilizar o sinal `>` no início da linha:

>Exemplo de citação MarkDown

~~Riscado~~


```
~~Para escrever riscado, utilizo dois acentos tios no início e final da linha~~
```

<a id="link5"></a>

## Linhas de Seções
---
Posso construir linhas sólidas inserindo `***`  ou  `---` ao fim/início de cada seção.

<a id="link6"></a>

## Links

Podemos definir alguns tipos de links.

###  1) definindo o link de maneira simples:

Exemplo:
[Click Aqui](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell)

__*Como fazer:*__

```
[Click Aqui](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell)
```

### 2) nomeando o link no momento do hover:

Exemplo:

[Click Aqui](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell, "Cypress")  

__*Como fazer:*__

```
[Click Aqui](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell, "Cypress")
```


### 3) Simplificando o link com uma 'tag':
Exemplo:

Mais informções: [Click Aqui][site-url]

[site-url]:
https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell


__*Como fazer:*__

```
Mais informações: [Click Aqui][site-url]

[site-url]:
https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell
```

<a id="link7"></a>

## Image Markdown  

### Apenas exibir uma imagem:

Exemplo:


![GitHub](https://cdn.pixabay.com/photo/2017/08/05/11/24/logo-2582757__340.png)

__*Como fazer:*__

```
![GitHub](https://cdn.pixabay.com/photo/2017/08/05/11/24/logo-2582757__340.png)
```


<a id="link8"></a>

## Links com Imagens
Podemos também linkar as imagens.

### 1) Imagem linkada e com hover definido.
Exemplo:

[![Markdown](https://static.thenounproject.com/png/2071725-200.png)](https://github.com/, "GitHub")

__*Como fazer:*__
```
[![GitHub](https://static.thenounproject.com/png/2071725-200.png)](https://github.com/, "GitHub")

```

### 2) Imagem/Gif do próprio diretório:  

Exemplo:

![Título](images/twin-peaks.gif)

__*Como fazer:*__

```
![Twin Peaks](images/twin-peaks.gif)
```

<a id="link9"></a>

## Tabelas

**_O alinhamento pode ser feito utilizando (`:`) centralizado, para esquerda ou para a direita. Pipe (`|`) separa as colunas e as linhas das colunas._**

## Exemplo 1

Nome | Idade | Profissão |
-----|-------|----------|
Nome A | 35 |  Desenvolvedor |  
Nome B | 30 | Quality Anssurance |  
Nome C | 22 |Designer |


__*Como fazer:*__

```
Nome | Idade | Profissão |
-----|-------|----------|
Nome A | 35 |  Desenvolvedor |  
Nome B | 30 | Quality Anssurance |  
Nome C | 22 |Designer |
```


## Exemplo 2

Nome | Idade | Profissão|
:-----:|:-------:|:----------|
Nome A | 35 |  Desenvolvedor |  
Nome B | 30 | Quality Anssurance |  
Nome C | 22 |Designer |

__*Como fazer:*__

## Exemplo 2
```

Nome | Idade | Profissão|
:-----:|:-------:|:----------|
Nome A | 35 |  Desenvolvedor |  
Nome B | 30 | Quality Anssurance |  
Nome C | 22 |Designer |
```
<a id="link10"></a>

## Listas
Nos exemplos abaixo, temos listas ordenadas e não ordernadas. 
OBS: Para garantir, lembre-se de inserir dois espaços ao fim de cada item antes de pular de linha com o Enter.


### Lista não ordenada com '`*`':

* Item 01
* Item 02
* Item 03
* Item 04
* Item 05

__*Como fazer:*__

```
* Item 01
* Item 02
* Item 03
* Item 04
* Item 05
```

### Lista não ordenada com '`-`':

- Item 01
- Item 02
- Item 03
- Item 04
- Item 05

__*Como fazer:*__

```
- Item 01
- Item 02
- Item 03
- Item 04
- Item 05

```


### Lista não ordenada  com subitens com '`+`' . 
__obs: O mesmo pode ser feito com os sinais acima. Para fazer, vá para próxima linha, pressione TAB e coloque o sinal que for de sua preferência.__

+ Item 01
    + Item 02
    + Item 03
+ Item 04
+ Item 05

__*Como fazer:*__

```
+ Item 01
    + Item 02
    + Item 03
+ Item 04
+ Item 05
```

### Lista não ordenada com espaçamento entre os itens:

* Item 01

* Item 02
* Item 03
* Item 04
* Item 05

__*Como fazer:*__

```
* Item 01

* Item 02
* Item 03
* Item 04
* Item 05
```

### Lista ordenada, posso manter o mesmo numeral que o MarkDown ordena corretamente.

1. Item 01
1. Item 02
1. Item 03
1. Item 04
1. Item 05

__*Como fazer:*__

```
1. Item 01
1. Item 02
1. Item 03
1. Item 04  
1. Item 05
```


### Lista ordenada 2

1994\. Brasil   
1998\. França  
2002\. Brasil

__*Como fazer:*__

```
1994\. Brasil

1998\. França  
2002\. Brasil
```
<a id="link11"></a>

## Highlight - Destacar trechos de códigos

Podemos destacar uma linha de comando ou um bloco de código.

### 1) Linha de código (acrescentar o sinal de crase no início e no fim do código):

Exemplo:

`npm init`  
`mkdir <nome da pasta>`

__*Como fazer:*__
```
`npm init`  
`mkdir <nome da pasta>`
```
### 2) Bloco de Códido com o estilo da linguagem em questão.

Exemplo:

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

  ### 3) Sintax Hightlighting com o estilo da linguagem
**OBS: Para dar destaque ao código com o estilo, basta declarar a linguagem logo após as crases iniciais (no exemplo abaixo foi definido Javascript).**

Exemplo:


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

__*Como fazer:*__

  ```

  ```javascript
describe ('Istagram interation', () => {

  beforeEach(() => {
    cy.visit("https://www.instagram.com")
  })

 it ('contain "Instagram"', () => {
   cy.title()
    .should('contain', 'Instagram')
    cy.wait(3000) 
  })```
```




 
