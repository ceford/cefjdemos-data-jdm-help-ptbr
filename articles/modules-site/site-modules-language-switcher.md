<!-- Filename: Help4.x:Site_Modules:_Language_Switcher  / Display title: Módulos: Seletor de Idioma -->

## Descrição

O tipo de módulo *Switcher de Idiomas* permite que você troque entre os
idiomas de Conteúdo disponíveis. Selecionar um idioma levará você para a
página correspondente a esse idioma.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Os Módulos: Aba de Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [Os Módulos: Aba de Atribuição de Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Os Módulos: Aba Avançada](jdocmanual?article=help/modules/modules-advanced-tab).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

- Selecione **Sistema → Gerenciar Painel → Módulos do Site** no menu do
  Administrador. Em seguida...
  - Para criar um novo módulo: selecione o botão **Novo** na Barra de Ferramentas. Então...
    - Selecione o tipo de módulo necessário.
  - Para editar um módulo existente:
    - Encontre o módulo na lista de módulos instalados e selecione o
      link do título na coluna **Título**.

## Captura de Tela

![aba do módulo de troca de idioma](../../../ptbr/images/modules-site/modules-language-switcher-module-tab.png)

## Campos do Formulário

- **Título** O título do módulo. Este também é o título exibido
  para o módulo, dependendo do campo de formulário *Mostrar Título*

### Aba do Módulo

#### Painel Esquerdo

- **Pré-texto** Este é o texto ou HTML que é exibido acima do
  seletor de idioma.
- **Pós-texto** Este é o texto ou HTML que é exibido abaixo do
  seletor de idioma.
- **Usar Menu Suspenso** Os três itens a seguir mudam para *Sim* e *Não*
  - **Não**
    - **Usar Bandeiras de Imagem** Se configurado para *Sim*, exibe a escolha do idioma como 
    bandeiras de imagem. Caso contrário, usa os nomes nativos de idiomas do conteúdo. Se configurado para
    *Não* aparece um campo extra: **Nomes Completos dos Idiomas**, que exibe
    um código de idioma de duas letras em maiúsculas para cada idioma.
    - **Idioma Ativo** Exibir ou não o idioma ativo.
    Se exibido, a classe `lang-active` será adicionada ao elemento.
    - **Exibição Horizontal** O padrão é configurado para *Sim*, ou seja, para criar uma
    exibição em lista horizontal. Configurado para *Não* para uma lista vertical.
  - **Sim** O item *Idioma Ativo* é exibido selecionado.
    - **Usar Bandeiras no Menu Suspenso** Se configurado para *Sim* a bandeira do idioma é colocada
      antes do nome do idioma na lista suspensa. 
    - **Nomes Completos dos Idiomas** Se configurado para *Não*, exibe um código de idioma de duas letras em maiúsculas para cada idioma.
    - **Idioma Ativo** Sem efeito na lista suspensa.

*Traduzido por openai.com*

