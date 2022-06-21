
# Projeto Lessons Learned

Esta página foi desenvolvida como projeto do bloco 3 do módulo de fundamentos da trybe
# Requisitos do projeto

## 1. Adicione uma cor de fundo específica para a página

<details>

<summary>A página deve possuir uma cor de fundo <code>rgb(253, 251, 251)</code>
</summary><br/>

**O que será testado:**

- Possuir cor de fundo: `rgb(253, 251, 251)`.

</details>

## 2. Adicione uma barra superior com um título

<details>

<summary>Essa barra superior deve possuir o <code>id</code> igual a <code>cabecalho</code> e deve ser fixa no topo da página com a propriedade <code>top</code> tendo <code>0</code>. O título deve estar dentro da barra e ser um elemento <code>h1</code> com <code>id</code> igual a <code>titulo</code>.
</summary><br/>

**O que será testado:**

- A barra possui o ID `cabecalho`;
- A barra superior deve ser fixa no topo da página, leia mais sobre ela [aqui](https://www.w3schools.com/css/css_positioning.asp);
- A barra deve ter a propriedade `top` tendo o valor `0`;
- O título deve estar dentro da barra e possuir o ID `titulo`, além de ser uma tag `h1`.

</details>

## 3. Adicione uma foto sua à página

<details>

<summary>A foto deve ser inserida utilizando uma tag <code>img</code> com o ID <code>minha_foto</code>.
</summary><br/>

**O que será testado:**

- A foto deve ser inserida utilizando uma tag img com o ID `minha_foto`.

</details>

## 4. Adicione uma lista de lições aprendidas à página

<details>

<summary>A lista deve possuir <strong>10</strong> itens, ser numerada e possuir o ID <code>licoes_aprendidas</code>.
</summary><br/>

**O que será testado:**

- A lista deve ser numerada;

- Possuir o id `licoes_aprendidas`;

- A lista deve possuir 10 itens.

</details>

## 5. Crie uma lista de lições que ainda deseja aprender para a página

<details>

<summary>A lista deve possuir <strong>10</strong> itens, não ser numerada e possuir o ID <code>licoes_a_aprender</code>.
</summary><br/>

**O que será testado:**

- A lista não deve ser numerada;
  
- Deve possuir o ID `licoes_a_aprender`;

- A lista deve possuir 10 itens.

</details>

## 6. Adicione um rodapé para a página

<details>

<summary>O rodapé deve utilizar a tag <strong>footer</strong> e possuir o ID <code>rodape</code>.
</summary><br/>

**O que será testado:**

- O rodapé deve possuir o ID `rodape`.

</details>

## 7. Insira pelo menos um link externo na página

<details>

<summary>A configuração desse link deve ser feita para abrir em uma nova aba do navegador. 
</summary><br/>

**O que será testado:**

- Ao clicar no link, será aberto uma nova aba no navegador, [leia mais sobre isso aqui](https://www.horadecodar.com.br/2019/11/21/como-fazer-para-o-link-abrir-em-nova-aba-tag-a-do-html/)

</details>

## 8. Crie um artigo sobre o seu aprendizado

<details>

<summary>O artigo deverá ser uma tag html <code>article</code> e deve possuir mais de 300 <strong>caracteres</strong> e menos de 600.
</summary><br/>

**O que será testado:**

- A `tag` `article` deve ser utilizada;
- O artigo deve ter mais de 300 caracteres e menos de 600.

</details>

## 9. Crie uma tag html `aside` que contenha uma breve descrição sobre você

<details>

<summary>A tag <code>aside</code> deverá possuir mais de 100 <strong>caracteres</strong> e menos de 300.
</summary><br/>

**O que será testado:**

- A `tag` `aside` deve ser utilizada;
- A sua descrição deve ter mais que 100 caracteres e menos que 300.
- Tudo que estiver dentro da tag `tag` `aside`, será contabilizado como caracter.


</details>

## 10. Aplique elementos HTML de acordo com o sentido e propósito de cada um deles

<details>

<summary>Para tornar o seu site mais acessível e melhorar o seu ranqueamento em mecanismos de busca na Web, a sua página deve conter os seguintes elementos: <code>article</code>, <code>header</code>, <code>aside</code> e <code>footer</code>.
</summary><br/>

**O que será testado:**

- Validar se a página possui um elemento `article`;
- Validar se a página possui um elemento `header`;
- Validar se a página possui um elemento `aside`;
- Validar se a página possui um elemento `footer`.

</details>

## 11. Teste se a semântica da sua página está aprovada pelo site [CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/)

<details>

<summary>Teste se a semântica da sua página está aprovada pelo site <a href="https://squizlabs.github.io/HTML_CodeSniffer/">CodeSniffer</a>.
</summary><br/>

**O que será testado:**

- O seu site deve passar com `0 errors` na verificação de semântica do site [CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/).

</details>

---
 
# Requisitos Bônus

## 12. Adicione uma tabela à página

<details>

<summary>A página deve possuir uma tabela
</summary><br/>

**O que será testado:**

- A página possui um elemento `<table>`, leia sobre [aqui](https://www.w3schools.com/html/html_tables.asp).

</details>

## 13. Utilize o Box model

<details>

<summary>Altere <code>margin</code>, <code>padding</code> e <code>border</code> dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes.
</summary><br/>

**O que será testado:**

- Verificar se algum elemento da página teve a `margin` modificada;
- Verificar se algum elemento da página teve o `padding` modificado;
- Verificar se algum elemento da página teve a `border` modificada.

</details>

## 14. Altere atributos relacionados às fontes

<details>

<summary>Modifique o estilo da sua tipografia alterando o tamanho de letra, a cor, o espaçamento entre as linhas e a <code>font-family</code>.
</summary><br/>

**O que será testado:**

- Altere o tamanho da letra;
- Altere a cor da letra;
- Altere o espaçamento entre as linhas;
- Altere o `font-family`.

</details>

## 15. Posicione a tag `article` e a tag `aside` uma ao lado do outra

<details>

<summary>Adicione ao elemento posicionado no lado esquerdo a classe <code>lado-esquerdo</code> e ao elemento posicionado no lado direito a classe <code>lado-direito</code>.
</summary><br/>

**O que será testado:**

- Utilizar a classe `lado-esquerdo`;
- Utilizar a classe `lado-direito`;
- Verificar se os elementos com as classes lado-direito e lado-esquerdo estão posicionados corretamente.

</details>

## Autores

- [@iamlucasgomes](https://github.com/iamlucasgomes)


## Live - Demo

Para ver esta página online, acesse [clicando Aqui](https://iamlucasgomes.github.io/project-lessons-learned)

## Stack utilizada

**Front-end:** HTML5 & CSS3

