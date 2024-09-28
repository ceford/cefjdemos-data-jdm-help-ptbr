<!-- Filename: Help4.x:Smart_Search:_Content_Maps  / Display title: Pesquisa Inteligente: Mapas de Conteúdo -->

## Descrição

A página *Pesquisa Inteligente: Mapas de Conteúdo* mostra os mapas de conteúdo atualmente no índice da Pesquisa Inteligente. Mapas de conteúdo permitem que você faça referência cruzada do seu conteúdo indexado (artigos, etc.) com informações meta relacionadas, como a categoria em que ele está localizado. Cada item de conteúdo que é indexado pela Pesquisa Inteligente é adicionado a um ou mais mapas de conteúdo que podem ser usados como filtros ao pesquisar no índice.

Os mapas de conteúdo são divididos em duas partes:

- Grupo de Mapas: Estes são super-contêineres para um tipo particular de informação. Por exemplo, um Grupo de Mapas pode ser *Tipo*, *Categoria*, *Evento*, *Idioma* ou *Autor*.
- Mapa de Conteúdo: Mapas de conteúdo são os valores reais para a informação meta em um determinado Grupo de Mapas. Os Mapas de Conteúdo são, por exemplo, os nomes das categorias ou autores.

Estes Grupos de Mapas e Mapas de Conteúdo formam o painel de pesquisa avançada disponível no front-end. Para cada Grupo de Mapas pode haver uma lista de seleção suspensa e os Mapas de Conteúdo são adicionados como valores à lista respectiva. Desenvolvedores de sites mais avançados podem substituir os layouts padrões e usar listas de seleção múltipla ou caixas de seleção em vez disso.

É importante notar que Grupos de Mapas e Mapas de Conteúdo de diferentes tipos de conteúdo são mesclados em uma única lista. Um artigo do Joomla em uma categoria chamada *Notícias* e um feed de notícias ou contato em uma categoria com o mesmo nome são mapeados para o mesmo Mapa de Conteúdo no mesmo Grupo de Mapas. Isto é um pouco como marcar diferentes tipos de conteúdo com o mesmo rótulo. O efeito é que o visitante do seu site não precisa saber como seu conteúdo está classificado para configurar os filtros corretos para encontrá-lo.

A tela de mapas de conteúdo mostra todos os Grupos de Mapas no índice da Pesquisa Inteligente junto com um número indicando o número de Mapas de Conteúdo dentro desse Grupo de Mapas e os itens dentro de um Mapa de Conteúdo. Clicar no número de um Grupo de Mapas permite que você veja o Mapa de Conteúdo dentro desse Grupo de Mapas junto com o número de itens de conteúdo que pertencem a esse Mapa de Conteúdo. Um item de conteúdo pode pertencer a múltiplos Mapas de Conteúdo dentro de um Grupo de Mapas, bem como a múltiplos Grupos de Mapas.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens de Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Se você é novo na Pesquisa Inteligente, então deveria ler o [guia rápido de Pesquisa Inteligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Como acessar

- Selecione **Componentes → Busca Inteligente → Mapas de Conteúdo** no menu do Administrador.

## Captura de Tela

![mapas de conteúdo da pesquisa inteligente](../../../ptbr/images/smart-search/smart-search-content-maps.png)

## Cabeçalhos de Coluna

- **Status** O status do item de conteúdo dentro da Busca Inteligente. Alterar o 
  status afeta apenas se o item de conteúdo está disponível nos resultados de busca
  e não afeta o item de conteúdo em si.
- **Título** O título do Grupo de Mapas ou Mapa de Conteúdo.
- **Mapas** O número de mapas dentro do Grupo de Mapas. Selecionar o
  número mostrará os mapas dentro do Grupo de Mapas.
- **Conteúdo Indexado Publicado** O número de itens de conteúdo publicados
  no Grupo de Mapas. Selecionar o número mostrará os itens de conteúdo publicados
  dentro do Grupo de Mapas.
- **Conteúdo Indexado Não Publicado** O número de itens de conteúdo não
  publicados no Grupo de Mapas. Selecionar o número mostrará os itens de conteúdo 
  não publicados dentro do Grupo de Mapas.

## Barra de Ferramentas

- **Ações** Revela uma lista de ações para Itens selecionados. Marque uma
  ou mais caixas de seleção de Itens para ativar a lista.
  - **Publicar**. Torna os Grupos de Mapas selecionados ou Mapas de Conteúdo disponíveis para
    visitantes do seu site.
  - **Despublicar.** Torna os Grupos de Mapas selecionados ou Mapas de Conteúdo
    indisponíveis para visitantes do seu site. Um Grupo de Mapas não publicado
    não será exibido como uma lista de seleção na interface do usuário. Um Mapa de Conteúdo não publicado
    não aparecerá na lista de seleção do Grupo de Mapas no qual está presente. Reindexar 
    não altera o estado de publicação dos Grupos de Mapas ou Mapas de Conteúdo.
- **Excluir** Exclui os Grupos de Mapas ou Mapas de Conteúdo selecionados. Funciona
  com um ou vários Grupos de Mapas ou Mapas de Conteúdo selecionados. Você pode
  recuperar Grupos de Mapas ou Mapas de Conteúdo excluídos executando novamente o indexador
  do Smart Search.
- **Estatísticas** Mostra algumas estatísticas básicas sobre o Smart Search.

*Traduzido por openai.com*

