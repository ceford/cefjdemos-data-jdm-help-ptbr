<!-- Filename: Help4.x:Users:_Edit_Profile  / Display title: Usuários: Novo ou Editar -->

## Descrição

A página *Usuários: Novo ou Editar* é usada para criar um novo usuário ou editar um usuário existente.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como acessar

Para editar um usuário existente:

- Selecione **Usuários → Gerenciar** no menu do Administrador. Em seguida...
  - Procure pelo usuário necessário e selecione o link do nome na
    coluna **Nome**.

Para criar um novo usuário:

- Selecione **Usuários → Gerenciar** no menu do Administrador. Em seguida...
  - Selecione o botão **Novo** na Barra de Ferramentas.
- Ou... Selecione **Usuários → Gerenciar → Ícone de Adição** no
  menu do Administrador.
- Ou... Selecione **Usuários → Ícone de Dashboard** no menu do
  Administrador. Em seguida...
  - Selecione o ícone **Adicionar** no painel de Usuários.
- Ou... Selecione **Dashboard Inicial → Painel do Site → Ícone de Adição de Usuários**
  começando pelo menu do Administrador.

## Captura de Tela

![editar detalhes do usuário](../../../ptbr/images/users/users-edit-account-details-tab.png)

## Campos do Formulário

### Detalhes da Conta

- **Nome** Insira o nome do usuário.
- **Nome de Login** Insira o nome de login (Nome de Usuário) para o usuário.
- **Senha** Preencha uma (nova) senha. Embora este campo não seja obrigatório, o usuário não conseguirá fazer login se nenhuma senha for definida.
- **Confirmar Senha** Preencha novamente a senha do campo acima para verificá-la. Este campo é obrigatório quando você preencheu o campo Nova Senha.
- **Email** Insira um endereço de email para o usuário.
- **Data de Registro** Data de registro do usuário.
- **Data da Última Visita** Data da última visita do usuário ao site.
- **Data do Último Reset** Data e hora do último reset de senha.
- **Contagem de Resets de Senha** Número de resets de senha desde o início do último reset.
- **Receber Emails do Sistema** (*Sim*/*Não*) Se configurado para sim, o usuário receberá emails do sistema.
- **Status do Usuário** (*Bloqueado*/*Habilitado*) Habilite ou bloqueie este usuário.
- **Requerer Reset de Senha** (*Sim*/*Não*) Se configurado para sim, o usuário terá que redefinir sua senha na próxima vez que fizer login no site.
- **ID** Número de registro no banco de dados.

### Aba Grupos de Usuários Atribuídos

![aba de grupos de usuários atribuídos ao editar usuário](../../../ptbr/images/users/users-edit-assigned-user-groups-tab.png)

O padrão é *Registrado*, mas pode ser alterado na página *Usuário: Opções*.

### Configurações Básicas

![aba de configurações básicas ao editar usuário](../../../ptbr/images/users/users-edit-basic-settings-tab.png)

- **Estilo do Template de Backend** Selecione um estilo de template para a interface de Backend do administrador. Isto afetará apenas este Usuário.
- **Idioma do Backend** Selecione o idioma para a interface de Backend do administrador. Isto afetará apenas este Usuário.
- **Idioma do Frontend** Selecione o idioma para a interface de frontend. Isto afetará apenas este Usuário.
- **Editor** Selecione um editor para este usuário. O padrão é TinyMCE, a menos que alterado na Configuração Global.
- **Fuso Horário** Há uma longa lista de fusos horários para escolher, organizada por continente, com a Europa perto do final. O fuso horário padrão do site é definido na Configuração Global.

### Configurações de Acessibilidade

![aba de configurações de acessibilidade ao editar usuário](../../../ptbr/images/users/users-edit-accessibility-settings-tab.png)

- **Monocromático** Sim/Não
- **Alto Contraste** Sim/Não
- **Destacar Links** Sim/Não
- **Aumentar Tamanho da Fonte** Sim/Não

### Opções de Registro de Ações do Usuário

Esta aba está disponível apenas para Super Usuários!

- **Enviar notificações para o Registro de Ações do Usuário** Se configurado para sim, o Usuário receberá notificações de registro de ações do usuário por email.
- **Selecionar eventos para ser notificado** Selecione as notificações do registro de ações do usuário para serem enviadas por email.

### Login de Autenticação Web W3C (WebAuthn)

Esta aba está presente apenas quando o site é acessado usando https. Para configurar o login sem senha, você precisa de um dispositivo de hardware, disponível na Amazon e em lojas similares por cerca de £15, ou um dispositivo com reconhecimento de impressão digital ou de rosto ou software biométrico similar. Você pode adicionar mais de um autenticador. Uma vez configurado, você pode fazer login clicando no botão de Autenticação Web no formulário de Login e depois pressionando o botão no dispositivo quando solicitado.

Esta aba está presente, mas não pode ser usada no formulário de edição de Usuário porque o login sem senha só pode ser configurado pelo próprio usuário através do formulário Editar Perfil.

### Token da API do Joomla

Esta aba é usada para gerenciar os tokens de segurança usados para autenticar no aplicativo API do Joomla (acesso remoto ao seu site). Se você não tem certeza do que isso faz, as chances são de que você não precisa e pode ignorar essas configurações com segurança.

O token é visível apenas para sua própria conta.

### Autenticação Multi-fator

![aba de autenticação multi-fator ao editar usuário](../../../ptbr/images/users/users-edit-multi-factor-authentication-tab.png)

Esta aba permite que você configure um ou mais métodos para permitir acesso à sua conta após o login com Nome de Usuário e Senha. Está presente apenas ao editar seu próprio perfil. Há vários métodos disponíveis. Se você perder acesso a um método por qualquer motivo, pode escolher outro método na tela de verificação pós-login. Os métodos alternativos devem ter sido configurados com antecedência!

#### Códigos de Backup

Este método gera um conjunto de números que você pode salvar ou imprimir. Cada número pode ser usado apenas uma vez, então lembre-se de atualizar sua lista após o uso.

#### Código de Verificação

Um formulário extra para preencher com métodos alternativos de configuração do código. Dê uma olhada e clique no botão Cancelar se decidir não prosseguir.

#### Chave Yubi

Este é para outro tipo de chave de hardware que fornece um código em uma tela. Dê uma olhada e selecione Cancelar se decidir não prosseguir.

#### Autenticação Web

Para um dispositivo de hardware com um botão para pressionar. Dê uma olhada e selecione Cancelar se decidir não prosseguir. Note que este método será ignorado se você usar o método separado de Login WebAuthn.

#### Código por Email

Com este método, um código é enviado para o seu endereço de email. Você será solicitado a inserir esse código para acessar o site. É um código de uso único. Um novo é enviado para cada login. Dê uma olhada e selecione Cancelar se decidir não prosseguir.

## Dicas

- Nome, Nome de Login e Email são obrigatórios.
- Se você não preencher um idioma específico, editor, site de ajuda e/ou
  fuso horário, as configurações padrão da Configuração Global,
  Gerenciador de Idiomas e/ou Gerenciador de Templates serão usadas.

*Traduzido por openai.com*

