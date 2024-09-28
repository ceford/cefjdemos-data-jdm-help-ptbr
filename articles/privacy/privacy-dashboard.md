<!-- Filename: Help4.x:Privacy_Dashboard  / Display title: Painel de Privacidade -->

## Descrição

A página de *Painel de Privacidade* lista o Tipo de Solicitação de Privacidade do Usuário, Status e Número de solicitações.

### Tutoriais

- [Visão Geral de Privacidade - Conteúdo e Fluxo de Trabalho](https://docs.joomla.org/Help4.x:Components_Privacy_Outline/en)
- [O Conjunto de Ferramentas de Privacidade](https://docs.joomla.org/J3.x:Privacy/en)
  (Tutorial Detalhado do Joomla 3)
- [Fluxo de Trabalho para Solicitação de Informações](https://docs.joomla.org/J3.x:Information_Request_Workflow_in_Privacy_Component/en)
  (Tutorial Detalhado do Joomla 3)

## Como acessar

- Selecione **Usuários → ícone do Painel de Privacidade** no menu do Administrador.

## Captura de Tela

![painel de privacidade](../../../ptbr/images/privacy/privacy-dashboard.png)

## Painéis de Dashboard

### Status de Privacidade

- **Política de Privacidade Publicada** Indica se uma Política de Privacidade está disponível. Navegue para *Plugins → Sistema - Consentimento de Privacidade* e selecione seu Artigo de Privacidade. Uma vez publicado, você pode editar seu artigo de Política de Privacidade a partir desta página.
- **Item de Menu do Formulário de Solicitação Publicado** Indica se o Item de Menu (que permite que os usuários enviem solicitações) está publicado ou não. Para criá-lo, navegue até seu Menu → Adicionar Novo Item de Menu → Tipo de Item de Menu: Criar Solicitação. Uma vez publicado, você pode editar seu item de menu a partir desta tela.
- **Solicitações Urgentes Pendentes** Número de solicitações urgentes que são mais antigas do que o número de dias definido nas Opções de Componente (de 10 a 29 dias).
- **Envio de E-mail Habilitado**
- **Criptografia de conexão do banco de dados**

### Solicitações de Privacidade

- **Tipo de Solicitação** Exibe os dois diferentes tipos de solicitação:
  - *Exportar* quando um usuário enviou uma solicitação para exportar seus dados
  - *Remover* quando um usuário enviou uma solicitação para ser removido.
- **Status** Exibe o status da solicitação
  - *Inválido* um Superusuário invalidou a solicitação
  - *Pendente* quando um usuário enviou uma solicitação, mas ainda não confirmou sua solicitação. Os usuários têm 2 maneiras de confirmar: visitando o URL mencionado no e-mail enviado ao usuário ou copiando o token do e-mail e colando-o no formulário no URL fornecido. O token é válido por 24 horas.
  - *Confirmado* o usuário confirmou sua solicitação.
  - *Concluído* um Superusuário completou a solicitação.
- **\# de solicitações** Exibe o número de solicitações para cada tipo. Este bloco também exibe o número total de solicitações e o número de solicitações ativas.

## Dicas

- Selecione um Tipo de Solicitação para ver a lista de solicitações desse tipo.

*Traduzido por openai.com*

