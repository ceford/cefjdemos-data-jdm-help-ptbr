<!--
{
    "source": "https://docs.joomla.org/Help4.x:Joomla_Update",
    "title": "Atualiza\u00e7\u00e3o do Joomla: Introdu\u00e7\u00e3o",
    "description": " ",
    "author": ""
}
-->

## Descrição

Esta página permite atualizar o Joomla! usando um pacote de atualização do
repositório de código do Joomla!. É melhor e mais seguro permitir que o Joomla
se atualize usando este método.

## Como Acessar

No **Painel inicial → Painel de notificações**, o ícone do Joomla exibirá
uma de duas mensagens:
- **O Joomla está atualizado**
- **X.Y.Z disponível - Atualize agora!**

Selecione o ícone.

Além disso, o **Sistema → Painel de atualização → Joomla** exibirá uma marca
de seleção, indicando que está atualizado, ou um número de versão, indicando
que uma nova versão está disponível.

## Captura de tela

Se o seu site estiver atualizado, você verá esta tela:

![Upload e atualização atualizados](../../../en/images/joomla-update/joomla-update/01-upload-update-up-to-date.png)

Se houver uma atualização disponível, você verá esta tela:

![Upload e atualização disponível](../../../en/images/joomla-update/joomla-update/02-upload-update-available.png)

Se estiver atualizando uma versão principal ou secundária, você verá uma tela
de verificação pré-atualização:

![Upload e atualização: verificação pré-atualização](../../../en/images/joomla-update/joomla-update/03-upload-update-pre-update-check.png)

Selecione cada um dos três itens de menu para verificar se algo precisa de atenção.

## Iniciar atualização

Se você não estiver usando a versão mais recente do Joomla, poderá instalar a
atualização mais recente nesta página. Para isso, certifique-se de ter feito
um backup e marque a caixa de seleção **Estou ciente...** para indicar que
você fez isso. Em seguida, selecione o botão **Iniciar atualização** e o Joomla
instalará a versão mais recente.

A tela de atualização mostra uma barra de progresso enquanto a atualização está em andamento.

### Enviar e atualizar

Você pode usar este botão para atualizar o Joomla se o seu servidor estiver
atrás de um firewall ou, de outra forma, não conseguir entrar em contato com
os servidores de atualização. Primeiro, baixe o Pacote de atualização do Joomla
em formato ZIP na página oficial de downloads do Joomla.

Você deve definir *upload_max_filesize* e *post_max_size* do PHP como 64 Mb
e o limite de memória do PHP como 256 Mb. Caso contrário, a atualização poderá
falhar. Um bom motivo para fazer aquele backup!

![Enviar e atualizar: enviar e instalar](../../../en/images/joomla-update/joomla-update/04-upload-update-upload-install.png)

## Opções de atualização

O botão Opções da barra de ferramentas permite selecionar o tipo de atualização:

- **Padrão** É usado para sites configurados para permanecer na versão instalada.
- **Joomla Next** É usado para sites que normalmente passam para a próxima versão
  principal assim que uma versão estável é lançada.
- **URL personalizada** Para desenvolvedores selecionarem uma fonte de atualização.

*Traduzido por openai.com*