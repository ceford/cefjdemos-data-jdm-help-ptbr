<!-- Filename: Help4.x:Users:_Options / Display title: Usuários: Opções -->

## Descrição

As opções de usuário definidas globalmente para todos os usuários
incluem

- captcha,
- permissão e tipo de registro,
- grupo de usuários padrão para novos usuários,
- contador de redefinição de senha ou de nome de usuário,
- aviso de registro de novo usuário à administração através de e-mail e
  muito mais.

## Como acessar
Selecione **Usuários → Gerenciar**

- Selecione o botão **Opções** na barra de ferramentas.

## Captura de tela

<img
src="https://docs.joomla.org/images/thumb/6/6c/Help-4x-Users-Options-screen-pt-br.png/800px-Help-4x-Users-Options-screen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6c/Help-4x-Users-Options-screen-pt-br.png/1200px-Help-4x-Users-Options-screen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/6/6c/Help-4x-Users-Options-screen-pt-br.png/1600px-Help-4x-Users-Options-screen-pt-br.png 2x"
data-file-width="2400" data-file-height="1500" width="800" height="500"
alt="Users Options screen pt" />

## Campos do formulário

### Opções de usuário

- **Permitir registro de usuários**.
  - Sim: Se definido como "Sim", os usuários podem se registrar no
    Frontend do site usando o link "Criar uma conta" fornecido no módulo
    de início de sessão.
  - Não: Se definido como "Não", o link 'Criar uma conta' não será
    exibido.
- **Grupo de Cadastro de Novo Usuário**. O
  grupo
  ao qual os usuários são atribuídos por padrão quando se registram no
  site. O padrão é 'Registrados'.
- **Comentários do Grupo de Usuários**. O grupo ao qual os convidados
  são atribuídos (Convidados são visitantes do site que não iniciam uma
  sessão). Se você alterar isso para um grupo diferente, é possível
  criar conteúdo no site que seja visível para os convidados, mas não
  visível para usuários conectados. \[<a
  href="https://magazine.joomla.org/all-issues/june-2021/explore-the-core-controlling-user-access?%7CSaiba"
  class="external text" target="_blank"
  rel="noreferrer noopener">mais.</a>\]
- **Enviar Senha**. Se definido como 'Sim', a primeira senha do usuário
  será enviada ao usuário como parte do e-mail de registro.
- **Ativação de Cadastro de Novo Usuário**.
  - Nenhum: A conta de usuário será ativada imediatamente, sem a
    necessidade de ação.
  - Usuário: O usuário receberá um e-mail com um link de ativação. A
    conta será ativada quando o usuário clicar no link de ativação.
  - Administrador: O usuário receberá um e-mail com um link de ativação.
    Quando o usuário clicar neste link, a administração do site será
    notificado através de e-mail e a ativação da conta de usuário
    precisa ser autorizada pela administração do site.
- **Notificar Administradores**. Envia notificações por e-mail, para a
  administração, quando a 'Ativação de conta de usuário' está definida
  como 'Nenhum' ou 'Usuário'.
- **Captcha**. Usa
  Captcha
  para os registros de contas de usuários e lembretes de nomes de
  usuários ou senhas de usuários.
- **Parâmetros do Usuário**.
  - Exibir: Se definido como 'Exibir', os usuários poderão modificar, no
    Frontend do site, suas próprias configurações de linguagens,
    editores e as preferências do site de ajuda.
  - Ocultar: Se definido como 'Ocultar', os usuários não poderão alterar
    essas configurações.
  - Idioma do site. Linguagem padrão do site.
- **Alterar Nome de Usuário**. Permitir que os usuários alterem o
  próprio nome de usuário.

### Opções de domínio de e-mail

<img
src="https://docs.joomla.org/images/thumb/b/bb/Help-4x-Users-Options-email-domain-subscreen-pt-br.png/600px-Help-4x-Users-Options-email-domain-subscreen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/bb/Help-4x-Users-Options-email-domain-subscreen-pt-br.png/900px-Help-4x-Users-Options-email-domain-subscreen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/b/bb/Help-4x-Users-Options-email-domain-subscreen-pt-br.png/1200px-Help-4x-Users-Options-email-domain-subscreen-pt-br.png 2x"
data-file-width="2002" data-file-height="1073" width="600" height="322"
alt="Users Options email domain subscreen pt" />

- **Nome do Domínio**. Insira uma lista de domínios de e-mail permitidos
  e não permitidos. Por padrão, todos os domínios são
  permitidos.Curingas (\*) são aceitos. Por exemplo:
  - \* (Asterisk): Permite ou bloqueia todos os domínios,
  - \*.com: Permite ou bloqueia todos os domínios '.com',
  - \*.joomla.org: Permite ou bloqueia todos os subdomínios pertencentes
    a 'joomla.org'.
- **Regra** Selecione se deve permitir ou não permitir o domínio.

### Opções de senha

<img
src="https://docs.joomla.org/images/thumb/5/5b/Help-4x-Users-Options-password-subscreen-pt-br.png/600px-Help-4x-Users-Options-password-subscreen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/5b/Help-4x-Users-Options-password-subscreen-pt-br.png/900px-Help-4x-Users-Options-password-subscreen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/5/5b/Help-4x-Users-Options-password-subscreen-pt-br.png/1200px-Help-4x-Users-Options-password-subscreen-pt-br.png 2x"
data-file-width="2002" data-file-height="1230" width="600" height="369"
alt="Users Options password subscreen pt" />

- **Redefinir Contagem Máxima**. O número máximo de redefinições de
  senha permitidas em um determinado período de tempo. Zero indica que
  não há limite.
- **Redefinir Tempo (horas)**. O período de tempo para o contador de
  redefinições.
- **Mínimo de caracteres**. Define o comprimento mínimo para uma senha.
- **Mínimo de números**. Define o número mínimo de números inteiros que
  devem ser incluídos em uma senha.
- **Mínimo de Símbolos**. Define o número mínimo de símbolos
  (como !@#\$) necessários em uma senha.
- **Mínimo de Maiúsculas**. Define o número mínimo de caracteres
  alfabéticos maiúsculos necessários para uma senha.
- **Mínimo de minúsculas**. Define o número mínimo de caracteres
  alfabéticos minúsculas necessários para uma senha.

### Multi-factor Authentication

<img
src="https://docs.joomla.org/images/thumb/c/c0/Help-4x-Users-Options-multi-factor-authentication-subscreen-pt-br.png/600px-Help-4x-Users-Options-multi-factor-authentication-subscreen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c0/Help-4x-Users-Options-multi-factor-authentication-subscreen-pt-br.png/900px-Help-4x-Users-Options-multi-factor-authentication-subscreen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/c/c0/Help-4x-Users-Options-multi-factor-authentication-subscreen-pt-br.png/1200px-Help-4x-Users-Options-multi-factor-authentication-subscreen-pt-br.png 2x"
data-file-width="2002" data-file-height="1501" width="600" height="450"
alt="Users Options multi factor authentication subscreen pt" />

- **Allowed frontend module positions**. When displaying the frontend
  Multi-factor Authentication page all modules will be hidden except
  those in the positions selected here.
- Show title in frontendLanguages: Overrides.
- **Allowed backend module positions**. When displaying the backend
  Multi-factor Authentication page all modules will be hidden except
  those in the positions selected here. Please note that modules in the
  'title' position are always shown: this is required to show the
  backend page icon and title.
- **Disable Multi-factor Authentication**. Any user who belongs in *any*
  of the selected user groups will be exempt from Multi-factor
  Authentication. Even if they have set up Multi-factor Authentication
  methods they will not be asked to use them when they are logging in,
  nor will they be able to view them, remove them, or change their
  configuration.
- **Enforce Multi-factor Authentication**. Any user who belongs in *any*
  of the selected user groups will be required to enable Multi-factor
  Authentication before being able to use the site.
- **Frontend template style**. Choose the frontend template style to use
  in the Multi-factor Authentication page. Select 'Use Default" to use
  the default site template style.
- **Multi-factor Authentication after silent login**. Should the user
  have to go through Multi-factor Authentication after a silent user
  login? Silent logins are those which do not require a username and
  password for example the Remember Me feature, WebAuthn etc.
- **Silent login authentication response types (for experts)**. For
  experts. A comma–separated list of Joomla authentication response
  types which are considered silent logins. The default is 'cookie' (the
  Remember Me feature) and 'passwordless' (WebAuthn).
- **Onboard new users**. If the user has not yet set up Multi-factor
  Authentication and this option is enabled they will be redirected to
  the Multi-factor Authentication setup page or the custom URL you set
  up below. This is meant to be a simple way to to let your users know
  that Multi-factor Authentication is an option on your site.
- **Custom redirection URL**. If it's not empty redirects to this URL
  instead of the Multi-factor Authentication setup page when the option
  above is enabled.Warning: This must be a URL inside your site. You
  cannot log in to an external link or to a different subdomain.

### Histórico de notas de usuários

<img
src="https://docs.joomla.org/images/thumb/a/ac/Help-4x-Users-Options-user-notes-history-subscreen-pt-br.png/600px-Help-4x-Users-Options-user-notes-history-subscreen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/ac/Help-4x-Users-Options-user-notes-history-subscreen-pt-br.png/900px-Help-4x-Users-Options-user-notes-history-subscreen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/a/ac/Help-4x-Users-Options-user-notes-history-subscreen-pt-br.png/1200px-Help-4x-Users-Options-user-notes-history-subscreen-pt-br.png 2x"
data-file-width="2002" data-file-height="565" width="600" height="169"
alt="Users Options user notes history subscreen pt" />

- **Habilitar versões**. Save version history for User Notes.
- **Máximo de versões**.
  The maximum number of versions to store for a User Note. If a User
  Note is saved and the maximum number of versions has been reached, the
  oldest version will be deleted automatically. If set to 0, then
  versions will never be deleted automatically.Saiba mais.

### Enviar E-mail em massa para usuários

<img
src="https://docs.joomla.org/images/thumb/1/1c/Help-4x-Users-Options-mass-mail-users-subscreen-pt-br.png/600px-Help-4x-Users-Options-mass-mail-users-subscreen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1c/Help-4x-Users-Options-mass-mail-users-subscreen-pt-br.png/900px-Help-4x-Users-Options-mass-mail-users-subscreen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/1/1c/Help-4x-Users-Options-mass-mail-users-subscreen-pt-br.png/1200px-Help-4x-Users-Options-mass-mail-users-subscreen-pt-br.png 2x"
data-file-width="2002" data-file-height="879" width="600" height="263"
alt="Users Options mass mail users subscreen pt" />

- **Prefixo do Assunto**. Digite o texto opcional a ser inserido
  automaticamente no início do assunto do e-mail em massa.
- **Sufixo da Mensagem**. Digite o texto opcional a ser inserido
  automaticamente no fim do corpo do e-mail em massa (por exemplo, uma
  assinatura).

### Integração

<img
src="https://docs.joomla.org/images/thumb/9/9c/Help-4x-Users-Options-integration-subscreen-pt-br.png/600px-Help-4x-Users-Options-integration-subscreen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9c/Help-4x-Users-Options-integration-subscreen-pt-br.png/900px-Help-4x-Users-Options-integration-subscreen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/9/9c/Help-4x-Users-Options-integration-subscreen-pt-br.png/1200px-Help-4x-Users-Options-integration-subscreen-pt-br.png 2x"
data-file-width="2002" data-file-height="593" width="600" height="178"
alt="Users Options integration subscreen pt" />

- **Editar campos personalizados**. Habilita a criação de campos
  personalizados.

### Permissões

This section lets you set up the default Access Control List
permissions for all users.

<img
src="https://docs.joomla.org/images/thumb/8/8c/Help-4x-Users-Options-permissions-subscreen-pt-br.png/600px-Help-4x-Users-Options-permissions-subscreen-pt-br.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/8c/Help-4x-Users-Options-permissions-subscreen-pt-br.png/900px-Help-4x-Users-Options-permissions-subscreen-pt-br.png 1.5x, https://docs.joomla.org/images/thumb/8/8c/Help-4x-Users-Options-permissions-subscreen-pt-br.png/1200px-Help-4x-Users-Options-permissions-subscreen-pt-br.png 2x"
data-file-width="2002" data-file-height="1522" width="600" height="456"
alt="Users Options permissions subscreen pt" />

To change the permissions for users, do the following.

1.  Selecione o **grupo** clicando em seu título localizado à esquerda.
2.  Encontre a **ação** desejada.
    - **Configurar o Controle de Acesso e Opções**. Users can edit the
      options and permissions.
    - **Configurar somente as Opções**. Users can edit the options exept
      the permissions.
    - **Acesso à Interface de Administração**. Users can access user
      administration interface.
    - **Criar**. Users can create users.
    - **Apagar**. Users can delete users.
    - **Editar**. Users can edit users.
    - **Editar Estado**. User can change the published state and related
      information.
    - **Editar Valor**. Users can edit any value of custom fields
      submitted in users.
3.  Selecione a permissão desejada para a ação que deseja alterar.
    - **Herdado**. Inherited for users in this Group from the Global Configuration
      permissions.
    - **Permitido**. Permitido para usuários neste grupo.Observe que, se
      esta ação for negada em um dos níveis mais altos, a permissão
      permitida aqui não terá efeito. Uma configuração negada não pode
      ser substituída.
    - **Negado**. Negado para usuários neste grupo.
4.  Clique em **salvar** na **barra de ferramentas** na parte superior.
    Quando a tela for atualizada, a coluna de configuração calculada
    mostrará a permissão efetiva para este(a) grupo e ação.

## Barra de ferramentas

No topo da página você verá a barra de ferramentas mostrada na [captura
de tela](#screenshot) acima.

- **Salvar**. Saves the users options and stays in the current screen.
- **Salvar & Fechar**. Saves the users options and closes the current
  screen.
- **Fechar**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Toggle Inline Help**. Show help text below some options.
- **Help**. Opens this help screen.

## Dicas rápidas

If you are a beginning user, you can just keep the default values here
until you learn more about using global options.
