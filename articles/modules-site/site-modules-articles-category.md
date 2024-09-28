<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category  / Display title: Módulos: Artigos - Categoria -->

## Descrição

O tipo de módulo *Artigos - Categoria* exibe uma lista de artigos publicados de uma ou mais categorias.

### Elementos Comuns

Alguns elementos desta página estão cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [O Módulos: Aba de Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [O Módulos: Aba de Atribuição de Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [O Módulos: Aba Avançada](jdocmanual?article=help/modules/modules-advanced-tab).
* [A Aba Permissões](jdocmanual?article=help/common-elements/edit-permissions).

<!-- ToDo: Um tutorial para mostrar como usar este módulo -->

## Como Acessar

- Selecione **Sistema → Gerenciar Painel → Módulos do Site** no menu do Administrador. Em seguida...
  - Para criar um novo módulo: selecione o botão **Novo** na Barra de Ferramentas. Em seguida...
    - Selecione o tipo de módulo necessário.
  - Para editar um módulo existente:
    - Encontre o módulo na lista de módulos instalados e selecione o link do título na coluna **Título**.

## Captura de Tela

![aba do módulo da categoria de artigos](../../../ptbr/images/modules-site/modules-articles-category-module-tab.png)

## Campos do Formulário

- **Título** O título do módulo. Este é também o título exibido 
  para o módulo dependendo do Campo do Formulário *Mostrar Título*

### Aba Módulo

#### Painel Esquerdo

- **Modo** Selecione o modo a ser utilizado. Se o Modo Normal for escolhido, 
  basta configurar o módulo e ele exibirá uma lista estática de Artigos nos 
  itens de menu aos quais você atribuir o módulo. Se o Modo Dinâmico for escolhido, 
  você ainda pode configurar o módulo normalmente, no entanto, a opção Categoria 
  não será mais utilizada. Em vez disso, o módulo detectará dinamicamente se 
  você está em uma visualização de Categoria e exibirá a lista de artigos dentro 
  dessa Categoria de acordo. Quando o Modo Dinâmico for escolhido, é melhor
  deixar o módulo configurado para exibir em todas as páginas, pois ele decidirá
  se exibe ou não algo dinamicamente.
- **Mostrar na Página do Artigo** Este item aparece se o Modo *Dinâmico* for selecionado.
  Selecione Mostrar ou Ocultar uma Lista de Artigos das Páginas de Artigos. Isso significa que 
  o módulo será exibido dinamicamente apenas nas Páginas de Categoria.

### Aba Opções de Filtragem

![opções de filtragem de categoria de artigos](../../../ptbr/images/modules-site/modules-articles-category-filtering-options-tab.png)

- **Artigos em Destaque** Mostrar ou ocultar ou selecionar Somente Artigos em Destaque.
- **Contagem** O número de itens a serem exibidos. O valor padrão de 0 exibirá 
  todos os artigos.
- **Tipo de Filtragem de Categoria** Incluir ou excluir as categorias selecionadas.
- **Categoria** Selecione uma ou mais categorias.
- **Artigos de Subcategorias** Incluir ou excluir artigos de subcategorias.
- **Profundidade da Categoria** O número de níveis de subcategorias a serem retornados.
- **Tipo de Filtragem de Autor** Incluir ou excluir artigos dos autores selecionados.
- **Autores** Selecione um ou mais autores da lista.
- **Tipo de Filtragem de Alias de Autor** Incluir ou excluir os aliases de autores selecionados.
- **Aliases de Autores** Selecione um ou mais aliases de autores da lista.
- **IDs de Artigos a Excluir** Insira cada ID de Artigo a excluir em uma nova linha.
- **Filtragem de Data** Selecione o tipo de filtragem por data.
- **Campo de Intervalo de Datas** Selecione qual campo de data utilizar para o intervalo.
- **Data de Início do Intervalo** Se o Intervalo de Datas foi selecionado acima, insira uma data de início.
- **Data Final** Se o Intervalo de Datas foi selecionado acima, insira uma data final.
- **Data Relativa** Se Data Relativa foi selecionada acima, insira um valor numérico de dias.
  Os resultados serão obtidos em relação à data atual e ao valor inserido.

### Aba Opções de Ordenação

![opções de ordenação de categoria de artigos](../../../ptbr/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Campo do Artigo para Ordenar Por** Selecione um campo da lista. A Ordenação de Destaque 
  deve ser usada apenas quando a Opção de Filtragem para Artigos em Destaque estiver configurada como *Somente*.
- **Direção da Ordenação** Selecione a direção da ordenação dos artigos.

### Aba Opções de Agrupamento

![opções de agrupamento de categoria de artigos](../../../ptbr/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Agrupamento de Artigos** Selecione um método de agrupamento de artigos da lista.
- **Direção do Agrupamento** Selecione a direção da ordenação.
- **Formato de Exibição de Mês e Ano** Insira um formato de data válido.

### Aba Opções de Exibição

![opções de exibição de categoria de artigos](../../../ptbr/images/modules-site/modules-articles-category-display-options-tab.png)

- **Títulos Vinculados** Mostrar os títulos como links para os artigos.
- **Data** Mostrar ou ocultar a data do artigo.
- **Campo de Data** Selecione o campo de data a ser exibido.
- **Formato da Data** Insira um formato de data válido.
- **Categoria** Mostrar ou ocultar o nome da categoria do artigo.
- **Visualizações** Mostrar ou ocultar o número de visualizações do artigo.
- **Autor** Mostrar ou ocultar o nome do autor ou alias do autor.
- **Texto de Introdução** Mostrar ou ocultar o texto de introdução do artigo.
- **Limite do Texto de Introdução** O número máximo de caracteres a serem exibidos.
- **Mostrar "Leia Mais"** Mostrar ou ocultar o link *Leia mais...* se o texto principal do artigo foi fornecido.
- **Mostrar Título com Leia Mais** Mostrar ou ocultar o título do artigo no 
  link *Leia Mais...*.
- **Limite do Leia Mais** Limitar o número de caracteres do título do artigo a ser exibido no 
  link *Leia Mais...*.

*Traduzido por openai.com*

