<!-- Filename: Help4.x:Menu_Item:_Search  / Display title: Pesquisa -->

## Descrição

O tipo de item de menu **Busca** é usado para criar uma página para Resultados de Busca Inteligente. Ele pode ser usado em conjunto com um módulo de Busca Inteligente para controlar o layout de uma Página de Resultados de Busca.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba Integração](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba Exibição da Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba Metadata](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba Atribuição de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Para criar um novo item de menu de Pesquisa:

- Selecione **Menus → \[nome do menu\]** no menu do Administrador
  (por exemplo, **Menus → Menu Principal**). Em seguida...
  - Selecione o botão **Novo** na Barra de Ferramentas. Em seguida...
  - Selecione o botão **Selecionar Tipo de Item de Menu**.
  - Na caixa de diálogo modal, selecione o item **Pesquisa Inteligente** para abrir uma lista e, em seguida, selecione o item **Pesquisar**.

Para editar um item de menu de Pesquisa existente:

- Selecione seu Título na lista Itens: Menus.

## Captura de Tela

![Item de Menu Detalhes da Pesquisa Inteligente](../../../ptbr/images/menu-items/smart-search-search-details-tab.png)

## Campos do Formulário

Se a opção *Usar Global* for selecionada para qualquer opção, o valor padrão de *Pesquisa Inteligente: Opções* será usado.

### Aba de Opções

![Aba de opções de busca do item de menu Pesquisa Inteligente](../../../ptbr/images/menu-items/smart-search-search-options-tab.png)

- **Filtros de Data** Mostrar ou ocultar os filtros de data de início e término na Pesquisa Avançada.
- **Pesquisa Avançada** Mostrar ou ocultar o elemento de Pesquisa Avançada.
- **Expandir Pesquisa Avançada** Mostrar ou ocultar a Pesquisa Avançada em estado expandido.
- **Taxonomia dos Resultados** ...?
- **Descrição dos Resultados** Mostrar ou ocultar uma descrição sob o link nos resultados da pesquisa.
- **Comprimento da Descrição** O número de caracteres da descrição a serem mostrados nos resultados da pesquisa. O padrão é 255.
- **Data do Resultado** ...?
- **URL do Resultado** Mostrar ou ocultar a URL do item de resultado nos resultados da pesquisa. A URL está localizada sob a descrição.

### Aba Avançada

![Aba avançada de busca do item de menu Pesquisa Inteligente](../../../ptbr/images/menu-items/smart-search-search-advanced-tab.png)

- **Exibir Seleção** Mostrar ou ocultar o controle Exibir \# que permite ao usuário selecionar o número de itens a serem mostrados na lista.
- **Paginação** Mostrar ou ocultar o suporte à Paginação. A Paginação fornece links de página na parte inferior da página que permitem ao usuário navegar para páginas adicionais. Esses são necessários se os itens listados não couberem em uma página.
    As seguintes opções estão disponíveis:
    - *Usar Global* Usar o valor padrão da tela de opções do componente.
    - *Automático* Links de paginação mostrados se necessário.
    - *Mostrar* Links de paginação mostrados se necessário.
    - *Ocultar* Links de paginação não mostrados. Nota: Neste caso, os usuários não poderão navegar para páginas adicionais.
- **Resultados da Paginação** Mostrar ou ocultar o número da página atual e o número total de páginas (por exemplo, *Página 1 de 2*) na parte inferior de cada página.
- **Permitir Busca Vazia** Se um filtro for selecionado, permite que uma string de busca vazia inicie uma busca com as restrições do filtro.
- **Você Quis Dizer** Sugerir termos alternativos de busca quando uma pesquisa não produzir nenhum resultado.
- **Explicação da Consulta** Mostrar ou ocultar uma explicação detalhada da pesquisa solicitada.
- **Mostrar Campos de Ordenação** Mostrar ou ocultar campos de ordenação adicionais.
- **Campos de Ordenação Adicionais**: Escolha um ou mais campos pelos quais ordenar os resultados da pesquisa:
  - *Relevância* Ordenar os resultados por relevância
  - *Título* Ordenar os resultados pelo título
  - *Data* Ordenar os resultados pela data
  - *Preço de lista* Ordenar os resultados pelo preço de lista
  - *Preço de venda* Ordenar os resultados pelo preço de venda
- **Direção da Ordenação** Direção para ordenar os resultados da pesquisa.

*Traduzido por openai.com*

