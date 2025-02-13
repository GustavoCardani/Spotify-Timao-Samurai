# Spotify-Timao-Samurai
Uma cópia do Spotify personalizada com o brasão do Corinthians.

No HTML foram utilizadas tags como <div>, que é um elemento de nível de bloco, cria containers bloco,  e <span> é um elemento em linha, para frases por exemplo, também Section, para todo conteúdo relacionado ao mesmo assunto.
Exemplificando: A Div é a casa e a Section os quartos.
Para cada tag Div, Section, existe uma configuração pré-escrita nos Scripts do JS. 
Lembre-se, não podemos esquecer de criar a caixa vazia para adicionar os elementos - CSS e JavaScript.

Existe um documento chamado "reset.css". Ele serve para limpar os excessos que vem pré-programados pelas tags.

Também existe um documento chamado "media-queries.css". Uma media query consiste de um media type e pelo menos uma expressão que limita o escopo das folhas de estilo usando media features, tal como largura, altura e cor. Media queries, adicionadas no CSS, deixam a apresentação do conteúdo adaptado para vários tipos de dispositivos, não precisando mudar o conteúdo em si. Isso melhora a responsividade do seu site. 

Existe uma "main-content-rem.css" que está com as medidas em REM, ao invés de PX.
Um documento "vars.css" para os Cards - cores. 

Documento script.js está todo o JS relacionado ao conteúdo da página. 
Documento search.js está todo o JS relacionado a barra de pesquisa.

Para testar a pesquisa da minha search box eu criei uma API (servidor) fake. Utilizando:  

npm i json-server -g (para criar um servidor fake)

json-server --watch api-artists/artists.json (para ativar o server)

DOM = (Document Object Model) Modelo de Objeto de Documentos
 É uma representação, uma “árvore”, daquele documento (o HTML) que vão ter todos os elementos que a gente compos nos códigos. 
É como se cada elemento do HTML fosse um nó da árvore, e a árvore que liga tudo é o DOM. 

O JavaScript consegue alterar, mostrar ou não, coisas através desse recurso que é o DOM.
Conseguimos colocar comportamento, manipulá-los com o javascript. Por isso você vai encontrar muitas contantes declaradas nesses documentos JS. 

Bom projeto!
