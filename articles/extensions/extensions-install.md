<!-- Filename: Help4.x:Extensions:_Install  / Display title: Extensões: Instalar -->

## Descrição

Extensões são usadas para adicionar capacidades ao Joomla! que não existem na instalação padrão. Centenas de extensões estão disponíveis para Joomla!, com mais sendo desenvolvidas o tempo todo.

As extensões são categorizadas em cinco tipos, conforme segue:

- Um *Componente* é uma mini-aplicação que renderiza o corpo principal da
  página. Exemplos de Componentes são Contatos, a Página Inicial e Feeds
  de Notícias.
- Um *Módulo* é uma Extensão menor tipicamente usada para renderizar um pequeno
  elemento que é exibido em várias páginas. Exemplos de Módulos
  incluem Menus e Itens Relacionados.
- Um *Plugin* é uma seção de código que é executada quando um evento
  pré-definido acontece dentro do Joomla!. Por exemplo, editores são Plugins que rodam quando
  uma sessão de edição é aberta.
- A Extensão de *Idioma* permite que o Front-end e o Back-end do
  Joomla! sejam apresentados em qualquer idioma para o qual exista uma Extensão de Idioma. Desta forma, o Joomla! pode ser lançado em um novo idioma sem mudanças no programa central.
- Um *Template* controla a maneira como o conteúdo de um site é exibido,
  incluindo a localização e o layout dos elementos, cores, fontes, e assim
  por diante. Templates permitem que a aparência do site seja separada
  do seu conteúdo.

### Elementos Comuns

Alguns elementos desta página são cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como Acessar

- Selecione **Sistema → Instalar Painel → Extensões** no menu do
  Administrador.

Existem quatro métodos de instalação disponíveis. Se **Instalar da Web** foi
colocado primeiro na lista ou foi o último método selecionado, haverá um
pequeno atraso enquanto o Joomla baixa uma seleção inicial de dados da Extensão
do Diretório de Extensões do Joomla.

A ordem normal das Abas para os métodos de instalação é a seguinte:

* Carregar Arquivo de Pacote
* Instalar a Partir de uma Pasta
* Instalar a Partir de um URL
* Instalar da Web

Apenas um método é necessário para instalar uma dada Extensão. O procedimento
normal para instalar uma Extensão Joomla! é o seguinte:

1.  Baixe um ou mais arquivos de arquivo (normalmente no formato ".zip"
    ou "tar.gz") do site do provedor da Extensão para um diretório local
    no seu computador. Observe que algumas Extensões são instaladas como
    um único arquivo (por exemplo, um Componente ou Módulo) enquanto outras
    Extensões podem ter dois ou mais arquivos (por exemplo, um Componente
    e um Módulo). Se houver duas ou mais partes, cada uma pode ter seu
    próprio arquivo de arquivo. Ou as partes podem ser combinadas em um
    arquivo de pacote.
2.  Escolha um dos métodos descritos para instalar a extensão.
3.  Quando terminar, a tela exibirá uma mensagem de **Sucesso** ou **Falha**.
4.  Dependendo da Extensão, pode ser necessário habilitar a
    Extensão (por exemplo, nas listas de Módulos ou Plugins).

## Guia de Envio de Arquivo do Pacote

![Aba de envio de arquivo do pacote de instalação da extensão](../../../ptbr/images/extensions/install-upload-package-file.png)

- Arraste e solte ou navegue até o local onde você baixou o arquivo de
  arquivo da extensão.

O envio começa automaticamente. Note o **Tamanho máximo de envio: 32.00MB**
definido para sua instalação. Se você não puder aumentar esse valor, pode usar
*Instalar a partir da Pasta*.

## Instalar a partir da Aba de Pasta

![Instalação da extensão a partir da aba de pasta](../../../ptbr/images/extensions/install-from-folder.png)

1. Crie um diretório temporário no seu disco rígido local e descompacte o arquivo de arquivo da Extensão neste diretório temporário.
2. Usando FTP, faça o upload do conteúdo deste diretório (incluindo arquivos e subdiretórios) para um diretório no seu servidor.
3. No campo *Instalar Diretório*, especifique o diretório do servidor onde você fez o upload dos arquivos e subdiretórios do pacote.
4. Clique no botão *Verificar e Instalar* e o Joomla! irá instalar o conteúdo do diretório fornecido.

Observe que é uma prática comum colocar a pasta contendo sua extensão descompactada na pasta tmp do seu site Joomla.

## Instalar da Guia URL

![Instalar extensão da guia url](../../../ptbr/imagens/extensoes/instalar-da-url.png)

Em vez de baixar o arquivo do pacote para o seu computador local, basta
especificar o URL do arquivo do pacote desejado. Em seguida, clique no botão "Verificar e Instalar" e o Joomla! o instalará automaticamente diretamente desse URL. *Observe que, com este método, você não terá uma cópia do arquivo do pacote no seu computador local.*

## Instalar a partir da guia Web

Para instalar uma extensão diretamente do Diretório de Extensões do Joomla (JED). Você pode selecionar extensões para listar por Categoria ou pode pesquisar por nome parcial.

![Instalação da extensão a partir da guia web](../../../ptbr/images/extensions/install-from-web.png)

## Dicas

- Quatro métodos alternativos de instalação estão disponíveis, conforme indicado acima. O mais comum é o método "Enviar Arquivo de Pacote".
- Se você deseja instalar um módulo ou plugin de terceiros que pertence a um componente, geralmente será necessário instalar o componente, bem como o módulo ou plugin, para poder utilizá-los. Isso normalmente está documentado nas instruções de instalação da extensão no site do autor.
- Da mesma forma, se você desinstalar um componente de terceiros que também tenha seus próprios módulos ou plugins, esses módulos e plugins não poderão mais ser usados. Portanto, é normalmente recomendado desinstalar esses módulos e plugins dependentes também.
- Alguns componentes desenvolvidos por desenvolvedores terceiros podem incluir seus próprios módulos ou plugins no instalador. Nesse caso, certifique-se de que esses diretórios de módulos ou plugins sejam graváveis. Caso contrário, a extensão não funcionará corretamente.
- **AVISO DE SEGURANÇA:** Recomenda-se que você use apenas as extensões de terceiros no seu site que realmente precisa. Não use seu site ao vivo para fins de teste porque isso pode comprometer seu site e servidor. Teste novas extensões em um site de teste local antes de implantá-las em seu site ao vivo.
- Não instale extensões do Joomla! baixadas de sites [Warez](https://en.wikipedia.org/wiki/Warez) porque podem estar infectadas com vírus ou malware que causam danos ao servidor e podem contaminar o computador dos seus visitantes!
- Instalar de uma URL remota pode ser perigoso. Por essa razão, é geralmente recomendado que você utilize as opções "Instalar da Web", "Enviar Arquivo de Pacote" ou "Instalar da Pasta" ao instalar novas extensões.

*Traduzido por openai.com*

