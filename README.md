# #1 Bikcraft

Este é um projeto desenvolvido durante o curso de Web Design da Origamid.
Trata-se de uma página de apresentação de produtos de uma fábrica de bicicletas.


### O que eu aprendi?

- A propriedade ```margin: 0 auto;``` do CSS faz com que o elemento centralize, automaticamente nas margens esquerda e direita.
- Dá pra criar linhas com as pseudopropriedades do CSS ```:after``` e ```:before,``` fazendo ```content: ""``` e definindo o tamanho da linha com ```heigh``` e ```width```;
- Colocando duas classes juntas, por exemplo ```class="btn btn-preto"```, no css ```.btn.btn-preto``` , a segunda classe irá sobrescrever a primeira, usando as definições padrão e mudando as coisas necessárias que sejam específicas para o elemento.
- Além de ```text-align: center``` pode usar também ```text-align: right``` para textos, que não seja o ```float```. Um exemplo é nos itens de um menu de um site, para deixá-los (a lista) na direita.
- Usar ```letter-spacing: .1em``` e ```line-height: 20px``` dá uma visão bonita ao fonte.
- Sempre usar ```alt``` nas imagens.
- Nas definições de CSS os arquivos de CSS listados por último nos <link rel="stylesheet"> irão sobrescrever os primeiros.
- É interessante usar sempre o Lorem Ipsum em português. Ao escrever o texto final é ideal seguir o número de caracteres que está no Lorem Ipsum do protótipo para manter a definição.
- Dá pra colocar inclusive imagens com background:url("../img/linhas.svg"); com o *```:after.``` Usando *```position:absolute``` dá pra ajustar essa imagem mais livremente pelo layout.

***Media queries coringas***
<p> Estilos para tablets <br>

 <code>
@media only screen and (min-width: 768px) and (max-width: 979px) {}
</code>
 </p>
<p> 
   Estilos para smartphones <br>

  <code>

@media only screen and (max-width: 787px) {}
</code>

 </p>

