<!-- Filename: Help4.x:Component:_Fields  / Display title: Componente: Campos -->

## Descrição

Campos são usados para exibir atributos adicionais de Artigos, Contatos ou Usuários.
Os dados são inseridos em um formulário de Edição do Administrador e exibidos no Site.
Um exemplo:

Suponha que você escreva artigos sobre aspectos da natureza, às vezes sobre Flores, às vezes
sobre Animais. Um campo que você pode querer registrar e exibir para ambos é o
Nome Latim, que exigiria um campo de texto. Outro poderia ser Habitat: Floresta, Lago, Campo,
e assim por diante, exigindo uma lista suspensa. Para flores, você pode querer
registrar a Estação de Floração usando 4 caixas de seleção, uma para cada estação, ou 12
caixas de seleção, uma para cada mês.

Campos vazios no formulário de entrada não são exibidos na saída do Site, então você
pode manter todos os campos em uma lista longa. No entanto, geralmente é melhor usar
categorias para seus Artigos, digamos Flores e Animais. Campos podem ser atribuídos
a mais de uma Categoria. Assim, os campos Nome Latim e Habitat seriam atribuídos
a ambos, mas a Estação de Floração seria atribuída apenas à categoria Flores.

Se um campo não for atribuído a um grupo, ele aparecerá no formulário de Edição em uma
aba Campos. Se um campo for atribuído a um grupo, ele aparecerá em uma aba com
esse nome. Então, para o grupo de Flores, parece apropriado criar um grupo
chamado Dados de Flores (ou apenas Flores, embora usar o mesmo nome para coisas diferentes
seja confuso). E para os outros campos comuns, você pode usar um grupo Natureza.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens da Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação da Lista](jdocmanual?article=help/common-elements/list-pagination).
* [Processo em Lote da Lista](jdocmanual?article=help/common-elements/list-batch-process).

### Artigo Relacionado

* Há um exemplo mais longo do uso de [Campos e Grupos de Campos](jdocmanual?article=user/fields/fields-and-field-groups)
* Há um artigo na Revista da Comunidade que inclui o uso de campos personalizados
em uma categoria para [Criar um banner a partir da descrição da categoria do Joomla](https://magazine.joomla.org/all-issues/july-2024/create-a-banner-from-joomla-s-category-description).

## Como Acessar

* Selecione **Conteúdo → Campos** no menu do Administrador.
* Selecione **Artigos** na lista suspensa *Artigos/Categoria*.
  * Selecione o botão **Novo** na *Barra de Ferramentas* para adicionar um novo campo.
  * Selecione um **Título** da lista para editar um campo existente.

**Nota:** Há uma lista suspensa que permite a criação de Campos para uma
Categoria e para Email no componente de Contato. Eles exigem alguma experiência em codificação para preparar substituições de template adequadas.

## Captura de Tela

![Lista de campos dos artigos](../../../ptbr/images/fields/articles-fields-list.png)

Existem 16 tipos de campos disponíveis, cada um implementado como um plugin. É provável que mais tipos se tornem disponíveis no futuro.

*Traduzido por openai.com*

