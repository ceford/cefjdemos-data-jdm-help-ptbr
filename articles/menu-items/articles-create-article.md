<!-- Filename: Help4.x:Menu_Item:_Create_Article  / Display title: Criar Artigo -->

## Descrição

O item de menu *Criar Artigo* permite que os usuários submetam um artigo via a interface do site. Normalmente, isso está disponível apenas para usuários que fizeram login no Frontend do site. Os usuários devem ter permissão para criar artigos.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba do Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba de Exibição da Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba de Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba de Atribuição de Módulos](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Selecione **Menus → \[nome do menu\]** no menu do Administrador.

Para adicionar um Item de Menu:

1.  Selecione o botão **Novo** na Barra de Ferramentas.
2.  Selecione o botão **Selecionar** no campo *Tipo de Item de Menu*.
3.  Selecione o item **Artigos** no diálogo pop-up.
4.  Selecione o item **Criar Artigo**.

Para editar um Item de Menu:

- Selecione um **Título** na lista

## Captura de Tela

![Item do Menu Artigos Criar Aba de Detalhes do Artigo](../../../ptbr/images/menu-items/articles-create-article-details-tab.png)

Sure, here's the translation to Portuguese (Brazil):

## Campos do Formulário

- **Título** O título que será exibido para este item de menu.
- **Alias** O nome interno do item de menu. Normalmente, você pode deixar
  este campo em branco e o Joomla preencherá com um valor padrão usando o Título em letras minúsculas
  e com traços em vez de espaços.

### Detalhes

#### Painel Esquerdo

- **Tipo de Item de Menu** O tipo de item de menu selecionado quando este item de menu
  foi criado. Este pode ser um dos tipos de item de menu padrão ou um tipo de item de menu
  fornecido por uma extensão instalada.
- **Link** O link gerado pelo sistema para este item de menu. Este campo
  não pode ser alterado e é somente para informação.
- **Janela de Destino** Selecione na lista suspensa.
- **Estilo do Template** Selecione na lista suspensa.

#### Painel Direito

- **Menu** Exibe em qual menu o link aparecerá.

### Opções

![Aba de detalhes de Criar Artigo de Itens de Menu](../../../ptbr/images/menu-items/articles-create-article-options-tab.png)

- **Categoria Específica**
  - *Sim* Os artigos serão atribuídos à categoria especificada. O usuário
    não poderá selecionar uma categoria.
  - *Não* O usuário poderá selecionar a categoria na caixa de seleção. Somente
    categorias para as quais o usuário tem permissão de *Criar* serão exibidas.
- **Redirecionamento de Submissão/Cancelar** Selecione a página para a qual o usuário será
  redirecionado após a submissão bem-sucedida do artigo.
- **Redirecionamento Personalizado ao Cancelar**
  - *Sim* Configure uma página para redirecionar quando o usuário cancelar a submissão do artigo.
  - *Não* Quando o usuário cancelar a submissão do artigo, ele será redirecionado para
    a página de *Redirecionamento de Submissão/Cancelar*.

## Captura de Tela do Frontend de Exemplo

Esta captura de tela mostra o Template Frontend padrão do Joomla, **Cassiopeia**, com todas
as opções de Edição de Layout configuradas para 'Esconder'.

[articles-create-article-frontend.png](../../../en/images/menu-items/articles-create-article-frontend.png)

## Dicas

Um usuário não autorizado normalmente receberá um erro ao selecionar um item de menu *Criar Artigo*. Por essa razão, é prática comum definir um Nível de Acesso de visualização para o item de menu que só pode ser visto por usuários autorizados a adicionar artigos.

*Traduzido por openai.com*

