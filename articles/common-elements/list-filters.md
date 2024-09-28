<!-- Filename: Help6.x:List_Filters  / Display title: Filtros de Listas -->

## Propósito¶

A maioria dos componentes possui visualizações de lista que exibem itens do banco de dados. Pode haver centenas de itens, talvez milhares, ou até milhões. Portanto, os Filtros de Lista são usados para reduzir a lista exibida para aqueles que provavelmente contêm o item no qual você precisa trabalhar.

Por exemplo, itens descartados geralmente não são exibidos por padrão. Se você quiser ver seus itens descartados, precisará definir o filtro **- Selecionar Status -** para **Descartado**. A captura de tela a seguir mostra os Filtros da página de Artigos.

## Opções de Filtro da Lista de Artigos¶

![Lista de artigos](../../../ptbr/images/common-elements/articles-list-filter-options.png)

Para **exibir** ou **ocultar** as Opções, selecione o botão **Opções de Filtro**. Note que as Opções são sempre exibidas ao retornar a qualquer página em que uma Opção tenha sido selecionada.

O número de Opções exibidas varia com o componente. Até mesmo o componente de Conteúdo, que exibe a lista de Artigos, pode ter filtros adicionais. Por exemplo, um filtro **- Selecionar Estágio -** é exibido se o componente de Conteúdo tiver **Fluxos de Trabalho** habilitados.

## A Barra de Pesquisa

### Pesquisa por Texto

*Passe o cursor* ou *selecione* o campo de *Pesquisa* para ver uma *Dica de Ferramenta* ou ouvir um equivalente *Áudio* indicando quais campos serão pesquisados. O comportamento padrão é pesquisar o texto inserido dentro do texto do título.

O componente de conteúdo permite um prefixo para pesquisar dentro do ID, Autor ou Conteúdo. Cada um desses termos precisa de dois pontos, mas pode estar em qualquer *Caixa*. Por exemplo, *ID:19* ou *Autor:João* ou *conteúdo:lorem ipsum*.

Para realizar uma pesquisa, insira parte do termo de pesquisa e selecione o ícone **Pesquisar** (<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Opções de Filtro e Limpar

O botão **Opções de Filtro** é usado para alternar a visualização dos vários filtros. Se não houver Filtros para um componente, esse botão estará ausente.

O botão **Limpar** é usado para limpar todos os filtros e restaurar a lista ao seu estado não filtrado. Se não houver filtros para um componente, esse botão estará ausente.

### Ordem dos Resultados

A ordem em que os resultados são apresentados é selecionável pelo usuário. Para artigos, a ordem padrão é *ID Decrescente*, o que coloca os artigos mais recentes no topo da lista. Mas você pode desejar pesquisar artigos por mais acessos, *Acessos decrescente*, ou artigos que em breve desaparecerão, *Fim da Publicação ascendente*.

A ordem dos resultados pode ser alterada selecionando um ícone de ordem nos cabeçalhos das colunas da lista. O ícone padrão *ID Decrescente* é representado por um caractere de seta para baixo (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>). Ele muda para uma seta para cima se a ordem de classificação for invertida, *ID Ascendente*.

### Número de Resultados

O número de resultados em uma lista é definido na página de Configuração Global, aba Site, campo Limite Padrão da Lista. O valor padrão para uma nova instalação é 20.

Há ocasiões em que isso não é conveniente. Você pode desejar ver *50* ou *100*. Tenha cuidado ao escolher *Todos*. Pode levar um longo tempo para recuperar os resultados e renderizar a página. O servidor pode ficar sem memória ou tempo e acionar um erro fatal. E seu navegador pode demorar muito para exibir a página.

O valor padrão para este conjunto de documentação foi definido para 5 porque isso é suficiente para capturas de tela ilustrativas.

## Como Usar Filtros

O propósito de cada filtro deve ser evidente a partir de seu rótulo de seletor não filtrado. Por exemplo, o filtro de Artigos **- Selecionar Status -** oferece cinco opções: *Excluído*, *Não Publicado*, *Publicado*, *Arquivado* e *Todos*. A última é funcionalmente equivalente ao não filtrado (*- Selecionar Status -*).

Quando uma opção de filtro é alterada, a página recarrega automaticamente com os novos resultados filtrados pela nova opção de filtro.

## Ocultar Colunas

Algumas listas de componentes têm muitas colunas e podem ser largas demais para a sua tela. Isso é especialmente verdadeiro em algumas traduções do texto dos cabeçalhos de coluna. O resultado mais irritante é que os Títulos podem quebrar e ser difíceis de ler.

Para liberar mais espaço para o Título, você pode abrir a lista suspensa de Colunas e selecionar colunas menos importantes para ocultar. Em seguida, feche a lista de Colunas novamente. O efeito é imediato, pois usa JavaScript para ocultar as colunas selecionadas no layout. Elas ainda estão presentes na página.

Suas configurações são salvas pelo seu navegador, então serão usadas até que você as altere novamente, mesmo que você saia e entre novamente.

*Traduzido por openai.com*

