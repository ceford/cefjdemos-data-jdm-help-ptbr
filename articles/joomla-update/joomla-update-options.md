<!--
{
    "source": "https://docs.joomla.org/Help4.x:Joomla_Update:_Options",
    "title": "Atualiza\u00e7\u00e3o do Joomla: Op\u00e7\u00f5es",
    "description": " ",
    "author": ""
}
-->

## Descrição

A página Atualização do Joomla: Opções é usada para definir parâmetros que controlam o processo de atualização do núcleo do Joomla.

### Elementos comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars)

## Como acessar

- Selecione **Sistema → Painel de atualização → Joomla** no menu do Administrador. Em seguida...
  - Selecione o botão **Opções** na barra de ferramentas.

## Captura de tela

![Opções de atualização do Joomla — Fonte da atualização](../../../ptbr/images/joomla-update/joomla-update-options/01-update-source.png)

## Campos do formulário

### Aba Fonte da atualização

- **Canal de atualização**
  - **Padrão** Esta configuração faz com que o Joomla exiba um aviso quando uma nova versão secundária ou de correção estiver disponível para a versão principal atual.
  - **Próxima versão do Joomla** Esta configuração faz com que o Joomla exiba um aviso quando uma nova versão principal estável estiver disponível e todas as versões secundárias e extensões existentes estiverem atualizadas.
  - **URL personalizada** Para desenvolvedores do Joomla. Mais campos serão exibidos.
- **Estabilidade mínima** O nível mínimo de estabilidade das atualizações de extensões que você deseja ver. Desenvolvimento é o menos estável; Estável é a qualidade de produção. Se uma extensão não especificar um nível, presume-se que seja Estável.
  - **Desenvolvimento** Para sites de desenvolvedores do Joomla.
  - **Alfa** Para sites de teste Alfa.
  - **Beta** Para sites de teste Beta.
  - **Candidata a lançamento** Para sites de teste de candidatas a lançamento.
  - **Estável** Para sites de produção.
- **URL personalizada** Se uma URL personalizada foi selecionada no Canal de atualização, um campo para inserir a URL aparece aqui.
- **Caixa de seleção de extensões potencialmente incompatíveis** Exibe a caixa de seleção na verificação pré-atualização se alguma das extensões instaladas no seu site for potencialmente incompatível com a versão do Joomla para a qual você está atualizando.  
  *Observação:* a caixa de seleção é exibida ao atualizar para uma nova família de versões do Joomla (versão secundária ou principal).
- **Caixa de seleção Confirmar backup** Exibe a caixa de seleção para confirmar que você fez um backup e está pronto para atualizar na etapa final antes de a atualização ser realmente aplicada.

### Aba Atualizações automatizadas

*As atualizações automatizadas estão disponíveis a partir do Joomla 5.4 para sites acessíveis publicamente na internet. Se o seu site estiver atrás de um firewall ou não estiver acessível publicamente, como em um ambiente de teste local, será necessário atualizá-lo manualmente.*

![Opções de atualização do Joomla — Fonte da atualização](../../../ptbr/images/joomla-update/joomla-update-options/02-automated-updates.png)

- **Atualização automatizada** Quando definido como *Sim*, seu site será atualizado automaticamente para a versão secundária ou de correção mais recente (incluindo correções de segurança) assim que ela estiver disponível. As versões principais não estão incluídas.
- **Token de atualização** Este é um token que identifica este site. Ele é criado pelo servidor remoto de atualização do Joomla e não pode ser alterado pelo usuário.
- **Última verificação** A data mais recente em que seu site entrou em contato com o servidor de atualização.
- **Enviar e-mail para grupos de usuários** Todos os usuários dos grupos selecionados receberão e-mails sobre atualizações automatizadas bem-sucedidas ou malsucedidas. Se nenhum usuário for encontrado, os e-mails serão enviados a todos os superusuários. Os destinatários devem ter a opção Receber e-mails do sistema ativada.

Use o botão *Alternar ajuda embutida* para obter mais detalhes.

*Traduzido por openai.com*