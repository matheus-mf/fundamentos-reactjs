<h1 align="center">Fundamentos do ReactJS</h1>

## Transpilar

Mesmo os navegadores mais modernos não conseguem entender os sprints do React, por isso é necessário usar o **Babel**.
Ele é responsável por transpilar o código React de uma maneira que os navegadores entendam. E usando os loaders do
**Webpack**, será possível converter _JavaScripts_, _Imagens_ e _Estilos_ de acordo com o que os navegadores esperam.

---

## Componentes

Conjunto isolado de HTMLs e CSSs que podem ser reaproveitado em outros lugares.

### JSX

Os elementos que criamos no React são feitos utilizam do JSX para descrever como a UI deve parecer, com ele pode-se
utilizar HTML no JavaScript.

![componente header](.github/componente-header.png)

### Fragment

Com o Fragment, pode-se agrupar uma lista de componentes filhos sem a adição de nós extras dentro do DOM.

Utilizando componente com Fragment:

![utilizando componente com fragment](.github/utilizando-componente-com-fragment.png)

---

## Propriedades

São informações que podemos passar de um componente pai para um componente filho. As propriedades são passadas para um
componente num formato de atributo, eles são extraídos do parâmetro _pros_ que o componente recebe.

Como passar uma propriedade para componente:

![passando propriedades para os componentes](.github/passando-props.png)

Como pegar a propriedade no componente, já com desestruturação:

![pegando propriedades no componente](.github/pegando-props.png)

Por padrão todo componente em React pode receber um atributo chamado _children_.

Como passar:

![passando propriedade children no componente](.github/passando-children.png)

Usando no componente:

![usando propriedade children no componente](.github/usando-children.png)

---

## Estado e Imutabilidade

---

## Importando CSS e imagens

---

## Listando Projetos da API

---

## Cadastrando Projetos
