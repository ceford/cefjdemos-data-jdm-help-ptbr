<!-- Filename: Help5.x:Scheduled_Tasks / Display title: Tarefas Agendadas -->

## Descrição

Tarefas Agendadas são usadas para executar tarefas rotineiras de manutenção do site como uma alternativa aos trabalhos cron do servidor. As tarefas são definidas em plugins no grupo de tarefas. Vários plugins de tarefa são fornecidos e podem ser usados como exemplos para criar outras tarefas especializadas.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como Acessar

Iniciando no menu Administrador:

- Selecione **Sistema → Painel de Gerenciamento → Tarefas Agendadas**

A lista de Tarefas Agendadas inicial tem três itens.

## Captura de tela

![scheduled tasks list](../../../ptbr/images/maintenance/scheduled-tasks-list.png)

## Cabeçalhos de Coluna

Colunas exclusivas para tarefas agendadas:

- **Tipo de Tarefa** As tarefas são criadas a partir de uma lista disponível de tipos.
- **Data da Última Execução** A data e a hora da última execução da tarefa.
- **Data da Próxima Execução** A data e a hora da próxima execução da tarefa.
- **Teste de Tarefa** Um botão para executar a tarefa manualmente.
- **Prioridade da Tarefa** A prioridade pode ser Baixa, Normal ou Alta. Tarefas de maior prioridade podem potencialmente bloquear tarefas de prioridade inferior.

## Histórico de Execução

Selecione o botão na Barra de Ferramentas para ver uma lista de execuções de tarefas individuais.

![task execution history list](../../../ptbr/images/maintenance/scheduled-tasks-logs.png)

## Tarefas Disponíveis

A captura de tela a seguir mostra uma lista de tarefas disponíveis. Algumas são demonstrações, outras são úteis.

![Scheduled Tasks Available](../../../ptbr/images/maintenance/scheduled-tasks-types.png)

Cada tarefa tem seus próprios parâmetros relacionados à tarefa que devem ser autoexplicativos. Por exemplo, a tarefa **Site Offline** só faz sentido se a **Editar Tarefa → Campos Básicos → Regra de Execução** estiver definida como **Execução Manual**.

## Opções de Tarefas Programadas

Selecione o botão Opções na Barra de Ferramentas para configurar tarefas agendadas.

### Configurar aba Tarefas

![task timeout setting](../../../ptbr/images/maintenance/scheduled-tasks-options-configure-tasks.png)

- **Tempo Limite da Tarefa** O padrão é 300 segundos.

### Aba do Agendador Preguiçoso

![lazy schedule setting](../../../ptbr/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- Tarefas **habilitadas** são acionadas pelos visitantes do site.
- Tarefas **desabilitadas** devem ser acionadas por um cron job externo.
- **Intervalo de solicitação** O padrão é 300 segundos.

### Aba Web Cron

![web cron setting](../../../ptbr/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- **Web Cron** Desativado é o padrão. Ativado requer um hash para acionar a tarefa. Antes do primeiro salvamento, há uma mensagem informando que uma chave é necessária. Após o salvamento, há um campo contendo uma URL de link do Webcron para copiar.

*Traduzido por openai.com*

