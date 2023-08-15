
 <h1><em>Html</em></h1>
 
<h3><bem>Semântica Html</em></h3>
   
 Significa a melhor compreensão do HTML para o computador, com o HTML5, temos a opção de dividir melhor as tags. E, utilizando o próprio HTML5 semântico, ficou ainda mais simples a compreensão para o computador.

<h3><em>Tags</em></h3>

 Tag HTML é uma marca que indica ao navegador que um determinado texto ou elemento deve ser interpretado conforme as regras do HTML.

 Principais Tags:

  <b>Tags estruturais;</b>

 - Tag <.html><./html>: Essa tag está sempre no começo e no fim da página web. Ela limita onde o código começa e termina.
 - Tag <.head><./head>:Utilizada para definir o começo e o fim do cabeçalho de um documento HTML, a qual também contém informações gerais sobre o documento, incluindo títulos e links.
 - Tag <.meta>: Essa tag traz dados básicos sobre o documento, como autor e data de criação.
 - Tag <.body><./body>: Indica para o navegador o corpo do documento HTML, ou seja, a parte principal da página web.
 - Tag <.section><../section>: É utilizada para definir seções em um documento, separando conteúdos como capítulos, artigos, cabeçalhos e etc.
 - Tag <.title><./title> : Define o título do documento HTML. Esse é o nome que é exibido no topo da janela do navegador quando a página é aberta.
 - Tag <div></div>: Tag que funciona como um contêiner e define um bloco inteiro de conteúdo. Muito útil para organizar elementos na página web.
 - Tag <nav></nav>: A tag <nav> é usada para representar uma seção com conjunto links de navegação, dentro do documento atual ou para outro documento.
 - Tag <article></article>: Tag que define um conteúdo independente e completo de outros, artigos com conteúdos que fazem sentido por si só.
 
<b>Tags de conteúdo</b>

- Tags HTML de título <.h1><./h1>,  <.h2><./h2>, <.h3><./h3>, <.h4><./h4>, <.h5><./h5>, <.h6><./h6>: Definem o tamanho do título do documento, sendo <.h1> de maior valor hierárquico e <.6> de menor valor hierárquico.
- Tags HTML de texto <.p><./p>: Define o começo e o fim de um parágrafo. Pode ser utilizado ao lado de align para indicar o alinhamento do trecho.
- Tag <.i></i>, <u></u>: Tag <.i><./i> formata textos em itálico e a tag <.u><./u> em sublinhado. Ambas requerem abertura e fechamento com o conteúdo entre elas.
- Tag <.br><./br>: Tags utilizadas para quebra de linha em um texto. É mais comum a utilização da tag fechada <./br> pois ela é suportada tanto em HTML quanto XHTML.
- Tag <.strong><./strong>: Tag utilizada para representar uma parte do texto que seja importante pois o texto fica em negrito no navegador web.
- Tag <.font><./font>: Tag <.font><./font> apesar de não ser compatível com HTML5 como visto na imagem acima, é utilizada no HTML para definir o estilo da fonte para o texto
- Tag <.span><./span>: Tag utilizada para agrupar elementos para fins de estilo, porém só deve ser usado quando não houver outra alternativa de elemento semântico.

<b>Tag de link HTML </b>

- Tag <.a><./a>: Cria um link e atribui elementos a ele, como:
href: vincula a URL do documento a algo;
name: o nome âncora;
target: identifica se o link deve ser aberto na mesma janela, em nova aba ou nova janela;
rel: aponta os tipos de link que avançam;
rev: define os links que podem reverter uma ação;
acesskey: para atribuir uma tecla a um comando;
shape e coords: para uso com formas de objetos;
tabindex: determina a ordem das guias que são exibidas para o usuário;
onclick: define um evento JavaScript para o click no item;
onmouseover: define um evento JavaScript caso o usuário passe com o ponteiro do mouse em cima do item;
onmouseout: define um evento JavaScript caso o ponteiro do mouse saia do item.

<b>Tags HTML de multimídia</b>

- Tag <.img/>: A tag <.img> permite inserir imagens na página web e não possui fechamento, contendo apenas atributos nela.
- Tag <.audio><./audio>: Tag <.audio> é utilizada para definir sons como música ou outros tipos de áudio. O HTML5 suporta mp3, onda e ogg.
- Tag <video></video>: A tag <.video> é usada para importação de arquivos de vídeo. HTML suporta três formatos de vídeos compatíveis com essa tag (mp4, webM e ogg).

<b>Tags HTML de listas</b>

  - Tag <.ol><./ol>: Cria listas ordenadas. Deve ser acompanhado de start, para indicar o começo da lista e type, para apontar o tipo de caractere que será ordenado.
  - Tag <.ul><./ul>: Cria listas não ordenadas. Precisa do type para apontar o tipo de item que fará parte da lista.
  - Tag <.li><./li>: Os elementos <.li><./li> define cada item da lista, que fazem parte de listas ordenadas ou não ordenadas.

<b>Tag  de comentários</b>

- Tag <.!– –> Essa tag cria um comentário em qualquer parte do código-fonte. Útil para orientar pessoas em modificações futuras. Ou para relembrar sobre como cada linha funciona.

<b>Tag HTML de estilos e scripts</b>

- Tag <.style><./style>: Essa tag define o estilo de parte ou de todo o conteúdo da página web com arquivo .css importado.
- Tag <.script><./script>: Tag utilizada para a importação de um documento Javascript para interações do lado cliente com conteúdo dinâmico.

<b>Tag HTML para recebimento de dados</b>

 <.input type=”text”>, <.input type=”email”>, <.input type=”Submit”>

 ![image](https://github.com/Tuanesfreitas/aula.front-end/assets/136396041/ef9aeb30-af02-4fb7-a765-915819cf0f7a)

Tags do tipo <input> são utilizadas para o recebimento de dados do usuário, possuindo diferença entre elas como o tipo do atributo que irá receber (type).

<h3><em>Classes</em></h3>

As classes são uma forma de identificar um grupo de elementos. Através delas, pode-se atribuir formatação a VÁRIOS elementos de uma vez. Exemplo:

      .classe1 {
        background: blue;
      }

Código HTML:

      <!DOCTYPE html>
      <html lang="pt-br">
        <head>
          <title></title>
          <meta charset="utf-8">
        </head>
        <body>
          <div class="classe1">Div1</div>
          <div class="classe1">Div2</div>
          <div class="classe1">Div3</div>
          <div class="classe1">Div4</div>
          <div class="classe1">Div5</div>
        </body>
      </html>
Então, todas as 'divs' que estiverem com a classe "classe1" estarão com um background azul(blue).

<h3><em>Ids</em></h3>

O atributo id é um identificador único que é usado para especificar o documento, ele é usado no CSS e JavaScript para executar uma determinada tarefa para um elemento único. 
Em CSS, o atributo id é escrito usando o símbolo # seguido do id.

Exemplo:

![image](https://github.com/Tuanesfreitas/aula.front-end/assets/136396041/6249be95-fb18-435a-9b6b-1e1a240af326)

<b>Section</b>

A tag section é utilizada para marcar as seções de conteúdo de uma página. Com Esse elemento agrupamos de forma lógica nosso conteúdo, separando a informação em áreas diferentes. O principal objetivo é retirar essa responsabilidade das divs. Tendo como principal diferencial a navegação semântica com HTML 5.

Exemplo: 

![image](https://github.com/Tuanesfreitas/aula.front-end/assets/136396041/c45f0bf8-7ce6-4fff-a62e-07e0df0d2e66)

