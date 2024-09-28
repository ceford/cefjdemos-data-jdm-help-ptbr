<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_User_Group  / Display title: Grupo de Usuários -->

## Descrição do Grupo

### Usuário - Criador de Contato

![Formulário de criador de contato do usuário](../../../en/images/plugins/plugin-group-user-contact-creator.png)

- **Página da Web Automática** Uma string formatada para gerar automaticamente uma página da web de contato. [name] é substituído pelo nome, [username] é substituído pelo nome de usuário, [userid] é substituído pelo ID do usuário e [email] é substituído pelo email.
- **Categoria** Categoria para atribuir contatos por padrão.
- **Publicar Automaticamente o Contato** Opcionalmente, defina o contato criado automaticamente para o estado publicado e visível para os visitantes do site.

### Usuário - Token da API do Joomla

Permite o gerenciamento de tokens de segurança usados para autenticação na aplicação da API do Joomla (acesso remoto ao site). Esses tokens são estritamente pessoais. Você pode visualizar seu próprio token, mas só pode desativar ou redefinir os tokens de outros usuários.

![Formulário de token da api do usuário joomla](../../../en/images/plugins/plugin-group-user-joomla-api-token.png)

- **Grupos de Usuários Permitidos** Selecione um ou mais para permitir que um grupo use Tokens do Joomla para autenticação na aplicação da API do Joomla.

### Usuário - Joomla!

![Formulário do usuário joomla](../../../en/images/plugins/plugin-group-user-joomla.png)

- **Criar Usuários Automaticamente** Determina se os usuários registrados no Joomla! serão criados automaticamente quando possível. O padrão é *Sim*.
- **Notificação por Email para o Usuário** Quando um administrador cria uma conta de usuário, isto determina se um email com o nome de usuário e senha será enviado para o usuário.
- **Forçar Logout para todas as Sessões?** Defina como Não para desativar isso.

### Usuário - Perfil

Este plugin adiciona capacidade de perfil de usuário a um website. Os usuários do site poderão preencher os campos de perfil habilitados na seção de opções deste plugin. Permite controlar quais campos de perfil são exibidos no formulário de registro de novo usuário e/ou na tela de perfil editável de cada usuário. Para controlar quais campos são exibidos no formulário de registro de novo usuário, defina as opções de campo na seção intitulada Informações de perfil do usuário requeridas no registro. Para os campos de perfil exibidos na tela de perfil do usuário, editável após o login, defina a opção de campo na seção de opções intitulada Informações de perfil do usuário requeridas. Cada campo tem as seguintes opções:

- **Obrigatório** O campo é visível nos perfis dos usuários e os usuários são obrigados a preenchê-lo.
- **Opcional** O campo é visível nos perfis dos usuários, mas é opcional e os usuários não precisam preenchê-lo.
- **Desativado** O campo está desativado e não é visível nos perfis dos usuários.

![Formulário de perfil do usuário](../../../en/images/plugins/plugin-group-user-profile.png)

- **Todos os campos** As três opções estão disponíveis, exceto para o campo Termos de Serviço, que oferece uma escolha entre *Obrigatório* e *Desativado*.

### Usuário - Termos e Condições

Este plugin permite a coleta do consentimento do usuário aos termos e condições do site.

![Formulário de termos e condições do usuário](../../../en/images/plugins/plugin-group-user-terms-and-conditions.png)

- **Termos e Condições Resumidos** Permite a entrada de um resumo dos Termos e Condições ou o uso do padrão de idioma.
- **Artigo de Termos e Condições** Selecione ou crie um artigo para os Termos e Condições para vincular ao formulário do usuário.

