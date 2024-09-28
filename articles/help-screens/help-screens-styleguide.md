<!-- Filename: Help4.x:Help_screens_styleguide  / Display title: Guia de Estilo das Telas de Ajuda -->

<div class="alert alert-warning">
Este guia de estilo é para a instalação do Joomla MediaWiki (docs.joomla.org).
</div>

Este é um trabalho em progresso e deve ser usado como uma diretriz para a criação de telas de ajuda para **Joomla 3.x**. As telas de ajuda que existem no Joomla! Docs Wiki estão sendo acessadas por cada instalação do Joomla! usando o sistema de ajuda padrão. Ao seguir este guia de estilo, o Projeto Joomla! pode oferecer consistência em todas as telas de ajuda, permitindo uma navegação mais fácil.

Se você tiver uma pergunta, publique-a na página de discussão associada à tela de ajuda, clicando na aba ***Discussão*** no topo da página da tela de ajuda.

## Layout da Página de Tela de Ajuda

### Descrição

Cada tela de ajuda deve ter uma seção de "**Descrição**". Esta seção entra em mais detalhes sobre o que a tela faz e é usada em tabelas de tela de ajuda ao longo deste wiki. <a href="https://docs.joomla.org/Menu_Management#Menu_Management_Help_Screens" class="mw-redirect" title="Menu Management">Aqui está um exemplo de uso</a>.

Não há um formato específico para essa seção porque a descrição deve estar diretamente correlacionada com o propósito e funcionalidade da tela. Podem haver subseções na descrição que detalhem informações mais específicas. Tente manter a descrição curta e direta ao ponto; se a descrição for longa, considere usar pontos de bala para resumir.

## Como Acessar

Toda e qualquer tela de ajuda deve ter uma seção **Como Acessar** que descreva os passos necessários para acessar a tela descrita. Isso pode ser redundante, pois o usuário deve estar na tela do administrador para ter acessado a tela de ajuda. Lembre-se, as telas de ajuda podem ser acessadas de várias maneiras diferentes. Por exemplo, alguém usando um motor de busca para descobrir como fazer algo pode encontrar uma tela de ajuda no wiki sem nunca ter acessado o sistema de ajuda.

#### Notas:

- Se a forma de acessar a tela for a partir de outra tela, o nome dessa tela deve ser um link para sua tela de ajuda.
- Você "clica" em botões, incluindo botões de barra de ferramentas, mas você "seleciona" itens de menu. O uso consistente dessa terminologia deve ajudar os usuários.
- Para facilitar a renderização da seta para a direita ( → ), **Este apontando → para aquele**.

### Captura de Tela

Captura de tela mostrando a aparência geral da tela.

#### Notas:

- As imagens de captura de tela podem ter qualquer largura, mas imagens maiores devem ter o \|800px adicionado na fonte.
- O nome do arquivo deve seguir nossa 
  <a href="https://docs.joomla.org/JDOC:Image_naming_convention"
  class="mw-redirect" title="JDOC: Convenção de nomeação de imagem">convenção padrão de nomes</a> para telas de ajuda.
  **Help-3x-**\<caminho-do-sistema-de-menu-em-minúsculas-separado-por-travessões\>**-screen-en.png**.
  Por exemplo, uma captura de tela da tela do Gerenciador de Artigos seria
  **\[\[File:Help-3x--content-article-manager-screen-en.png\]\]**.
- O nome do arquivo deve sempre incluir um código de idioma no final do nome, para o inglês -en é adicionado.
- Você pode usar arquivos .png ou .jpg.

## Campos do Formulário (por Aba)

### Aba Detalhes

Esta seção deve ser incluída apenas em telas de ajuda que descrevam
telas que incluam um formulário. Isso inclui todas as telas de adicionar/editar,
mas também inclui telas como Configuração Global do Site
e pop-ups modais como <a
href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options"
title="Help4.x:Components Article Manager Options">Help4.x:Componentes
Opções do Gerenciador de Artigos</a>.

### Outros Tipos de Abas

Se os campos estiverem agrupados em conjuntos de campos ou abas, então agrupe os campos sob
subtítulos.

### Cabeçalhos de Coluna

Esta seção deve ser incluída apenas em telas de ajuda que descrevam
telas de gerenciamento do back-end; isto é, onde você tem uma lista de itens sendo
exibidos. Esta seção deve descrever cada uma das colunas da lista.

### Filtros da Lista

Esta seção deve ser incluída apenas em telas de ajuda que descrevam
telas de gerenciamento do back-end; isto é, onde você tem uma lista de itens sendo
exibidos. Esta seção deve descrever como usar os filtros da lista para
filtrar o conteúdo da tela. Veja
<a href="https://docs.joomla.org/Screen.content.15#List_Filters"
title="Screen.content.15">Screen.content.15#Filtros_da_Lista</a> para um exemplo
da versão 1.5.

### Opções

Esta seção deve ser incluída apenas em telas de ajuda onde a tela
tem um botão de ferramenta Opções que abre uma sub-tela de opções modal. Se
existirem muitas opções e a tela de ajuda se tornaria excessivamente longa
se fossem descritas aqui, então, faça um link para uma tela de ajuda separada
com um sufixo "\_Opções". Por exemplo, veja <a
href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options"
title="Help4.x:Components Article Manager Options">Componentes: Opções
do Gerenciador de Artigos</a>.

Como a tela de opções modal geralmente é dividida em abas, você deve adicionar uma
subseção sob esta seção para cada aba. Por exemplo, se houver uma aba rotulada "Layout de Edição", você deve adicionar um título de terceiro nível com esse nome e, dentro dessa subseção, descrever cada um dos campos disponíveis. Você deve começar cada subseção com uma captura de tela do painel de opções apropriado.

### Barra de Ferramentas

Obviamente, esta seção deve ser incluída apenas em telas de ajuda onde uma
barra de ferramentas está presente.

Descreve os botões disponíveis e suas funções associadas. Use
**pedaços** aqui porque muitos serão os mesmos para diferentes telas.
Melhor fornecer uma imagem da barra de ferramentas.

A primeira palavra deve sempre ser um verbo e, a menos que seja um verbo irregular,
também deve terminar com a letra "s". Isso significa que você deve
estruturar a descrição como se estivesse usando a palavra "isso" como o
sujeito, mas deixando o sujeito fora da frase. Isso tornará a
frase um fragmento de sentença. Por exemplo:

- Em vez de "Para encontrar tesouros enterrados, clique neste botão."
  - Diga, "Encontra tesouros enterrados."
- Em vez de "Você pode clicar neste botão para inserir uma imagem de John
  Stamos no documento atual."
  - Diga, "Insere uma imagem de John Stamos."
- Em vez de "Informe-se de que uma imagem de John Stamos é a mesma
  coisa que um tesouro enterrado."
  - Diga, "Informa que uma imagem de John Stamos é a mesma coisa que
    um tesouro enterrado."

Como muitas barras de ferramentas são as mesmas em várias telas, a
convenção de nomeação de arquivos de imagem das barras de ferramentas tem como objetivo tornar
fácil reutilizar imagens de barras de ferramentas sempre que possível. As imagens das barras de ferramentas devem seguir esta convenção de nomenclatura: Help\<versão\>-Toolbar-\<listadeicones\>.png, onde
\<listadeicones\> é uma lista separada por '-' das legendas da barra de ferramentas. Cada palavra
deve ser capitalizada, espaços e '&' removidos. Por exemplo:
Help30-Toolbar-Novo-Editar-Deletar-Opções-Ajuda.png

### Processo em Lote

Esta seção deve ser incluída apenas em telas de ajuda onde a tela
possui um recurso de processo em lote. Por exemplo, veja
<a href="https://docs.joomla.org/Help4.x:Components_Banners_Categories"
title="Help4.x:Components Banners Categories">Componentes: Categorias de Banners</a>.

### Dicas

Como o nome sugere, esta seção deve incluir dicas, sugestões,
recomendações que possam ajudar o usuário a realizar tarefas
relacionadas à tela.

*Traduzido por openai.com*

