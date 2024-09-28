<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container  / Display title: Item do Menu: Contêiner do Menu de Componentes -->

## Descrição

O Contêiner do Menu de Componentes é usado para mostrar um contêiner de componentes na interface do Administrador. Um caso de uso pode ser o seguinte:

Suponha que você só deseja mostrar links para um subconjunto dos Componentes do seu site para certos usuários. Super Usuários verão links para tudo, é claro. Você pode fazer isso da seguinte forma:

- Crie um novo Grupo de Usuários chamado, por exemplo, Filial, com Público como pai.
- Defina as Permissões Globais para este grupo para Permitir Login de Administrador.
- Crie um novo menu chamado, por exemplo, Menu da Filial sem predefinições importadas.
- Crie um Módulo vinculado chamado, por exemplo, Menu da Filial com menu para mostrar como Menu da Filial. Defina Verificar Menu como Não e Acesso como Público.
- Crie um item de menu de Contêiner de Menu de Componentes para o Menu da Filial chamado, por exemplo, Componentes da Filial.
  - Oculte quaisquer componentes que você não deseja que os usuários da Filial vejam.
  - Mostre aqueles aos quais eles devem ter acesso.
- Defina as Permissões dos Componentes para o Grupo da Filial como permitido para todos, exceto Configurar ACL e Configurar Opções.

Para um Super Usuário, o menu do Administrador terá uma duplicação óbvia de links. No entanto, um usuário da Filial verá apenas o menu de Componentes da Filial e o Painel Inicial. Você também precisará ajustar as permissões de Acesso dos módulos de Ícone Rápido lá! E você realmente precisa criar um módulo de Painel para quaisquer componentes que os usuários da Filial tenham acesso.

Para usuários que precisam acessar Artigos, você pode adicionar mais itens de menu ao Menu da Filial. Dessa forma, você pode criar um menu totalmente personalizado para os usuários da Filial.

### Elementos Comuns

Alguns aspectos desta página são cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).

## Como Acessar

Para criar um novo Item de Menu de Contêiner de Componente:

- Crie um novo Menu em **Menus → Gerenciar** no menu do Administrador.
  - Selecione **Administrador** no seletor suspenso *Site/Administrador*.
  - Selecione o botão **Novo** na Barra de Ferramentas. Preencha o formulário:
    - **Título** Menu da Filial
    - **Nome Único** menu_filial
    - **Descrição** Menu personalizado para a Filial.
    - **Importar Predefinição** Nenhum
    - **Salvar**
    - **Permissões** Selecione o grupo *Filial* e defina tudo como *Permitir*.
    - **Salvar & Fechar**
    - Selecione o botão **Criar um Módulo** e preencha o formulário de diálogo:
    - **Título** Componentes da Filial
    - **Verificar Menu** Não (caso contrário, haverá uma mensagem convidando você a 
      *ativar o modo de recuperação do menu*.)
    - **Acesso** Especial
    - **Posição** Menu
- Selecione **Menus → [nome do menu]** no menu do Administrador.
- Selecione o botão **Novo** na Barra de Ferramentas para criar um novo item de menu.
- Selecione o botão **Selecionar** do Tipo de Item de Menu.
- Selecione o link **Listar Contêiner de Componente** em **Links do Sistema** na
  janela modal do Tipo de Item de Menu.

Para editar um Item de Menu de Contêiner de Componente existente, selecione seu Título na
lista de Itens de Menu.

## Captura de Tela

![Componentes do Item de Menu Container do Menu](../../../ptbr/images/menu-items/administrator-components-menu-container.png)

## Campos de Formulário

- **Nome** O nome do item do menu, por exemplo, *Menu de Filiais*. Ele aparecerá na parte inferior do menu Administrador.
- **Alias** O nome interno do item. Normalmente, você pode deixar isso em branco e o Joomla preencherá um valor padrão com o Título em letras minúsculas e com traços em vez de espaços.

### Aba Detalhes

#### Painel Esquerdo

- **Tipo de Item do Menu** Neste caso, *Container de Menu de Componentes*.
- **Mostrar ou Ocultar Itens do Menu** Lista de itens do menu com botões para definir o status de visibilidade. Se um item pai estiver definido como *Ocultar*, todos os itens filhos também serão ocultos, mesmo se estiverem definidos para *Mostrar*.

#### Painel Direito

- **Menu** Mostra em qual menu o link aparecerá.
- **Pai** O item (categoria, item do menu, e assim por diante) que é o pai do item que está sendo editado.
- **Ordenação** Indica a ordem deste Item do Menu no Menu. A ordem padrão é adicionar o Item do Menu ao final do Menu. Este Item do Menu será movido para a posição de ordem logo após o Item do Menu selecionado na lista suspensa. Note que a Ordem dos Itens do Menu também pode ser alterada no Gerenciador de Itens do Menu.
- **Status** O status de publicação do item.
- **Nota** Isso é normalmente para uso do administrador do site (por exemplo, para documentar informações sobre este item) e não aparece no Frontend do site.

## Dicas

- O item **Componentes da Filial** aparece na parte inferior do menu do Administrador. O acesso ao menu principal do Administrador e a esta seção pode ser customizado para o grupo da Filial.

*Traduzido por openai.com*

