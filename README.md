# DOM

## Exercícios de classe 🏫
***1.  Slider de depoimentos***

Dado o arquivo html e css encontrado nesta pasta, crie dentro do elemento `<script>` um código que reproduza [o seguinte comportamento](https://i.imgur.com/DGXHIw7.gif).

**Neste exercício usaremos:**
 - evento de clique
 - seletor de elementos da DOM
 - manipulação de texto dos elementos

Você deverá implementar no mínimo duas funções: 
 - `pessoaAnterior()` 
  - Mudar os conteúdos dos elementos: `.carousel__img`, `.review-text`, `.author__name`, `.author__title` para os conteúdos da pessoa anterior
 - `proximaPessoa()`
  - Mudar os conteúdos dos elementos: `.carousel__img`, `.review-text`, `.author__name`, `.author__title` para os conteúdos da próxima pessoa

Se necessário, crie outras funções e varíaveis além das que já estão dentro do `<script>`

---

***2.  Popup***

Dado o arquivo html e css encontrado nesta pasta, crie dentro do elemento `<script>` um código que reproduza [o seguinte comportamento](https://i.imgur.com/hw6kY0U.gif).

**Neste exercício usaremos:**
 - evento de clique
 - seletor de elementos da DOM
 - manipulação de classes

Você deverá implementar a seguinte função: 
 - `mostrarPopup()` 
  - Colocar a classe *show* no elemento com classe *popup* caso ele não possui-lá e remover caso ele possui-lá

Se necessário, crie outras funções e varíaveis além das que já estão dentro do `<script>`

---

## Exercícios de casa 🏠
***3. Frases motivadoras***

Utilizando o array `frases` encontrado no `<script>` do arquivo HTML encontrado nessa pasta, construa uma página com no mínimo os seguintes elementos:
 - Um título
 - Um parágrafo
 - Um botão

Você também deve implementar no mínimo uma função com o nome `novaFrase()` que será executada no clique do botão e irá buscar do array `frases` uma frase aleatória e colocar essa frase como conteúdo do parágrafo.

Para pegarmos um indíce aleatório de 0 até um tamanho conhecido podemos utilizar a seguinte expressão: `Math.floor(Math.random() * array.length)`. 

`Math.random()` retorna um número de 0 até 1, multiplicamos isso pelo tamanho do array e arredondamos para baixo.

**Neste exercício usaremos:**
 - evento de clique
 - seletor de elementos da DOM
 - manipulação de texto dos elementos

---

***4. Contatos frequentemente contatados***

Utilizando o array `contatos` encontrado no `<script>` do arquivo HTML encontrado nessa pasta, construa uma página com no mínimo elementos já presentes no arquivo HTML.

Você deve:
1. Ordenar o array `contatos` de modo que os 5 primeiros itens sejam os contatos que tenham o maior número de `mensagens`;
2. Criar um novo array com apenas os primeiros 5 elementos do array `contatos` depois de ordenado;
3. Preenchecer os `<li>`s com os dados dos contatos (imagem, nome e descrição);

**Neste exercício usaremos:**
 - seletor de elementos da DOM
 - manipulação de texto dos elementos
 - manipulação de atributo dos elementos

<details>
  <summary>Dicas</summary>
  <ul>
    <li>Podemos usar a função <code>sort()</code> para ordenar o array</li>
    <li>Podemos usar a função <code>slice()</code> para criar um novo array com apenas os primeiros 5 elementos</li>
    <li>Podemos selecionar todos os itens da lista com <code>document.querySelectorAll('li')</code>, dar um loop na lista retornada e para cada item da lista executarmos um <code>document.querySelector()</code> em cada elemento do item da lista</li>
  </ul>
</details>

---

###### tags: `front-end` `módulo 2` `DOM` `JS`
