<!-- Filename: Help4.x:Smart_Search:_Indexed_Content  / Display title: Busca Inteligente: Conteúdo Indexado -->

## Descrição

A página *Busca Inteligente: Conteúdo Indexado* mostra uma lista de todos os itens de conteúdo que foram indexados na Busca Inteligente.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos das Colunas da Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens da Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Se você é novo na Busca Inteligente, deve ler o 
  [Guia de Início Rápido da Busca Inteligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Como acessar

- Selecione **Componentes → Pesquisa Inteligente → Índice** no menu do Administrador.

## Captura de Tela

![busca inteligente conteúdo indexado](../../../ptbr/imagens/busca-inteligente/busca-inteligente-conteudo-indexado.png)

## Criar um Índice

Selecione o botão **Índice** na Barra de Ferramentas. Isso abrirá uma janela para mostrar o progresso da operação de indexação. A operação de indexação pode levar algum tempo, dependendo do número de itens de conteúdo do site e do número de palavras e frases de pesquisa contidas em cada item de conteúdo. Uma barra de progresso indicará quanto do processo de indexação já foi concluído. Não feche esta janela até que a indexação tenha sido completada. Em sites com uma grande quantidade de conteúdo, isso pode demorar muito tempo (dezenas de minutos).

Você deve rodar o indexador após novos conteúdos serem introduzidos no site que a função de Pesquisa Inteligente não identifique automaticamente. Por exemplo, ao importar novos conteúdos em lote, onde o importador não dispare automaticamente a Pesquisa Inteligente para indexar cada novo item de conteúdo. NOTA: O indexador da Pesquisa Inteligente também pode ser executado a partir da interface de linha de comando (CLI) se necessário. Consulte Configuração de indexação automática da Pesquisa Inteligente.

## Barra de Ferramentas

- **Indexar** Executa o indexador de Pesquisa Inteligente. Uma pequena janela pop-up aparecerá com uma barra de progresso que avança conforme o processo de indexação trabalha no conteúdo do site.
- **Ações** Selecione uma caixa de seleção para ativar a lista suspensa.
  - **Publicar** Torna os itens selecionados disponíveis para os visitantes do site.
  - **Despublicar** Torna os itens selecionados indisponíveis para os visitantes do site.
- **Excluir** Exclui os itens de conteúdo selecionados. Funciona com um ou vários itens de conteúdo selecionados. Excluir um item de conteúdo da Pesquisa Inteligente apenas o remove do índice e não afeta o item de conteúdo em si.
- **Manutenção**
  - **Otimizar**
  - **Limpar Índice** Limpa o índice da Pesquisa Inteligente esvaziando todas as tabelas de índice. Para continuar usando a Pesquisa Inteligente, selecione o botão Indexar na Barra de Ferramentas após a limpeza. AVISO: Limpar o índice também esvazia os filtros de conteúdo. Eles devem ser reintroduzidos manualmente após um ciclo de Limpeza-Índice.
- **Estatísticas** Mostra algumas estatísticas básicas sobre a Pesquisa Inteligente.

## Dicas

- Se você executar o indexador e obter um erro de *undefined null*, verifique
  as permissões no diretório `/logs` do Joomla. O servidor web precisa
  ter permissão de escrita nesse diretório para que o indexador funcione.
- Se a lista estiver vazia, certifique-se de que o plug-in Smart Search
  esteja habilitado.

*Traduzido por openai.com*

