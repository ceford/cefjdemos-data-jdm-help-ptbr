<!-- Filename: Help4.x:Edit_Permissions  / Display title: Editar Permissões -->

## Propósito

Muitas extensões possuem telas de edição com uma aba de Permissões que é usada para alterar
as permissões atribuídas aos Grupos de Usuários. O número de Grupos de Usuários pode variar
pois grupos personalizados podem ser adicionados para fins especiais. O
número de Ações que podem ser alteradas também varia conforme a extensão. Este artigo
é uma breve descrição das telas de permissões para esses fins
especiais.

Imagine que existe um usuário que cuida de Mídia (imagens e arquivos) mas
não possui outras responsabilidades. Um grupo chamado Oddjob foi
criado e atribuído ao nível de acesso Especial. Um usuário também chamado Oddjob foi
criado e atribuído ao grupo Oddjob.

Para mais informações detalhadas sobre Grupos de Usuários, Níveis de Acesso e Permissões
há um tutorial separado sobre [Controle de Acesso](jdocmanual?article=user/users/access-control).

## Permissões de Configuração Global

Neste exemplo, usuários do grupo Oddjob receberam permissão Global para acessar a interface do Administrador, mas nada além disso.

![Captura de Tela das Permissões](../../../ptbr/images/common-elements/global-configuration-permissions-tab.png)

## Permissões de Configuração de Componentes

Para acessar um componente específico, as permissões devem ser configuradas nas opções do componente. Neste exemplo, as opções do componente Mídia.

![Captura de Tela da Mídia](../../../ptbr/images/common-elements/media-options-permissions-tab.png)

Você vai perceber que este componente possui menos Ações disponíveis e o grupo "Oddjob" tem permissões apenas suficientes para realizar o trabalho.

Para alterar as permissões deste componente:

* Selecione o Grupo clicando em seu título localizado à esquerda.<br>
    Encontre a Ação desejada.
    * Apagar. Usuários podem apagar este artigo.
    * Editar. Usuários podem editar este artigo.
    * Editar Estado. O usuário pode alterar o estado de publicação e as informações relacionadas a este artigo.
* Selecione a permissão desejada para a ação que você deseja alterar.
    * Herdado. Herdado para usuários deste Grupo a partir da Configuração Global, Opções de Artigos, ou Categoria de Artigos.
    * Permitido. Permitido para usuários deste Grupo. Nota: Se esta ação for Negada em um dos níveis superiores, a permissão Permitida aqui não terá efeito. Uma configuração Negada não pode ser sobreposta.
    * Negado. Negado para usuários deste Grupo.
* Clique em Salvar na Barra de Ferramentas no topo. Quando a tela for atualizada, a coluna "Configuração Calculada" mostrará a permissão efetiva para este Grupo e Ação.

## A Experiência do Usuário

Após o login, um usuário no grupo Oddjob verá os módulos do Painel Inicial que têm o acesso **Especial** configurado e um link no Menu para o componente de Mídia.

![Painel Inicial para Oddjob](../../../ptbr/images/common-elements/home-dashboard-for-oddjob.png)

E a tela de Mídia para o usuário Oddjob é como esperado:

![Tela de Mídia para Oddjob](../../../ptbr/images/common-elements/media-screen-for-oddjob.png)

*Traduzido por openai.com*

