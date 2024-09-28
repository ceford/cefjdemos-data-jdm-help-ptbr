<!-- Filename: Help4.x:Extensions:_Discover  / Display title: Extensões: Descobrir -->

## Descrição

Esta página permite que você descubra extensões que não passaram pelo
processo normal de instalação. Por exemplo, algumas extensões são muito grandes
em tamanho de arquivo para serem carregadas usando a interface web devido a limitações do
ambiente de hospedagem web. Usando este recurso, você pode fazer o upload dos arquivos de extensão diretamente
para o seu servidor web usando outros meios, como FTP ou SFTP, e colocar esses
arquivos de extensão no diretório apropriado. Você pode então usar a
funcionalidade de descoberta para encontrar a extensão recém-carregada e ativá-la na
sua instalação Joomla!. Usando a operação de descoberta, você também pode
descobrir e instalar várias extensões ao mesmo tempo. Uma extensão
pode ser instalada com a função de descoberta seguindo os seguintes passos:

1. Carregue os arquivos descompactados da extensão para o diretório apropriado
    na sua instalação Joomla!. Por exemplo, se você quiser carregar uma
    extensão de template de site na sua instalação Joomla!, você deverá
    criar um diretório para a extensão de template no subdiretório /templates
    da sua instalação Joomla!. Em seguida, você deve carregar
    os arquivos da extensão de template nesse diretório.
2. Depois de carregar os arquivos da extensão, volte para a página
    Gerenciador de Extensões Descobrir e selecione o botão **Descobrir**
    na barra de ferramentas. Isso iniciará a função de busca que
    procurará nos diretórios de extensões do Joomla! por extensões não instaladas.
3. Se a extensão carregada for compatível com a sua versão do Joomla! e
    ainda não estiver instalada, ela aparecerá na listagem de
    extensões descobertas nesta página.
4. Marque a caixa de seleção à esquerda da extensão descoberta e depois
    selecione o botão **Instalar** na barra de ferramentas. Isso instalará a
    extensão na sua instalação Joomla!.

### Elementos Comuns

Alguns elementos desta página estão cobertos em artigos de
Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens de Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como Acessar

- Selecione **Sistema → Instalar Painel → Discover** no menu do Administrador.

## Captura de Tela

![Lista de extensões descobertas](../../../ptbr/images/extensions/discover-list.png)

## Cabeçalhos de Coluna

- **Nome** O nome da extensão.
- **Localização** Indica se é uma extensão do site ou do administrador.
- **Tipo** O tipo de extensão – Módulo, Plugin, Template, Idioma.
- **Versão** O número da versão da extensão.
- **Data** A data de lançamento da extensão.
- **Autor** O autor da extensão.
- **Diretório** Se a extensão for um plugin, isso mostra o subdiretório dentro do diretório /plugins da instalação do Joomla!, onde a extensão está localizada. Por padrão, o Joomla! tem os seguintes subdiretórios no diretório de Plugins, cada um representando diferentes tipos de plugins definidos: authentication, content, editors, editors-xtd, extension, search, system, user.
- **ID** O número de ID. Um número de identificação atribuído exclusivamente para esta entrada. Ele é automaticamente atribuído pelo Joomla! e é usado para a identificação interna da entrada. O número não pode ser alterado.

## Dicas

- Se você tiver muitas extensões que deseja instalar, pode fazer o upload de todas
  elas nos diretórios apropriados da sua instalação do Joomla! e, em seguida, usar
  esta tela para descobrir todas elas em uma única operação. Você pode então instalar
  todas as extensões de uma vez, selecionando todas elas e clicando no botão **Instalar**
  na barra de ferramentas.

*Traduzido por openai.com*

