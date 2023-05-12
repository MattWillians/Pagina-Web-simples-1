# Pagina-Web-simples-1
uma pagina web desenvolvida através de cursos feitos pela plataforma Alura


###
# SOBRE O HTML
###

O HTML é uma Linguagem de marcação textual usada para estruturar paginas WEB. Ele é a principal fonte de estrutura para todas as paginas web e suas tags são usadas para identificar o que estamos passando de informação para as maquinas que acessam nossas pagnias.

as tags HTML são criadas usando o sinal de "menor que" ( < ) em seguida o nome da tag, e por fim, o sinal de "maior que" ( > ) e o final da tag é dado da mesma forma, porem, antas do seu nome é dado com uma barra "/", porem isso não é necessario em tags que possuem self-closing (auto-fechamento)

 ```
 <!--Tag que precisa de fechamento--> <-- COMENTARIO EM HTML
     
         <h1>Olá Mundo!</h1>

 <!--Tag de auto fechamento--> <-- COMENTARIO EM HTML
    
     <img src="banner.jpg">

Tipos de Tag

tags podem ser caracterizadas com "2 tipos primitivos": 1. Nivel de bloco (block-level), 2. Em linha (inline). 

Elementos em nivel de BLOCO ocupam toda largura do elemento pai (no caso de uma pagina, ele vai ocupar do canto esquerdo até o direito todo de onde esta, mas vale o mesmo para um grupo) este tipo de elemento tambem é chamado de "container"

Já os elementos inline ocupam o seu exato espaço na pagina, ou seja, seu tamanho acaba exatamente no tamanho aparente

Mais algumas tags: 

1. <!DOCTYPE html>
Esta tag informa ao navegador que estamos usando a ultima versão da linguagem de marcação HTML

2. <html>
representa o começo de fato da nossa pagina, tudo dentro dessa tag se faz referente ao que é conteudo dentro de uma pagina Web

3. <body>
representa todo o conteudo em texto, imagem e videos que o usuario vê e interage na pagina html

4. <script>
Este elemento diz respeito a um arquivo script que possa estar dentro do nosso projeto, é passado para ele o local desse script usando o método SRC

5. <head>
Informações que o documento passa ao navegador para serem interpretadas, como por exemplo titulo, links, imagem da folha, link para o CSS de estilo

6. <meta>
Define os metadados ou seja, informações do documento HTML como dito acima

7. <link>
É uma tag vazia, que contem apenas atributos que fazem relação com documentos HTML como recursos externos, é comum ser usado para vincular uma folha de estilo externa, tambem é usada para definir o favico da pagina (icone do navegador)

8. <style>
é usado para declarar o estilo (CSS) de um documento

Falando de TAGS, Temos tambem as TAGS semânticas, são tags que possuem um significado que trazem sentido a uma pagina HTML, organizando tudo de forma que quem vê, entenda a organização dos itens. Por exemplo: usar a tag: <header> para cabeçalhos, ou indicar que o texto é um paragrafo usando o <p>.

algumas das tags Semânticas são:

1. <header>
É usaado para o cabeçalho da pagina, tudo referente ao cabeçalho pode ser colocado nele

2. <main>
É usado para identificar onde fica o conteudo principal da pagina em questão, ou seja, todo o conteudo principal

3. <footer>
É usado para identificar o rodapé de sua pagina web, assim como o cabeçalho. Geralmente é usado para colocar a marca registrada do criador da pagina.

4. <section>
Pode ser entendida como um conjunto de informações que se relacionam, formando uma sessão dentro de seu documento HTML.

5. <article>
Funciona da mesma forma que uma section.

6. <container>
Funciona da mesma forma que um article

7. <aside>
usada para colocar informações ao canto esquerdo da pagina em forma de um container, sem atrapalhar os headers nem as sections

8. <nav>
Identifica a barra de navegação da pagina Web, ela vai ficar presa no teto da pagina, mesmo dando scroll ela vai se manter no mesmo local

9. <ol>
A lista Ordenada, (<ol>) é usada para declarar uma lista de itens onde sua ordem importa para rodar o processamento.

10. <ul>
Unordered List, ou lista não ordenada, é o mesmo que uma lista ordenada, porem, a ordem dos objetos não importa nesse caso

11. <li>
Representa um item da lista, que deve ser colocada em uma <ol> ou <ul>


Tags sem semântica

as tags que não possuem semantica não entregam significado ao texto em questão, elas são para fins de separação e estilização dos objetos.

1. <div>
Usado para criar uma "caixa de itens" dividindo os itens de sua pagina HTML por sessões para que não sejam perdidos

2. <span>
Serve para adicionarmos estilo a um trecho especifico de texto dentro de nosso documento HTML, sem necessidade de modificar milhares de coisas

3. <b>
Mesma função do span, a diferença é que o <b> deixa o texto em negrito

4. <i>
deixa o texto em questão em italico
```




















