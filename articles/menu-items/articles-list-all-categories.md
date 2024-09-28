<!-- Filename: Help4.x:Menu_Item:_List_All_Categories  / Display title: Listar Todas as Categorias -->

## Descrição

O tipo de item de menu *Listar Todas as Categorias em uma Árvore de Categorias de Artigos* é usado para mostrar Categorias em uma lista hierárquica. Dependendo das opções selecionadas para este layout, você pode clicar no Título de uma categoria para mostrar os artigos naquela categoria.

### Elementos Comuns

Alguns aspectos desta página são cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba Categoria](jdocmanual?article=help/menu-items-common/menu-item-category).
* [A Aba Layout de Blog](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [A Aba Layouts de Lista](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [A Aba Opções](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [A Aba Integração](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba Exibição da Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba de Atribuição de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Selecione **Menus → \[nome do menu\]** no menu do Administrador.

Para adicionar um Item de Menu:

1.  Selecione o botão **Novo** na Barra de Ferramentas.
2.  Selecione o botão **Selecionar** no Tipo de Item de Menu.
3.  Selecione o item **Artigos**.
4.  Selecione o item **Listar Todas as Categorias em uma Árvore de Categoria de Artigos**.

Para editar um Item de Menu:

- selecione um **Título** da lista.

## Captura de Tela

![Item de Menu Lista de Artigos Todas as Categorias guia de detalhes](../../../ptbr/images/menu-items/articles-list-all-categories-details-tab.png)

## Campos do Formulário

- **Título** O título que será exibido para este item de menu.
- **Alias** O nome interno do item de menu. Normalmente, você pode deixar
  este campo em branco e o Joomla preencherá com um valor padrão, que é o título em letras minúsculas e com hífens em vez de espaços.

### Aba Detalhes

#### Painel Esquerdo

- **Tipo de Item de Menu** O Tipo de Item de Menu selecionado quando este item de menu
  foi criado. Este pode ser um dos tipos de itens de menu principais ou um tipo
  de item de menu fornecido por uma extensão instalada.
- **Selecionar a Categoria de Nível Superior**
  - *Raiz* Incluir todas as categorias de artigos.
  - Caso contrário, selecione a categoria de nível superior desejada. Todas as
    categorias filhas da categoria selecionada aparecerão no item de menu.
- **Link** O link gerado pelo sistema para este item de menu. Este campo
  não pode ser alterado e serve apenas para informação.
- **Janela de Destino** Selecione na lista suspensa.
- **Estilo do Template** Selecione na lista suspensa.

#### Painel Direito

- **Menu** Mostra em que menu o link aparecerá.

### Aba Categorias

![Menu Item Articles List All Categories categories tab](../../../ptbr/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Descrição da Categoria de Nível Superior** Mostrar a descrição da
  categoria de nível superior.
- **Descrição Alternativa** Insira uma descrição para substituir a
  descrição da categoria para o item de menu.
- **Níveis de Subcategorias** Controla quantos níveis de subcategorias
  mostrar.
- **Categorias Vazias** Mostrar categorias que não contêm artigos ou
  subcategorias.
- **Descrições de Subcategorias** Mostrar a descrição das
  subcategorias.
- **\# Artigos na Categoria** Mostrar uma contagem do número total de
  artigos em cada categoria.

### Aba Layout de Blog

As opções de Layout de Blog controlam a aparência da navegação na categoria, caso
resulte em um layout de blog.

O formulário de layout de blog possui um layout diferente do dos Elementos Comuns
acima, mas os campos são similares.

### Aba Compartilhado

As Opções Compartilhadas se aplicam para Opções Compartilhadas em Lista, Blog e Em Destaque,
a menos que sejam alteradas pelas configurações do menu.

![Menu Item Articles List All Categories categories tab](../../../ptbr/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Paginação** A paginação fornece links de página na parte inferior da
  página que permitem ao usuário navegar para páginas adicionais. Estes
  são necessários se os Artigos não couberem em uma única página.
  - *Esconder* Links de paginação não mostrados. *Nota* Os usuários não poderão
    navegar para páginas adicionais.
  - *Mostrar* Links de paginação mostrados, se necessário.
  - *Automático* Links de paginação mostrados, se necessário.
- **Resumo da Paginação** Mostrar o número da página atual e o total de páginas
  (por exemplo, *Página 1 de 2*) na parte inferior de cada página.

## Dicas

- As categorias podem ser *aninhadas* em níveis, semelhantes a pastas em um disco
  rígido. Em teoria, não há um limite absoluto para o número de níveis
  que você pode ter. No entanto, como questão prática, é recomendado manter
  os níveis ao mínimo. O layout Mostrar Todas as Categorias pode não funcionar
  corretamente se o número de níveis exibidos for maior que 5.
- Se você configurar os títulos das categorias como linkáveis, o usuário pode explorar
  a categoria. Quando eles fizerem isso, eles normalmente verão um item de menu
  de Lista de Categoria ou de Blog de Categoria, dependendo da opção selecionada.
  Se houver um item de menu preexistente para essa categoria (por exemplo, um item
  de menu Blog de Categoria), então esse item de menu será exibido na exploração
  e as opções definidas para esse item de menu controlarão a exibição da página.
  Caso contrário, as opções definidas para o item de menu Mostrar Todas as Categorias
  atual controlarão a exibição da página.
- Você pode configurar a opção de explorar para uma lista ou blog em 2 lugares.
  - Em *Artigos: Opções* você pode definir o valor padrão para todas as categorias.
  - Em *Categoria: Editar* você pode definir um valor para uma categoria específica. 
    Se isso for definido, ele substituirá o valor padrão.
- Para personalizar um *Formato de Data* você pode usar `D M Y` para dia mês ano ou `d-m-y`
  para uma versão curta, por exemplo, 17-08-05. Se deixado em branco, a tradução da chave
  DATE_FORMAT_LC1 será usada do seu arquivo de idioma.

*Traduzido por openai.com*

