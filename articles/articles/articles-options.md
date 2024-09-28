<!-- Filename: Help4.x:Articles:_Options  / Display title: Artigos: Opções -->

## Descrição

A página *Artigos: Opções* é usada para definir valores padrão globais para artigos. Eles são utilizados quando *Usar Global* é selecionado para uma opção em um item de menu de Artigos. Por exemplo, para mostrar a *Data de Criação* de um artigo em seus itens de menu de Artigos, defina essa opção como *Mostrar* aqui para que seja o valor padrão.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

Selecione o botão **Opções** na Barra de Ferramentas de qualquer página da lista de *Artigos*.

## Captura de Tela

![Captura de tela das opções de artigos](../../../pt/images/articles/articles-options-articles-tab.png)

## Campos de Formulário

### Aba Artigos

Essas configurações se aplicam aos layouts de artigos, a menos que sejam alteradas para um item de menu ou artigo específico.

- **Escolher um Layout** Selecione o valor padrão para itens de menu de Artigo Único.
- **Título** Mostrar o Título do Artigo.
- **Títulos Vinculados** Mostrar o título como um link para o artigo.
- **Texto de Introdução**
  - **Mostrar** O Texto de Introdução do artigo será exibido no artigo completo.
  - **Ocultar** Apenas a parte do artigo após a quebra "Leia Mais" será exibida no artigo completo.
- **Posição das Informações do Artigo**
  - **Acima** Coloca o bloco de informações do artigo acima do texto.
  - **Abaixo** Coloca o bloco de informações do artigo abaixo do texto.
  - **Dividido** Divide o bloco de informações do artigo em 2 blocos separados. Um bloco está acima e o outro está abaixo do texto.
- **Título das Informações do Artigo** Exibe a palavra *Detalhes* no topo do bloco de informações do artigo.
- **Categoria** Mostrar o Título da Categoria do Artigo.
  - **Linkar Categoria** Mostrar o título como um link para essa Categoria. Nota: Isso pode ser configurado para um layout de blog ou de lista com a opção *Escolher um Layout* na aba Categoria.
- **Categoria Pai** Mostrar o Título da Categoria Pai do Artigo.
  - **Linkar Categoria Pai** Mostrar o título como um link para essa Categoria. Nota: Isso pode ser configurado para um layout de blog ou de lista com a opção *Escolher um Layout* na aba Categoria.
- **Associações** Mostrar as bandeiras associadas ou o Código do Idioma. Multilíngue apenas.
  - **Usar Bandeiras de Imagem** Exibir a escolha de idioma como bandeiras de imagem se Associações estiver definido como *Mostrar*.
- **Autor** Mostrar o autor do Artigo.
  - **Link para a Página de Contato do Autor** Mostrar como um link para um layout de Contato para aquele autor. Nota: O autor deve ser configurado como um Contato. Além disso, um link não será exibido se houver um valor de Pseudônimo do Autor para o contato.
- **Data de Criação** Mostrar a data de criação do Artigo.
- **Data de Modificação** Mostrar a data de modificação do Artigo.
- **Data de Publicação** Mostrar a data de início da publicação do Artigo.
- **Navegação** Mostrar um link de navegação *Anterior* ou *Próximo*.
- **Link "Leia Mais"** Mostrar o link Leia Mais para conectar a parte do artigo antes da quebra Leia Mais com o resto do Artigo.
- **Leia Mais com Título**
  - **Mostrar** O título do artigo faz parte do link Leia Mais. O link estará no formato "Leia Mais: \[título do artigo\]".
  - **Ocultar** O link será "Leia mais".
- **Limite de "Leia Mais" (caracteres)** O número máximo de caracteres do título a incluir. Nota: Isso pode impedir que o texto Leia Mais se torne excessivamente longo se o artigo tiver um título muito longo.
- **Tags** Mostrar as tags de cada artigo.
- **Gravar Hits** Registrar o número de vezes que o artigo foi visualizado.
- **Hits** Mostrar o número de vezes que o artigo foi exibido por um usuário.
- **Links Não Autorizados**
  - **Sim** O Texto de Introdução para artigos restritos será exibido. Clicar no link Leia Mais exigirá que os usuários façam login para visualizar o conteúdo completo do artigo.
  - **Não** Artigos que o usuário não está autorizado a visualizar (com base no nível de acesso de visualização do artigo) não serão exibidos.
- **Posicionamento dos Links**
  - **Acima** Links são mostrados acima do conteúdo.
  - **Abaixo** Links são mostrados abaixo do conteúdo.

### Aba Layout de Edição

Estas opções controlam o layout da página de edição do artigo.

![Opções de edição de layout de artigos](../../../ptbr/images/articles/articles-options-editing-layout-tab.png)

- **Permitir Captcha ao Enviar** Selecione o plugin captcha que será usado no formulário de envio do artigo. Se *Usar Global* estiver selecionado, certifique-se de que um plugin captcha esteja selecionado na Configuração Global.
- **Opções de Publicação** Ocultar a aba Opções de Publicação no Backend ao editar Artigos. Isso significa que os usuários do Backend não poderão editar os campos nesta aba. Esses campos sempre serão definidos para seus valores padrão.
- **Opções do Artigo** Ocultar a aba Opções de Artigo no Backend ao editar Artigos. Isso significa que os usuários do Backend não poderão editar os campos nesta aba. Esses campos sempre serão definidos para seus valores padrão.
- **Opções da Tela de Edição** Ocultar a aba Configurar Tela de Edição ao editar Artigos.
- **Permissões do Artigo** Ocultar a aba Permissões ao editar Artigos.
- **Associações Multilíngue** Ocultar a aba Associações ao editar Artigos.
- **Habilitar Versões** Salvar histórico de versões para Artigos e Categorias.
- **Máximo de Versões** O número máximo de versões a serem armazenadas para um Artigo ou Categoria. Se um Artigo ou Categoria for salvo e o número máximo de versões for atingido, a versão mais antiga será excluída automaticamente. Se configurado como "0", as versões nunca serão excluídas automaticamente.
- **Imagens e Links no Frontend** Ocultar a aba Imagens e Links na tela do editor de artigos do Frontend.
- **Imagens e Links do Administrador** Ocultar a aba Imagens e Links no Backend ao editar Artigos.
- **Janela de Destino do URL A** Define o valor padrão para o destino do primeiro Link no artigo. As opções são:
  - **Abrir na janela pai** Abre no principal navegador, substituindo o artigo atual do Joomla.
  - **Abrir em nova janela** Abre o link em uma nova janela do navegador.
  - **Abrir em popup** Abre o link em uma janela popup do navegador (sem controles completos de navegação).
  - **Modal** Abre o link em uma janela popup modal.
- **Janela de Destino do URL B** Define o valor padrão para o destino do segundo Link no artigo. Mesmas opções do URL A.
- **Janela de Destino do URL C** Define o valor padrão para o destino do terceiro Link no artigo. Mesmas opções do URL A.
- **Classe de Imagem de Introdução** Define o atributo de classe para uma Imagem de Introdução selecionada no campo Imagem de Introdução.
- **Classe de Imagem do Texto Completo** Define o atributo de classe para uma Imagem de Artigo Completo selecionada no campo Imagem de Artigo Completo.

### Aba Categoria

Essas configurações se aplicam às Opções de Categoria de Artigos, a menos que sejam alteradas pela categoria individual ou pelas configurações do menu.

![Opções de categoria de artigos](../../../ptbr/images/articles/articles-options-category-tab.png)

- **Escolher um Layout** Selecione o layout padrão a ser exibido quando um link da Categoria for selecionado.
- **Título da Categoria** Mostrar o título da categoria.
- **Descrição da Categoria** Mostrar a descrição da categoria.
- **Imagem da Categoria** Mostrar a imagem da categoria.
- **Níveis de Subcategoria** Controlar quantos níveis de subcategorias exibir.
- **Categorias Vazias** Mostrar categorias que não contêm nenhum artigo ou subcategoria.
- **Mensagem de Sem Artigos** Exibir uma mensagem "Não há artigos nesta categoria".
- **Cabeçalho de Subcategorias** Mostrar as Subcategorias como subtítulo na página.
- **Descrições das Subcategorias** Mostrar as descrições das subcategorias.
- **# Artigos na Categoria** Mostrar a contagem do número total de artigos em cada categoria.
- **Tags** Mostrar as tags para a categoria.

### Aba Categorias

Essas configurações se aplicam às Opções de Categorias de Artigos, a menos que sejam alteradas pela categoria individual ou pelas configurações do menu.

![Opções de categorias de artigos](../../../ptbr/images/articles/articles-options-categories-tab.png)

- **Descrição da Categoria do Nível Superior** Mostrar a descrição da categoria de nível superior.
- **Níveis de Subcategoria** Controlar quantos níveis de subcategorias exibir.
- **Categorias Vazias** Mostrar categorias que não contêm nenhum artigo ou subcategoria.
- **Descrições das Subcategorias** Mostrar a descrição das subcategorias.
- **# Artigos na Categoria** Mostrar a contagem do número total de artigos em cada categoria.

### Aba Layouts de Blog/Destaque

Essas configurações se aplicam a layouts de blog ou destaque, a menos que sejam alteradas para um item de menu específico.

![Opções de layout de blog e destaque de artigos](../../../ptbr/images/articles/articles-options-blog-layouts-tab.png)

- **# Artigos Principais** Número de Artigos a serem exibidos utilizando a largura total da área principal de exibição. "0" significa que nenhum Artigo será exibido usando a largura total. Se um Artigo tiver uma quebra "Leia Mais...", apenas a parte do texto antes da quebra (o texto de introdução) será exibida.
- **Classe do Artigo Principal** Adicione qualquer classe CSS para personalizar o layout. Adicione uma borda no topo com a classe boxed. Para a posição da imagem, utilize, por exemplo, image-left, image-right. Adicione image-alternate para ordenar alternadamente as imagens de introdução.
- **# Artigos de Introdução** Determina o número de Artigos a serem exibidos após o Artigo Principal. Esses Artigos serão exibidos no número de colunas definidas no parâmetro Colunas abaixo. Se um Artigo tiver uma quebra "Leia Mais...", apenas o texto antes da quebra (texto de introdução) será exibido, seguido de um link "Leia Mais...". A ordem em que os artigos serão exibidos é determinada pelos parâmetros Ordem da Categoria e Ordem do Artigo abaixo.
- **Classe do Artigo** Adicione qualquer classe CSS para estilização personalizada. Adicione uma borda no topo com a classe boxed. Para a posição da imagem, utilize, por exemplo, image-left, image-right. Adicione image-alternate para ordenar alternadamente as imagens de introdução.
- **# Colunas** O número de colunas a ser usado na área de Artigos de Introdução. Isso geralmente varia entre 1 e 3 (dependendo do template em uso). Se for 1, os Artigos de Introdução serão exibidos utilizando a largura total da área de exibição, assim como os Artigos Principais.
- **Direção das Colunas Múltiplas** Em layouts de blog com múltiplas colunas, se os artigos serão ordenados para Baixo ou Através das colunas.
  - **Para Baixo** Ordena os artigos descendo pela primeira coluna e depois para a próxima coluna.
  - **Através** Ordena os artigos através das colunas e depois volta para a primeira coluna.
- **# Links** O número de Links a serem exibidos na área de Links da página. Esses links permitem que um usuário acesse artigos adicionais, se houver mais artigos do que cabem na primeira página do Layout de Blog.
- **Incluir Subcategorias**
  - **Nenhuma** Apenas artigos da categoria atual serão exibidos.
  - **Todas** Todos os artigos da categoria atual e todas as subcategorias serão exibidos.
  - **1-5** Todos os artigos da categoria atual e subcategorias até e incluindo aquele nível serão exibidos.
- **Imagem de Introdução Vinculada** Se Sim, um clique na imagem de introdução exibe o artigo.

### Aba Layouts de Lista

Essas configurações se aplicam às Opções de Layouts de Lista, a menos que sejam alteradas para um item de menu ou categoria específico.

![Opções de layouts de lista de artigos](../../../ptbr/images/articles/articles-options-list-layouts-tab.png)

- **Selecionar Exibição** Mostrar o controle Exibir \# que permite ao usuário selecionar o número de artigos a exibir.
- **Campo de Filtro** Mostrar um campo de texto no Frontend onde um usuário pode filtrar os artigos. Opções no menu de edição do Backend.
  - **Ocultar** Não mostrar um campo de filtro.
  - **Título** Filtrar pelo título do artigo.
  - **Autor** Filtrar pelo nome do autor.
  - **Hits** Filtrar pelo número de hits do artigo.
  - **Tags** Filtrar pelas tags do artigo.
  - **Mês (publicado)** Filtrar pelo mês dos artigos publicados.
- **Cabeçalhos de Tabela** Mostrar um cabeçalho na lista de artigos no Frontend.
- **Data** Mostrar uma data na lista.
  - **Ocultar** Não mostrar nenhuma data.
  - **Criado** Mostrar a data de criação.
  - **Modificado** Mostrar a data da última modificação.
  - **Publicado** Mostrar a data de início da publicação.
- **Hits** Mostrar o número de hits para artigos.
- **Autor** Mostrar o nome do autor.
- **# Artigos na Lista** Número de artigos exibidos na lista.

### Aba Compartilhada

Essas configurações se aplicam às Opções Compartilhadas em layouts de Lista, Blog e Destaque, a menos que sejam alteradas pelas configurações do menu.

![Opções compartilhadas de artigos](../../../ptbr/images/articles/articles-options-shared-tab.png)

- **Ordem da Categoria**
  - **Sem Ordem** Os artigos são ordenados apenas pela Ordem do Artigo, sem considerar a Categoria.
  - **Título Alfabético** As categorias são exibidas em ordem alfabética (A a Z).
  - **Título Reverso Alfabético** As categorias são exibidas em ordem alfabética inversa (Z a A).
  - **Ordem da Categoria** As categorias são ordenadas de acordo com a coluna Ordem inserida em Artigos: Categorias.
- **Ordem do Artigo**
  - **Mais Recentes Primeiro** Os artigos são exibidos começando pelos mais recentes e terminando com os mais antigos.
  - **Mais Antigos Primeiro** Os artigos são exibidos começando pelos mais antigos e terminando com os mais recentes.
  - **Título Alfabético** Os artigos são exibidos por Título em ordem alfabética (A a Z).
  - **Título Reverso Alfabético** Os artigos são exibidos por Título em ordem alfabética inversa (Z a A).
  - **Autor Alfabético** Os artigos são exibidos por Autor em ordem alfabética (A a Z).
  - **Autor Reverso Alfabético** Os artigos são exibidos por Autor em ordem alfabética inversa (Z a A).
  - **Mais Hits** Os artigos são exibidos pelo número de hits, começando pelo que tem mais hits e terminando com o que tem menos hits.
  - **Menos Hits** Os artigos são exibidos pelo número de hits, começando pelo que tem menos hits e terminando com o que tem mais hits.
  - **Ordenação** Os artigos são ordenados de acordo com a coluna Ordem inserida em Artigos.
  - **Ordenação Reversa** Os artigos são ordenados inversamente de acordo com a coluna Ordem inserida em Artigos.
- **Data para Ordenação** A data usada quando os artigos são classificados por data.
  - **Criado** Usar a data de criação do artigo.
  - **Modificado** Usar a data de modificação do artigo.
  - **Publicado** Usar a data de início da publicação do artigo.
- **Paginação** A paginação fornece links de página na parte inferior da página que permitem ao usuário navegar para páginas adicionais. Esses são necessários se os Artigos não couberem em uma página.
  - **Ocultar** Links de paginação não são exibidos. Nota: Os usuários não poderão navegar para páginas adicionais.
  - **Mostrar** Links de paginação exibidos se necessário.
  - **Auto** Links de paginação exibidos se necessário.
- **Resumo da Paginação** Mostrar o número da página atual e o total de páginas (por exemplo, "Página 1 de 2") na parte inferior de cada página.
- **Artigos em Destaque**
  - **Mostrar** Exibir artigos em destaque e artigos não em destaque.
  - **Ocultar** Exibir apenas artigos não em destaque.
  - **Apenas** Exibir apenas artigos em destaque.

### Aba Integração

Essas configurações determinam como o Componente de Artigos se integrará com outras extensões.

![Opções de integração de artigos](../../../ptbr/images/articles/articles-options-integration-tab.png)

#### Painel de Feeds de Notícias

- **Link do Feed RSS** Se definido como Mostrar, um link de Feed aparecerá como um ícone de feed na barra de endereço da maioria dos navegadores.
- **Incluir no Feed**
  - **Texto de Introdução** Apenas o texto de introdução do artigo será exibido no feed.
  - **Texto Completo** Todo o texto do artigo será exibido no feed.
- **Link "Leia Mais"** Mostrar um link "Leia mais" no feed.

#### Painel de Roteamento

- **Remover IDs das URLs** Remover o id do banco de dados dos artigos em um link.

#### Painel de Campos Personalizados

- **Editar Campos Personalizados** Habilitar a criação de campos personalizados.

#### Painel de Workflow

- **Habilitar Workflow** Usar workflows personalizados para gerenciar artigos.

## Dicas

- Usuários novatos podem manter os valores padrões aqui.
- Usuários experientes podem economizar tempo criando valores padrões apropriados aqui.
  Novos itens de menu e artigos poderão então usar os valores padrões para
  a maioria das opções.
- Todos os valores definidos aqui podem ser substituídos no nível do item de menu, categoria ou
  artigo.

*Traduzido por openai.com*

