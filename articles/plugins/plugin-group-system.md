<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_System_Group  / Display title: Grupo de Sistemas -->

## Descrição do Grupo

### Sistema - Recursos Adicionais de Acessibilidade

Este plugin adiciona uma barra de ferramentas de acessibilidade ao seu site com opções de acessibilidade adicionais.

![Formulário de recursos adicionais de acessibilidade do sistema](../../../ptbr/images/plugins/plugin-group-system-additional-accessibility-features.png)

### Sistema - Depuração

Este plugin fornece informações de depuração. O relatório é exibido abaixo da tela principal das interfaces frontend e backend de uma instalação do Joomla!.

#### Aba do Plugin

![Aba do plugin no formulário de depuração do sistema](../../../ptbr/images/plugins/plugin-group-system-debug-plugin-tab.png)

- **Grupos Permitidos** Grupos de usuários que verão as informações de depuração quando ativado.
- **Exibir Perfilagem** Exibir ou não as informações de pontos de perfilagem.
- **Exibir Consultas** Incluir ou não o log de consultas SQL nas informações de depuração.
- **Exibir Uso de Memória** Incluir ou não os dados de uso de memória nas informações de depuração.

#### Aba de Idioma

![Aba de idioma no formulário de depuração do sistema](../../../ptbr/images/plugins/plugin-group-system-debug-language-tab.png)

- **Mostrar erros ao analisar arquivos de idioma** Exibir ou não uma lista de arquivos de idioma com erros devido à sua não conformidade com a especificação de arquivos de idioma do Joomla!.
- **Mostrar Arquivos de Idioma** Exibir ou não os arquivos de idioma que foram carregados para gerar a página.
- **Mostrar Cadeias de Idioma** Incluir ou não cadeias de idioma indefinidas nas informações de depuração.
- **Remover a Primeira Palavra** Sempre remover ou não a primeira palavra em cadeias de palavras múltiplas.
- **Remover do Início** Remove as palavras especificadas do início da cadeia de idioma. Para várias palavras, separe cada palavra com o caractere pipe ( | ) assim: palavra1|palavra2
- **Remover do Fim** Remove as palavras especificadas do final da cadeia de idioma. Para várias palavras, separe cada palavra com o caractere pipe ( | ) assim: palavra1|palavra2

#### Aba de Registro

![Aba de registro no formulário de depuração do sistema](../../../ptbr/images/plugins/plugin-group-system-debug-logging-tab.png)

### Sistema - Campos

O plugin de campos do sistema que é necessário para exibir os campos personalizados.

### Sistema - Cabeçalhos HTTP

Este plugin pode configurar Cabeçalhos de Segurança HTTP. Favor verificar a documentação de Gerenciamento de Cabeçalhos HTTP para mais detalhes sobre este plugin.

![Formulário de cabeçalhos HTTP do sistema](../../../ptbr/images/plugins/plugin-group-system-http-headers.png)

### Sistema - Destaque

Plugin do sistema para destacar termos especificados.

### Sistema - Agendador de Tarefas

Este plugin procura por tarefas de plugin de trabalhos a serem executadas.

![Formulário de agendador de tarefas do sistema](../../../ptbr/images/plugins/plugin-group-system-job-scheduler.png)

- **Frequência (em minutos)** Defina como zero para executar em cada carregamento de página (para testes).
- **Webcron** Defina como Sim para chamar como um comando CLI. Para mais informações veja Escrevendo uma Aplicação CLI.
- **Chave de Ativação** A chave a ser passada em um comando Webcron.

### Sistema - Estatísticas do Joomla!

![Formulário de estatísticas do Joomla! do sistema](../../../ptbr/images/plugins/plugin-group-system-joomla-statistics.png)

- **ID Único** Um identificador que permite ao projeto Joomla! contar instalações únicas do plugin. Isso é enviado com as estatísticas de volta ao servidor.
- **Intervalo (horas)** As estatísticas serão enviadas a cada X horas. O padrão é 12.
- **Modo** Selecione a maneira pela qual você deseja que as estatísticas sejam enviadas.

### Sistema - Notificação de Atualização do Joomla!

![Formulário de notificação de atualização do Joomla! do sistema](../../../ptbr/images/plugins/plugin-group-system-joomla-update-notification.png)

- **Emails de Super Usuários** Uma lista separada por vírgulas dos endereços de email que receberão emails de notificação de atualização. Os endereços na lista DEVEM pertencer a usuários existentes do seu site que têm privilégio de Super Usuário. Se nenhum dos emails listados pertencer aos Super Usuários, ou se estiver em branco, todos os Super Usuários deste site receberão o email de notificação de atualização.
- **Idioma do Email** Se você escolher Automático (padrão), o email de notificação de atualização para os Super Usuários estará no idioma do site no momento em que o plugin for acionado. Selecionando um idioma aqui você está forçando os emails de notificação de atualização a serem enviados neste idioma específico.

### Sistema - Código de Idioma

Fornece a habilidade de alterar o código de idioma no documento HTML gerado para melhorar o SEO. Os campos aparecerão quando o plugin estiver ativado e salvo. Mais informações em W3.org.

### Sistema - Filtro de Idioma

![Formulário de filtro de idioma do sistema](../../../ptbr/images/plugins/plugin-group-system-language-filter.png)

- **Seleção de Idioma para novos Visitantes** Selecione o idioma padrão do site ou detecte as configurações do navegador automaticamente.
- **Mudança Automática de Idioma** Esta opção mudará automaticamente o idioma do conteúdo usado no Frontend quando o idioma do site do usuário for alterado.
- **Associações** Permite a associação de itens ao alternar de um idioma para outro.
- **Adicionar Meta Tags Alternativas** Adiciona meta tags alternativas para itens de menu com itens de menu associados em outros idiomas.
- **Adicionar Meta Tag x-default** Adiciona a meta tag x-default para melhorar o SEO.
- **Idioma x-default** Escolha seu idioma x-default.
- **Remover Código de Idioma da URL** Remover ou não o Código de Idioma da URL definido (ex. seu_dominio.com/ptbr) do seu Idioma de Conteúdo que corresponde ao idioma padrão do site quando a URL SEF está configurada como *Sim*.
- **Duração do Cookie** Os cookies de idioma podem ser configurados para expirar no final da *Sessão* ou após *um ano*.

### Sistema - Rotação de Logs

![Formulário de rotação de logs do sistema](../../../ptbr/images/plugins/plugin-group-system-log-rotation.png)

- **Rotação de Logs (em dias)** Com que frequência os logs devem ser rotacionados.
- **Logs Máximos** O número máximo de logs antigos a serem mantidos.

### Sistema - Logout

O plugin de logout do sistema permite ao Joomla redirecionar o usuário para a página inicial se ele escolher fazer logout enquanto está em uma página de acesso protegido.

### Sistema - Cache de Página

Este plugin habilita o cache de página. O cache de página permite que o servidor web salve snapshots de páginas e os utilize ao servir páginas web. Isso melhora o desempenho do seu site e reduz a carga de trabalho do servidor. Este plugin possui as seguintes opções:

![Formulário de cache de página do sistema](../../../ptbr/images/plugins/plugin-group-system-page-cache.png)

- **Usar Cache do Navegador** Utilizar ou não o mecanismo para armazenar um cache de página no navegador local. O padrão é *Não*.
- **Excluir Itens de Menu** Selecione quais itens de menu você deseja excluir do cache.

### Sistema - Consentimento de Privacidade

Este plugin permite coletar o consentimento dos seus usuários para a política de privacidade do site e gerenciar a expiração do consentimento.

![Formulário de consentimento de privacidade do sistema](../../../ptbr/images/plugins/plugin-group-system-privacy-consent.png)

- **Resumo da Política de Privacidade** Permite inserir um resumo da sua política de privacidade ou manter a existente.
- **Tipo de Privacidade** Escolha entre Artigo e Item de Menu. Dependendo da escolha, um ou outro dos dois campos seguintes estará presente.
- **Artigo de Privacidade** Selecione ou Crie um Artigo para sua política de privacidade para vincular ao formulário do seu usuário.
- **Item de Menu de Privacidade** Selecione ou Crie um Item de Menu vinculado a um Artigo contendo sua política de privacidade.
    - *Nota:* Tenha cuidado extra com sites multilíngues. É melhor garantir que o Artigo ou Item de Menu ocorram como Associações em todos os idiomas.
- **Mensagem de Redirecionamento** A mensagem que será exibida no redirecionamento. Insira sua própria mensagem ou mantenha a existente.

![Aba de expiração do formulário de consentimento de privacidade do sistema](../../../ptbr/images/plugins/plugin-group-system-privacy-consent-expiration.png)

- **Habilitar** (Sim/Não) A expiração está desativada por padrão. Ative se deseja realizar verificações para a expiração dos consentimentos de privacidade.
- **Verificação periódica (dias)** (0 a 120 dias) 30 dias por padrão. Se a Expiração estiver ativada, defina o número de dias para realizar a verificação.
- **Expiração** (180 a 720 dias) 360 dias por padrão. Se a Expiração estiver ativada, defina o número de dias para expirar o consentimento de privacidade.
- **Lembrar** (0 a 120 dias) 30 dias por padrão. Se a Expiração estiver ativada, defina o número de dias para enviar um lembrete antes da expiração do consentimento de privacidade.

### Sistema - Redirecionamento

![Formulário de redirecionamento do sistema](../../../ptbr/images/plugins/plugin-group-system-redirect.png)

- **Coletar URLs** Esta opção controla a coleta de URLs. Isso é útil para evitar carga desnecessária no banco de dados.
- **Incluir Nome de Domínio em URLs Expirados** Salvar a URL expirada como absoluta (incluir domínio) ou relativa (excluir domínio).
- **Excluir URLs** Defina expressões regulares ou termos que devem ser excluídos ao salvar.

### Sistema - Lembrar de Mim

Este plugin fornece funcionalidade de *Lembrar de Mim*. Isso permite que o site *lembre* seu nome de usuário e senha para que você possa ser automaticamente logado quando retornar ao site. Este plugin não tem opções.

### Sistema - SEF

Este plugin adiciona suporte SEF aos links no documento. Ele opera diretamente no HTML e não requer uma tag especial. Ele possui as seguintes opções:

![Formulário de SEF do sistema](../../../ptbr/images/plugins/plugin-group-system-sef.png)

- **Domínio do Site** Se o seu site puder ser acessado através de mais de um domínio, insira o domínio preferencial (às vezes referenciado como canônico) aqui. Nota: https://exemplo.com e https://www.exemplo.com são domínios diferentes.

### Sistema - Limpeza de Dados de Sessão

![Formulário de limpeza de dados de sessão do sistema](../../../ptbr/images/plugins/plugin-group-system-session-data-purge.png)

- **Habilitar Limpeza de Dados de Sessão** Quando ativado, este plugin tentará limpar dados expirados com base na frequência calculada pela probabilidade e divisor.
- **Habilitar Limpeza de Metadados de Sessão** Quando ativado, este plugin limpará metadados opcionais de sessão do banco de dados. Observe que essa operação não será executada quando o manipulador de banco de dados estiver em uso, pois esses dados são apagados como parte da operação de Limpeza de Dados de Sessão.
- **Probabilidade** Em combinação com o campo divisor, esses dois campos são usados para determinar a frequência da operação de limpeza de dados de sessão sendo acionada em uma solicitação.
- **Divisor** Em combinação com o campo probabilidade, esses dois campos são usados para determinar a frequência da operação de limpeza de dados de sessão sendo acionada em uma solicitação. A probabilidade é calculada usando probabilidade/divisor, por exemplo, 1/100 significa que há uma chance de 1% de que o processo seja executado em cada solicitação.

### Sistema - Pular para Navegação

O plugin cria um menu dropdown consistindo dos links para os locais importantes em uma determinada página web. Isso facilita para usuários de teclado e leitores de tela pular rapidamente para o local desejado escolhendo-o da lista de opções.

![Formulário de pular para navegação do sistema](../../../ptbr/images/plugins/plugin-group-system-skip-to-navigation.png)

### Sistema - Registro de Ações do Usuário

![Formulário de registro de ações do usuário do sistema](../../../ptbr/images/plugins/plugin-group-system-user-actions-log.png)

- **Dias para excluir logs após** Insira quantos dias os logs devem ser mantidos antes de serem excluídos. Insira 0 se você não quiser excluir os logs.

### Sistema - Registro de Usuário

![Formulário de registro de usuário do sistema](../../../ptbr/images/plugins/plugin-group-system-user-log.png)

- **Registrar Nomes de Usuário** Esta opção registrará o nome de usuário utilizado quando uma autenticação falhar.

*Traduzido por openai.com*

