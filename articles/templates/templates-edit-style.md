<!-- Filename: Help4.x:Templates:_Edit_Style  / Display title: Templates: Editar Estilo -->

## Descrição

A página *Modelos: Editar Estilo* é usada para editar estilos de modelos. Quando um modelo é instalado pela primeira vez, um estilo padrão é criado para ele. O estilo padrão do modelo terá o mesmo nome que o modelo com um sufixo *- Padrão*. Para fazer uma variação diferente do estilo padrão do modelo, marque a caixa de seleção do estilo padrão e pressione o ícone *Duplicar* na barra de ferramentas. Em seguida, edite o duplicado.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como Acessar

- Selecione **Sistema → Painel de Modelos → Estilos de Modelos de Site**
  no menu do Administrador. Ou...
- Selecione **Sistema → Painel de Modelos → Estilos de Modelos do Administrador**
  no menu do Administrador. Então...
  - Selecione o nome do Estilo do Modelo para editar na coluna Estilo.


## Captura de Tela

![modelos cassiopeia editar guia do editor de estilo](../../../ptbr/images/templates/templates-site-edit-style-details-tab.png)

## Campos de Formulário

- **Nome do Estilo** O nome do estilo. Este é o nome que será exibido na coluna Estilo da tela *Template: Estilos*.

### Aba Detalhes

- **Informação** O nome do template, indicador de Site ou Administrador e uma breve descrição.

### Aba Avançada

![templates cassiopeia editar estilo aba avançada](../../../ptbr/images/templates/templates-site-edit-style-advanced-tab.png)

Esta seção pode não estar presente para todos os estilos. Se um template do qual um estilo deriva tiver opções configuráveis, elas estarão presentes aqui. São estas opções configuráveis adicionais que permitem ter múltiplos estilos diferentes de templates com variações dessas opções. As opções disponíveis vão variar com base nas opções que o desenvolvedor do template disponibilizou.

### Configurações de Cor do Atum

O template padrão do Administrador permite que você experimente variações de cores. Salve e veja!

### Configurações de Imagem do Atum

Você pode selecionar uma imagem para substituir o **Logo de Login** no formulário de login do Administrador, e o **Logo da Marca** na barra de título do Administrador em modo expandido e em modo compacto. Os padrões são os logos da Marca Joomla. Na Barra de Título, a palavra Joomla! está presente na versão **Marca Grande** e omitida na versão **Marca Pequena**. Selecione **Alternar Menu** para ver a mudança.

Se você fornecer sua própria Marca Pequena, também precisará fornecer uma substituição de estilo de largura. Para isso, crie um arquivo user.css na raiz do template e insira o seguinte, mas substitua 3rem por uma largura adequada para sua imagem:

       .header .logo.small {
           width: 3rem;
       }

### Aba de Atribuição de Menu

![templates cassiopeia editar estilo aba de atribuição de menu](../../../ptbr/images/templates/templates-site-edit-style-menu-assignment-tab.png)

Esta seção contém todos os itens de menu configurados no seu site Joomla! Para aplicar o estilo atual à página web correspondente de um item de menu, marque a caixa ao lado do item de menu. Você pode pressionar o botão *Alternar Seleção* para inverter as seleções de itens de menu.

**Nota** Se uma caixa de seleção estiver esmaecida e não puder ser marcada, pode ser porque o item de menu está em uso por outro usuário. Você pode verificar se este é o caso indo à tela do gerenciador de menus para o menu em questão. Se houver um símbolo de cadeado ao lado do item de menu, ele está atualmente em uso por outro usuário.

*Traduzido por openai.com*

