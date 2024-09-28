<!-- Filename: Help4.x:Users:_Options  / Display title: Usuários: Opções -->

## Descrição

A página *Usuários: Opções* é usada para definir opções globais para todos os usuários, incluindo:

- Captcha,
- registro permitido e tipo de registro,
- grupo de usuários padrão para novos usuários,
- contador de redefinição de senha ou nome de usuário,
- aviso por e-mail de novo registro de usuário para a administração e mais.

## Como Acessar

* Selecione **Site → Usuários** no *Painel Inicial*. Ou...
* Selecione **Usuários → Gerenciar** no menu do Administrador. Então...
* Selecione o botão da barra de ferramentas **Opções**

## Captura de Tela

![opções de usuários aba de opções de usuários](../../../ptbr/images/users/users-options-user-options-tab.png)

## Campos de Formulário

### Aba Opções do Usuário

- **Permitir Registro de Usuário**
  - *Sim* Os usuários podem se registrar no Frontend do site usando o
    link *Criar uma Conta* fornecido no formulário de Login.
  - *Não* O link *Criar uma Conta* não será exibido.
- **Grupo Padrão de Registro de Novo Usuário** O grupo ao qual os usuários são atribuídos por
  padrão quando se registram no site. Padrão é *Registrado*.
- **Grupo de Usuários Convidados** O grupo ao qual os convidados são atribuídos (Convidados
  são visitantes do site que não estão logados). É possível
  criar conteúdo no site que seja visível para convidados, mas não visível
  para usuários logados.
- **Enviar Senha** Se configurado como *Sim*, a primeira senha do usuário será
  enviada por e-mail ao usuário como parte do e-mail de registro.
- **Ativação de Nova Conta de Usuário**
  - *Nenhuma* A conta de usuário será ativada imediatamente sem nenhuma ação necessária.
  - *Usuário* O usuário receberá um e-mail com um link de ativação. A
    conta será ativada quando o usuário selecionar o link de ativação.
  - *Administrador* O usuário receberá um e-mail com um link de ativação.
    Quando o usuário selecionar esse link, o Administrador do Site será notificado via
    e-mail e solicitado a ativar a conta do usuário.
- **Enviar E-mail para Administradores** Enviar notificação por e-mail para
  administradores com *Ativação de Nova Conta de Usuário* configurada como *Nenhuma* ou *Usuário*.
- **Captcha** O plugin Captcha para Registro de Conta de Usuário, Lembrete de Senha
  de Usuário e Lembrete de Nome de Usuário.
- **Parâmetros de Usuário no Frontend**
  - *Mostrar* Os usuários poderão modificar as Configurações Básicas no Frontend do site.
  - *Ocultar* O usuário não poderá alterar essas configurações.
- **Idioma do Frontend** Mostrar ou Ocultar o idioma do site.
- **Alterar Nome de Usuário** Permitir que o usuário altere o Nome de Usuário.

### Aba Opções de Domínio de E-mail

![aba opções de domínio de e-mail dos usuários](../../../ptbr/images/users/users-options-email-domain-options-tab.png)

- **Nome de Domínio** Insira uma lista de domínios de e-mail permitidos e não permitidos.
  Por padrão, todos os domínios são permitidos. Curingas (\*) são suportados. Por
  exemplo:
  - \* (Asterisco): Permite ou não permite todos os domínios
  - \*.com: Permite ou não permite todos os domínios '.com'
  - \*.joomla.org: Permite ou não permite todos os subdomínios 'joomla.org'.
- **Regra** Selecione se deseja permitir ou não o domínio.

### Aba Opções de Senha

![aba opções de senha dos usuários](../../../ptbr/images/users/users-options-password-options-tab.png)

- **Contagem Máxima de Redefinições** O número máximo de redefinições de senha permitidas
  dentro do período de tempo. Zero indica sem limite.
- **Tempo de Redefinição** O período de tempo, em horas, para o contador de redefinição.
- **Comprimento Mínimo** Defina o comprimento mínimo para uma senha.
- **Mínimo de Números** Defina o número mínimo de números que devem ser
  incluídos em uma senha.
- **Mínimo de Símbolos** Defina o número mínimo de símbolos (como !@#\$)
  exigidos em uma senha.
- **Mínimo de Letras Maiúsculas** Defina o número mínimo de caracteres alfabéticos maiúsculos
  exigidos para uma senha.
- **Mínimo de Letras Minúsculas** Defina o número mínimo de caracteres alfabéticos minúsculos
  exigidos para uma senha.

### Aba Autenticação Multi-fator

![aba autenticação multi-fator dos usuários](../../../ptbr/images/users/users-options-multi-factor-authentication-tab.png)

- **Posições de módulos de frontend permitidas** Ao exibir a página de
  Autenticação Multi-fator no frontend todos os módulos serão ocultados, exceto
  os nas posições selecionadas aqui.
- **Mostrar título no frontend** Exibir um título na página de
  verificação de Autenticação Multi-fator no frontend? Observe que o
  título é sempre exibido no backend. Se você precisar alterar o
  título, substitua a chave de idioma `COM_USERS_HEADING_MFA` usando
  Idiomas: Substituições.
- **Posições de módulos de backend permitidas** Ao exibir a página de
  Autenticação Multi-fator no backend todos os módulos serão ocultados, exceto
  os nas posições selecionadas aqui. Observe que os módulos na
  posição `title` são sempre exibidos: isso é necessário para exibir o
  ícone da página do backend e o título.
- **Desativar Autenticação Multi-fator** Qualquer usuário que pertença a *qualquer*
  um dos grupos de usuários selecionados estará isento da Autenticação
  Multi-fator. Mesmo que tenham configurado métodos de Autenticação Multi-fator,
  eles não serão solicitados a usá-los ao fazer o login,
  nem poderão exibi-los, removê-los ou alterar sua
  configuração.
- **Enforce Multi-factor Authentication** Qualquer usuário que pertença a *qualquer*
  um dos grupos de usuários selecionados será obrigado a habilitar a Autenticação
  Multi-fator antes de poder usar o site.
- **Estilo do template do frontend** Escolha o estilo do template do frontend a ser usado
  na página de Autenticação Multi-fator. Selecione *Usar Padrão* para usar
  o estilo do template padrão do site.
- **Autenticação Multi-fator após login silencioso** O usuário deve
  passar pela Autenticação Multi-fator após um login silencioso? Logins silenciosos são aqueles
  que não exigem um nome de usuário e senha, por exemplo, o recurso Lembrar-me, WebAuthn, etc.
- **Tipos de resposta de autenticação de login silencioso (para especialistas)** Para
  especialistas. Uma lista separada por vírgulas de tipos de resposta de autenticação do Joomla
  que são considerados logins silenciosos. O padrão é `cookie` (o
  recurso Lembrar-me) e `sem senha` (WebAuthn).
- **Onboard novos usuários** Se o usuário ainda não configurou a Autenticação
  Multi-fator e esta opção estiver ativada, ele será redirecionado para
  a página de configuração de Autenticação Multi-fator ou para a URL personalizada que você configurou
  abaixo. Esta é uma forma simples de informar seus usuários de
  que a Autenticação Multi-fator é uma opção no seu site.
- **URL de redirecionamento personalizado** Se não estiver vazio, redireciona para esta URL
  em vez da página de configuração de Autenticação Multi-fator quando a opção
  acima está habilitada. Aviso: Esta deve ser uma URL dentro do seu site. Você
  não pode entrar em um link externo ou em um subdomínio diferente.

### Aba Histórico de Notas de Usuário

![aba histórico de notas de usuário](../../../ptbr/images/users/users-options-user-notes-history-tab.png)

- **Habilitar Versões** Salvar histórico de versões para Notas de Usuário.
- **Máximo de Versões** O número máximo de versões a serem armazenadas para uma
  Nota de Usuário. Se uma Nota de Usuário for salva e o número máximo de versões
  tiver sido atingido, a versão mais antiga será excluída automaticamente. Se
  configurado como 0, as versões nunca serão excluídas automaticamente.

### Aba E-mail em Massa para Usuários

![aba e-mail em massa para usuários](../../../ptbr/images/users/users-options-mass-mail-users-tab.png)

- **Prefixo do Assunto** Insira um texto opcional a ser inserido automaticamente
  antes do assunto do e-mail em massa.
- **Sufixo do Corpo do E-mail** Insira um texto opcional a ser inserido automaticamente
  após o corpo do e-mail (por exemplo, uma assinatura).

### Aba Integração

![aba integração dos usuários](../../../ptbr/images/users/users-options-integration-tab.png)

- **Habilitar Campos Personalizados** Habilitar a criação de campos personalizados.

## Dicas

Se você é um usuário iniciante, mantenha os valores padrão aqui
até aprender mais sobre o uso das opções globais.

*Traduzido por openai.com*

