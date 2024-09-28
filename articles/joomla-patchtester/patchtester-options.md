<!-- Filename: Help4.x:Components_Patch_Tester_Options  / Display title: Opções do Testador de Patches -->

## Descrição

O *Joomla! Patch Tester* é usado por Testadores para verificar se patches de código
produzidos por Desenvolvedores realmente fazem o que deveriam fazer sem
efeitos colaterais indesejados. A página de *Opções* é usada para configurar a conexão com o Github.

### Elementos Comuns

Alguns elementos desta página são cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

Mais Informações: [Um Guia para Iniciantes sobre Teste de Bugs no Joomla](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Como Acessar

- Selecione **Componentes → Patch Tester** no menu do Administrador.
  - Selecione o botão *Opções* na Barra de Ferramentas.

## Captura de Tela

![Formulário de Opções do Patchtester](../../../ptbr/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Campos de Formulário

### Aba Repositório GitHub

- **Repositório GitHub** O padrão é `Joomla! CMS`. Use-o.

### Aba Autenticação no GitHub

Você precisa de uma conta no GitHub e de um Token do GitHub. Tudo gratuito - veja a aba de Autenticação no GitHub para detalhes.

![Opções do Patchtester aba de autenticação no github](../../../ptbr/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **Método de Autenticação do GitHub** Escolha o método Token. O método Credenciais não funcionará a partir de setembro de 2020.
- **Token do GitHub** Cole o Token obtido no GitHub.

### Aba Configurações do Servidor CI

Essas configurações são usadas para testes automatizados. Use os padrões para testes manuais.

![Opções do Patchtester aba de configurações do servidor ci do github](../../../ptbr/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **Endereço do Servidor CI** Padrão: `https://ci.joomla.org`
- **Alternar Integração CI** Padrão: Desligado


*Traduzido por openai.com*

