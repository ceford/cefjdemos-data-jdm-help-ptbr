<!-- Filename: Help4.x:Menu_Item:_Login_Form  / Display title: Formulário de Login -->

## Descrição

O tipo de item de menu **Formulário de Login** é usado para criar uma página contendo um formulário de login.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba Exibição da Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba Atribuição de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Para criar um novo item de menu de **Formulário de Login**:

- Selecione **Menus → \[nome do menu\]** no menu do Administrador
  (por exemplo, **Menus → Menu Principal**). Então...
  - Selecione o botão Novo na Barra de Ferramentas. Então...
  - Selecione o botão Selecionar Tipo de Item de Menu.
  - No diálogo modal, selecione o item Usuários para abrir uma lista e, em seguida,
    selecione o item **Formulário de Login**.

Para editar um item de menu de Formulário de Login existente:

- Selecione seu Título na lista *Menus: Itens*.

## Captura de Tela

![Detalhes da aba do formulário de login](../../../ptbr/images/menu-items/users-login-form-details-tab.png)

## Campos do Formulário

### Aba de Opções

![Detalhes da aba do formulário de login](../../../ptbr/images/menu-items/users-login-form-options-tab.png)

#### Painel de Login

- **Escolher Tipo de Redirecionamento de Login** Isso pode ser um *Item de Menu* ou uma *URL Interna*.
  Os seguintes campos mudam dependendo da configuração deste parâmetro. Para 
  um site multilíngue, recomenda-se *Item de Menu*.
  - **Item de Menu de Redirecionamento de Login** Selecione ou crie um item de menu para a página
    para redirecionar após um login bem-sucedido. Se nenhum item de menu for selecionado, 
    os usuários serão redirecionados para seu perfil após o login.
  - **Redirecionamento de Login** Selecione uma URL interna para redirecionar após o login.
- **Descrição do Login** Mostrar ou ocultar a descrição do login.
- **Texto da Descrição do Login** Insira o texto a ser exibido na página de Login.
- **Imagem do Login** Selecione ou faça o upload de uma imagem para exibir na página de Login.
- **Descrição da Imagem (Texto Alternativo)** Necessário para leitores de tela para fins de acessibilidade.
- **Sem Descrição** Uma caixa de seleção para selecionar se a imagem é puramente decorativa e 
  não requer explicação.

#### Painel de Logout

Este painel utiliza os mesmos títulos de campo para controlar o processo de logout.

## Dicas

- A **URL de Login e Logout** pode ser usada para enviar um usuário para uma página específica criada para fornecer algum feedback. Por exemplo, uma página intitulada *Você está agora logado* com algumas informações gerais. O uso de um Módulo de Usuário para mostrar links para Atualizar Perfil do Usuário, Visualizar Perfil do Usuário e outras funções de Usuário podem ser exibidos nesta página, melhorando a experiência do usuário no site.

*Traduzido por openai.com*

