<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper  / Display title: Envoltório de Iframe -->

## Descrição

O tipo de item de menu *Iframe Wrapper* é usado para criar uma página com conteúdo embutido usando um IFrame com controle do tamanho, largura e altura do iframe.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba Exibição da Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba Atribuição de Módulos](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Para criar um novo Item de Menu IFrame Wrapper:

- Selecione **Menus → \[nome do menu\]** no menu do Administrador
  (por exemplo, **Menus → Menu Principal**). Então...
  - Selecione o botão **Novo** na Barra de Ferramentas. Então...
  - Selecione o botão Selecionar Tipo de Item de Menu.
  - No diálogo modal, selecione o item Usuários para abrir uma lista e depois
    selecione o item de menu **IFrame Wrapper**.

Para editar um item de menu *IFrame Wrapper* existente:

- Selecione seu Título na lista *Menu: Itens*.

## Captura de Tela

![Aba de detalhes do wrapper iframe](../../../ptbr/images/menu-items/wrapper-iframe-wrapper-details-tab.png)

## Campos do Formulário

### Aba de Parâmetros da Barra de Rolagem

![Aba de parâmetros da barra de rolagem do wrapper do Iframe](../../../ptbr/images/menu-items/wrapper-scroll-bar-parameters-tab.png)

- **Largura** Largura da Janela do IFrame. Insira um número de pixels ou uma
  porcentagem. Por exemplo, *550* significa 550 pixels; *75%* significa 75% da
  largura do contêiner `<main>`. Um número absoluto de pixels pode ser maior que
  o contêiner e causar problemas de layout. Em caso de dúvida, tente 100%.
- **Altura** Altura da Janela do IFrame. Insira um número de pixels. Por exemplo,
  *550* significa 550 pixels.

### Aba Avançada

![Aba avançada do wrapper do Iframe](../../../ptbr/images/menu-items/wrapper-advanced-tab.png)

- **Altura automática** Define automaticamente a altura para a altura da página externa.
  *Nota* - isso só funcionará se a página externa estiver no **mesmo
  domínio**. Por exemplo, `http://www.example.com`, o HTML externo deve
  estar na estrutura de arquivos raiz do `example.com`. Subdomínios não irão
  funcionar, pois um subdomínio é considerado um domínio separado.
- **Adição automática** Prefixa automaticamente o endereço da web com http://. Essa
  funcionalidade irá automaticamente detectar e não prefixar uma URL com http:// ou
  https:// já utilizada na URL.
- **Carregamento Preguiçoso** ...

*Traduzido por openai.com*

