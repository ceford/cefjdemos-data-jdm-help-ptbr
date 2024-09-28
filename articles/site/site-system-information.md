<!-- Filename: Help4.x:Site_System_Information  / Display title: Informações do Sistema -->

## Descrição

A página de *Informações do Sistema* fornece informações sobre o ambiente do servidor host. Existem cinco diferentes painéis de guias: Informações do Sistema, Configurações do PHP, Arquivo de Configuração, Permissões de Pastas e Informações do PHP. Cada painel fornece informações detalhadas sobre aquele aspecto do site. É útil ao resolver problemas de configuração.

- Observe que nenhuma dessas configurações pode ser alterada a partir desses painéis.
  Isso deve ser feito em diferentes locais ao longo da instalação do Joomla!,
  dependendo da configuração específica.
- Algumas configurações podem ser alteradas a partir da página de Configuração Global. Outras
  dependem da configuração do servidor host e não podem ser alteradas de dentro
  do Joomla!.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como acessar

- Selecione **Sistema → Painel de Informações → Informações do Sistema**
  no menu do Administrador.

## Captura de Tela

![painel inicial](../../../ptbr/images/site/system-information-tab.png)

## Guias de Formulário

### Guia de Informações do Sistema

- **PHP Built on** Fornece detalhes do sistema operacional principal
  no qual o servidor web que executa o Joomla está rodando.
- **Database Type** Fornece o tipo de banco de dados que está sendo usado
  pela instalação do Joomla.
- **Database Version** Fornece a versão atual do banco de dados MySQL
  que está sendo usado pela instalação do Joomla.
- **Database Collation** Como o banco de dados MySQL está estruturado para
  as informações usadas pelo Joomla!.
- **Database Connection Collation** O conjunto de caracteres e a collation do
  banco de dados.
- **PHP Version** Fornece a versão atual do script servidor PHP
  que está sendo usada para esta instalação do Joomla.
- **Web Server** Fornece o tipo e a versão atuais do servidor web
  no qual a instalação do Joomla! está rodando.
- **Web Server to PHP Interface** O script que permite a interação
  entre o servidor web (na maioria dos casos, Apache) e a linguagem de script
  PHP.
- **Joomla! Version** Fornece a versão atual do Joomla!. Recomenda-se
  que esteja sempre atualizada e utilizando a versão estável mais recente.
- **User Agent** O resumo do sistema operacional local da máquina do usuário
  atual e das informações do navegador, usado para criar um ID de sessão único
  para acesso e funcionalidade dentro do site Joomla!.

### Guia de Configurações PHP

![home dashboard](../../../ptbr/images/site/php-settings-tab.png)

Esta tela mostra as informações de Configurações PHP. Se alguma dessas
configurações estiver destacada como incorreta, elas devem ser corrigidas.

- **Safe Mode** Configuração recomendada: OFF
- **Open basedir** Configuração recomendada: Dependente do site
- **Display Errors** Configuração recomendada: OFF
- **Short Open Tags** Configuração recomendada: ON
- **File Uploads** Configuração recomendada: ON
- **Magic Quotes** Configuração recomendada: OFF
- **Register Globals** Configuração recomendada: OFF
- **Output Buffering** Configuração recomendada: OFF
- **Session Save Path** Configuração recomendada: Dependente do site
- **Session Auto Start** Configuração recomendada: 0
- **XML Enabled** Configuração recomendada: SIM
- **Zlib Enabled** Configuração recomendada: SIM
- **Native ZIP Enabled** Configuração recomendada: SIM
- **Disabled Functions** Configuração recomendada: Dependente do site
- **Multibyte String (mbstring) Enabled** Configuração recomendada: SIM
- **Iconv Available** Configuração recomendada: SIM
- **Maximum Input Variables** Configuração recomendada: 2500

### Guia de Arquivo de Configuração

![home dashboard](../../../ptbr/images/site/configuration-file-tab.png)

Esta guia mostra o conteúdo do arquivo *configuration.php* atual do Joomla!,
que está armazenado no diretório `path-to-joomla-root`. Este arquivo é criado automaticamente
quando você instala o Joomla pela primeira vez e é onde a maioria das mudanças
na seção de Configuração Global do Joomla são registradas. Observe
que nenhuma das configurações pode ser alterada a partir desta página. Use a Configuração Global
para ver mais informações sobre essas configurações e fazer alterações.

### Guia de Permissões de Pastas

![home dashboard](../../../ptbr/images/site/folder-permissions-tab.png)

Esta guia mostra uma lista dos diretórios aos quais o servidor web deve
ter acesso de gravação. Observe que todos os diretórios listados nesta
página devem estar como **Gravável**. Caso contrário, você pode precisar alterar
as permissões para poder instalar e usar o Joomla! com sucesso. O
arquivo configuration.php está incluído e mostrado como **Não Gravável**.

### Guia de Informações do PHP

![home dashboard](../../../ptbr/images/site/php-information-tab.png)

Esta guia exibe as configurações de configuração da linguagem de script
do lado do servidor PHP que o Joomla! utiliza, juntamente com todas as
informações do sistema associadas que contribuem para a criação do servidor web.
É a saída de um script php.info integrado ao Joomla!.

O PHP está instalado e executa-se no servidor (daí o lado do servidor mencionado acima),
e, portanto, todas as configurações são feitas no servidor. O visitante do
site não precisa ter nada especial rodando em sua máquina
local para visualizar ou usar qualquer funcionalidade extra que o PHP proporciona ao site.

Todas as configurações que são provavelmente necessárias estão exibidas aqui.
Qualquer alteração necessária deve ser feita dentro do arquivo *php.ini* e
outros arquivos de configuração no servidor web.

Quanto controle um proprietário de site tem sobre essas informações depende
de possuir o servidor ou se o host do servidor é flexível em sua
abordagem ao cliente.

É uma boa prática conhecer as limitações de uma determinada instalação
do servidor. A saída dessa tela é usada para encontrar informações detalhadas
sobre como o PHP é implementado no servidor.

Para obter detalhes completos sobre as informações contidas na guia Info do PHP,
visite: [http://php.net/phpinfo](http://php.net/phpinfo).

## Dicas

- Se você estiver tendo problemas para instalar extensões, enviar arquivos ou alterar opções de configuração, verifique a aba Permissões de Diretório para garantir que você tenha permissão para escrever nos arquivos do seu servidor web. O *Status* dos diretórios deve ser *Gravável*. Caso contrário, você pode não conseguir enviar ou editar arquivos nesses diretórios.
- Quando você estiver procurando ajuda com problemas de configuração, por exemplo, em um fórum da web do Joomla!, é muito útil postar informações específicas sobre sua instalação do Joomla!. Esta página é uma maneira fácil de encontrar todas essas informações em um só lugar. Melhor ainda - use o **Assistente de Postagens do Fórum** documentado no topo das páginas individuais do Fórum Joomla, como o fórum de [Perguntas Gerais](https://forum.joomla.org/viewforum.php?f=834).

*Traduzido por openai.com*

