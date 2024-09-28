<!-- Filename: Help4.x:Site_Global_Configuration  / Display title: Configuração Global -->

## Descrição

A tela de Configuração Global permite configurar o site Joomla com suas configurações pessoais. As configurações feitas nesta tela se aplicam a todo o site.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como acessar

- Selecione **Painel do Sistema → Configuração Global** no Painel Inicial. Ou...
- Selecione **Sistema → Painel de Configuração → Configuração Global** no
menu do Administrador.

## Captura de Tela

![guia de configuração global do site](../../../ptbr/images/site/global-configuration-site-tab.png)

## Campos de Formulário

### Aba Site

#### Painel do Site

- **Nome do Site** Insira o nome do site. Este será utilizado em
  várias localizações (por exemplo, na barra de título do navegador do Backend e em páginas Offline do Site).
- **Site Offline** Selecione se o acesso ao Frontend está disponível.
- **Mensagem Offline**
    - *Ocultar*
    - *Usar Mensagem Personalizada* A mensagem usa o valor definido no campo *Mensagem Personalizada*.
    - *Usar Mensagem Padrão do Idioma do Site* A mensagem usa o valor
      definido no arquivo ini do idioma do site.
- **Imagem Offline** Selecione uma imagem para ser exibida na página offline. Garanta que a imagem tenha menos de 400px de largura.
- **Edição no Frontend** Selecione a edição para módulos e itens do menu.
- **Editor Padrão** Selecione o editor de texto padrão. Usuários registrados poderão alterar sua preferência em seus dados pessoais.
- **Captcha Padrão** Selecione o captcha padrão para o seu site. Talvez você precise inserir as informações necessárias no plugin captcha.
- **Nível de Acesso Padrão** Selecione o nível de acesso padrão para novos itens.
- **Limite de Lista Padrão** Define o comprimento padrão das listas no Backend para todos os usuários.
- **Limite de Feed Padrão** Selecione o número de itens de conteúdo a serem exibidos nos feeds.
- **Endereço de Email do Feed** Os feeds de notícias RSS e Atom incluem o endereço de email do autor.
  - *Email do Autor* Inclui o email do autor do artigo do Perfil do Usuário no feed de notícias.
  - *Email do Site* Inclui o endereço de email *De* do site para cada artigo.

#### Painel de Metadados

- **Descrição Meta do Site** Insira uma descrição geral do site que será utilizada pelos motores de busca.
- **Robôs** Instruções para robôs.
  - *indexar, seguir* Indexar esta página e seguir os links nesta página.
  - *não indexar, seguir* Não indexar esta página, mas ainda assim seguir os links na página. Por exemplo, você pode fazer isso para uma página de mapa do site onde deseja que os links sejam indexados, mas não quer que esta página apareça nos motores de busca.
  - *indexar, não seguir* Indexar esta página, mas não seguir nenhum link na página. Por exemplo, você pode querer fazer isso para um calendário de eventos, onde deseja que a página apareça nos motores de busca, mas não deseja indexar cada evento.
  - *não indexar, não seguir* Não indexar esta página ou seguir qualquer link na página.
- **Direitos de Conteúdo** Descreva quais direitos outros têm para usar este conteúdo. Isso é transmitido aos motores de busca usando a meta tag `rights` no cabeçalho HTML.
- **Meta Tag do Autor** Mostrar a meta tag do autor ao visualizar artigos.
- **Versão do Joomla** Controla se a meta tag `generator` no cabeçalho do documento HTML no Frontend e nos feeds Atom inclui a versão exata do site Joomla. É recomendável ocultá-la por questões de segurança.

#### Painel SEO

- **URLs Amigáveis para Motores de Busca** Selecione se os URLs são otimizados para Motores de Busca.
- **Usar Reescrita de URL**
  - *Apache e Litespeed* Renomear `htaccess.txt` para `.htaccess`.
  - *IIS* Renomear `web.config.txt` para `web.config`.
  - *NginX* você deve configurar seu servidor.
  - *Outro* Se estiver em dúvida, consulte sua empresa de hospedagem.
- **Adicionar Sufixo ao URL** Se sim, o sistema adicionará um sufixo ao URL com base no tipo de documento.
- **Apelidos Unicode** Escolha entre transliteração e apelidos unicode. Transliteração é o padrão.
- **Nome do Site nos Títulos das Páginas** Começar ou terminar todos os Títulos de Página com o nome do site (por exemplo, *Meu Nome de Site - Meu Nome de Artigo*).

#### Painel de Cookies

- **Domínio do Cookie** Domínio a ser usado ao definir cookies de sessão. Preceda o domínio com '.' se o cookie deve ser válido para todos os subdomínios.
- **Caminho do Cookie** Caminho para o qual o cookie deve ser válido.

### Aba Sistema

![aba de configuração global do sistema](../../../ptbr/images/site/global-configuration-system-tab.png)

#### Painel de Depuração

- **Sistema de Depuração** Se ativado, informações de diagnóstico, tradução de idioma e erros de SQL (se houver) serão exibidos. As informações serão exibidas no rodapé de todas as páginas que você visualizar dentro do Backend e Frontend do Joomla. Não é aconselhável deixar o modo de depuração ativado ao executar um site ao vivo.
- **Idioma de Depuração** Ative para ver os indicadores de depuração `**...**` ou `??...??` na saída da página onde os arquivos de idioma do Joomla são usados para traduzir chaves de string para seus valores traduzidos. O primeiro formato indica que a string foi traduzida com sucesso. O segundo indica que o texto foi inserido em linguagem natural e não pode ser traduzido.
  - **Exibição do Idioma** Selecione se você deve exibir a constante de idioma ou o valor do idioma ao depurar as strings do idioma.

#### Painel de Cache

- **Cache do Sistema** Ative o cache e defina o nível de cache.
  - *Nível Conservador* cache do sistema menor.
  - *Nível Progressivo* sistema de cache mais rápido e maior, inclui cache de renderizadores de módulo. Não é apropriado para sites extremamente grandes.
  - **Manipulador de Cache**
    - *Arquivo* O mecanismo de cache nativo é baseado em arquivos. Certifique-se de que as pastas de cache são graváveis.
  - **Cache Específico para Plataforma** Habilite quando a saída HTML em dispositivos móveis diferir de outros dispositivos.
  - **Tempo de Cache (minutos)** O comprimento máximo de tempo em minutos para um arquivo de cache ser armazenado antes de ser atualizado.
  - **Caminho para a Pasta de Cache** Especifique uma pasta gravável para armazenar arquivos de cache se você não deseja usar a pasta padrão.

#### Painel de Sessão

- **Manipulador de Sessão** O mecanismo pelo qual o Joomla identifica um usuário uma vez que ele está conectado ao site usando cookies não persistentes.
  - *Banco de Dados* O manipulador de sessão de banco de dados é o manipulador padrão porque é o único que o Joomla pode configurar e controlar totalmente por conta própria.
  - *Sistema de Arquivos* O manipulador de sistema de arquivos será ligeiramente mais eficiente que o manipulador de banco de dados, mas requer que o PHP esteja configurado corretamente, caso contrário, ele travará e o Joomla se tornará totalmente inutilizável.
    - *Caminho para Salvar a Sessão* Insira o caminho completo do sistema de arquivos. Certifique-se de que o caminho tenha permissões apropriadas para o PHP ler e gravar arquivos, e se `coleta de lixo de sessão` estiver habilitada para excluir arquivos. Se este caminho não for definido, o Joomla dependerá da configuração PHP `session.save_path INI` ou recorrerá ao diretório temporário do sistema (conforme definido pela função PHP sys_get_temp_dir()). Se nenhum desses caminhos estiver configurado ou as permissões estiverem erradas, então é game over. Para recuperar, edite o arquivo configuration.php e defina `$session_handler = 'database'`.
  - *Outros manipuladores* APCu, Memcached, Redis e WinCache dependem de extensões PHP opcionais e podem estar disponíveis se o seu sistema os suportar. APCu ou WinCache podem não ser melhores do que a opção de sistema de arquivos *puro*. Os manipuladores Memcached e Redis são exagerados para o Joomla em um ambiente típico de hospedagem compartilhada. Esses tipos de manipuladores são bem-sucedidos se você estiver implantando o Joomla em um ambiente de balanceamento de carga onde múltiplos servidores estão envolvidos e você precisa que os dados da sessão da aplicação estejam disponíveis em todos os servidores.
- **Tempo de Vida da Sessão (minutos)** Logout automático de um usuário após ele ter ficado inativo pelo número de minutos informado. Não configure um valor muito alto.
- **Sessões Compartilhadas** Quando ativado, a sessão de um usuário é compartilhada entre as seções Frontend e Backend do site. Observe que alterar este valor invalidará todas as sessões existentes no site. Isso não está disponível quando a opção [Forçar HTTPS](#forcehttps) está definida como *Somente Administrador*.
- **Rastrear Metadados de Sessão**
  - *Sim* Metadados adicionais sobre a sessão de um usuário (incluindo seu nome de usuário, ID de usuário e qual aplicação ele está conectado) serão registrados na tabela de banco de dados da sessão.
  - *Não* Recursos dependentes desses dados ficarão indisponíveis.

### Aba Servidor

![aba de configuração global do servidor](../../../ptbr/images/site/global-configuration-server-tab.png)

#### Painel do Servidor

- **Caminho para Pasta Temporária** Especifique uma pasta gravável para armazenar arquivos temporários.
- **Compressão de Página Gzip**
  - *Sim* Comprimir automaticamente as páginas HTML geradas com Gzip, tornando-as menores e aumentando a pontuação de velocidade do seu site.
  - *Não* Se seu servidor já estiver fazendo isso por você ou se entrar em conflito com extensões de terceiros.
- **Relatório de Erros** Este parâmetro define o nível de relatório de erros a ser usado pelo PHP no site Joomla.
  - *Padrão do Sistema* Deixa o nível de relatório de erros configurado no servidor.
  - *Nenhum* Desativa o relatório de erros.
  - *Simples* Substitui a configuração do servidor para fornecer um nível básico de relatório.
  - *Máximo* Substitui a configuração do servidor para permitir o relatório de todos os erros. Caso seu site Joomla falhe a ponto de não ser possível usar a página do administrador para ativar o relatório de erros, você pode ativar o relatório de erros completo editando o arquivo `configuration.php`. Definir `$error_reporting = 'maximum'` é equivalente a definir *Relatório de Erros* para *Máximo*.
- **Forçar HTTPS** Força o acesso ao site nas áreas selecionadas a ocorrer apenas com HTTPS (conexões HTTP criptografadas com o prefixo de protocolo https://) e também força o uso de cookies seguros. Note, você deve ter o HTTPS ativado no seu servidor para utilizar esta opção.

#### Painel de Localização

- **Fuso Horário do Site** Escolha uma cidade na lista para configurar a data e a hora para exibição.

#### Painel de Serviços da Web

- **Habilitar CORS** Compartilhamento de Recursos entre Origem ou [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) permite que scripts executados em um navegador interajam com recursos de uma origem diferente.
  - **Access-Control-Allow-Origin** Especifica a origem permitida para acessar serviços da Web neste site, enviada de volta em resposta a um pedido pré-flight. Padrão: `*` (=todos).
  - **Access-Control-Allow-Headers** Especifica o(s) cabeçalho(s) enviado(s) de volta em resposta a um pedido pré-flight. Padrão: `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Especifica o(s) método(s) de serviço da Web permitido(s) para acessar neste site, enviado de volta em resposta a um pedido pré-flight. Padrão: todos os métodos disponíveis para a rota solicitada.

#### Painel de Proxy

- **Atrás de Balanceador de Carga** Se o seu site está atrás de um balanceador de carga ou proxy reverso, ative esta configuração para que os endereços IP e outras configurações dentro do Joomla sejam ajustados automaticamente.
- **Habilitar Proxy de Saída** Alguns hosts não permitem nenhum acesso de rede do seu site para o mundo exterior por padrão e requerem que você configure manualmente um proxy de saída.
  - **Host do Proxy de Saída** Nome do host (domínio) ou endereço IP.
  - **Porta do Proxy de Saída**
  - **Nome de Usuário do Proxy de Saída** Deixe em branco se seu proxy de saída não exigir autenticação.
  - **Senha do Proxy de Saída**

#### Painel de Banco de Dados

- **Tipo de Banco de Dados** O tipo de banco de dados em uso, selecionado durante o processo de instalação. Não edite este campo a menos que seja absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Host** O nome do host para o seu banco de dados inserido durante o processo de instalação. Não edite este campo a menos que seja absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Nome de Usuário do Banco** O nome de usuário para acesso ao seu banco de dados inserido durante o processo de instalação. Não edite este campo a menos que seja absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Senha do Banco** A senha a ser usada para acessar o banco de dados. Não edite este campo a menos que seja absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Nome do Banco de Dados** O nome do seu banco de dados inserido durante o processo de instalação. Não edite este campo a menos que seja absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Prefixo das Tabelas do Banco** O prefixo usado para suas tabelas de banco de dados, criado durante o processo de instalação. Não edite este campo a menos que seja absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Criptografia de Conexão**
  - Padrão (controlado pelo servidor)
  - Autenticação unidirecional
    - **Verificar Certificado do Servidor**
      - **Caminho para o Arquivo CA** Caminho do sistema de arquivos.
  - Autenticação bidirecional
    - **Caminho para o Arquivo de Chave Privada** Localização do sistema de arquivos.
    - **Caminho para o Arquivo de Certificado** Localização do sistema de arquivos.
    - **Verificar Certificado do Servidor**
      - **Caminho para o Arquivo CA** Caminho do sistema de arquivos.
    - **Conjunto de Cifras Suportado (opcional)** Nenhuma entrada necessária (somente recomendado para usuários experientes). Para mais detalhes, veja a documentação do seu banco de dados.

#### Painel de Mail

- **Enviar Mail**
  - *Sim* Ativar envio de email.
  - *Não* Desativar envio de email. Recomenda-se colocar o site offline ao desativar a função de email.
- **Desabilitar Mail em Massa**
  - *Sim* Desabilitar a função de Mail em Massa para Usuários.
  - *Não* Tornar a função de Mail em Massa para Usuários ativa.
- **Email do Remetente** O endereço de email que será usado para enviar emails do site.
- **Nome do Remetente** Texto exibido no cabeçalho *De:* ao enviar um email do site. Geralmente o nome do site.
- **Email de Resposta** O endereço de email que será usado para receber respostas dos usuários finais.
- **Nome de Resposta** Texto exibido no cabeçalho *Para:* quando os usuários finais responderem ao email recebido.
- **Mailer** Selecione qual mailer para a entrega dos emails do site.

### Aba de Log

![aba de configuração global de log](../../../ptbr/images/site/global-configuration-logging-tab.png)

#### Painel de Log

- **Caminho para a Pasta de Log** O Joomla pode opcionalmente manter um arquivo de log de suas próprias operações e de extensões de terceiros. Forneça o caminho absoluto para uma pasta que seja gravável pelo PHP; se estiver ausente ou não for gravável, o Joomla não carregará. Por razões de segurança, você não deve usar uma pasta com acesso geral, como `/tmp`.
- **Logar Quase Tudo** Loga tudo, exceto APIs obsoletos.
- **Logar APIs Obsoletos** Loga APIs obsoletos.

#### Painel de Log Personalizado

- **Prioridades de Log** Pode ser usado para gerenciar registros personalizados. Selecione os eventos que deseja ver no arquivo de log. O padrão é *Todos*. Os itens podem ser selecionados ou desmarcados clicando na lista suspensa.
- **Categorias de Log** Uma lista separada por vírgulas de categorias de log a incluir ou excluir. Categorias de log comuns incluem, mas não se limitam a: `database`, `databasequery`, `database-error`, `deprecated` e `jerror`. Se estiver vazio, o log personalizado será desativado.
- **Modo de Categoria de Log** Define o modo para a lista de categorias de log acima.

### Aba Filtros de Texto

![aba de configuração global de filtros de texto](../../../ptbr/images/site/global-configuration-text-filters-tab.png)

Essas configurações de filtro de texto serão aplicadas a todos os campos do editor de texto enviados pelos usuários nos grupos selecionados.

Essas opções de filtragem dão mais controle sobre o HTML que seus provedores de conteúdo enviam. Você pode ser tão rigoroso ou liberal quanto precisar para atender às necessidades do seu site. A filtragem é opcional e as configurações padrão fornecem boa proteção contra marcações comumente associadas a ataques na web.

## Dicas

- A maioria dessas configurações pode ser definida uma vez e depois deixada inalterada.
- Se for necessário fazer grandes modificações, considere tirar o site do ar para testá-lo e garantir que tudo está funcionando corretamente.
- As configurações são salvas no arquivo `configuration.php` na raiz do site. As permissões desse arquivo são configuradas como somente leitura (444) após fazer alterações na página de Configuração Global e devem ser dadas permissões de escrita ao proprietário (644) antes de editar com um editor de texto.

*Traduzido por openai.com*

