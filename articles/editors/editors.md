<!-- Filename: Help4.x:Editors  / Display title: Editores -->

## TinyMCE

TinyMCE é o editor padrão para usuários do Frontend e Backend. O editor
permite aos usuários uma interface familiar de processamento de texto para usar ao editar
Conteúdo.

TinyMCE pode ser configurado com 3 conjuntos diferentes de botões da barra de ferramentas. Isso
é configurado no plugin Editor - TinyMCE.

### Barras de Ferramentas

#### Predefinição Simples

O conjunto da barra de ferramentas 2 fornece uma linha de botões como mostrado abaixo. O conjunto é
atribuído por padrão ao grupo de usuários Público.

<img
src="https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/600px-Help-4x-editor-tinymce-simple-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/900px-Help-4x-editor-tinymce-simple-en.png 1.5x, https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/1200px-Help-4x-editor-tinymce-simple-en.png 2x"
data-file-width="1451" data-file-height="80" width="600" height="33"
alt="tinymce simple preset toolbar" />

- Botões permitem que você deixe o texto: em negrito, sublinhado ou tachado.
- Desfazer e Refazer.
- Lista não ordenada, Lista ordenada.
- Colar Como Texto: Com frequência, ao copiar e colar texto de outras fontes,
  como arquivos PDF, documentos de texto ou páginas da web, o texto selecionado
  contém informações de formatação que não são necessárias ou desejadas. Usar
  "Colar Como Texto" removerá toda a formatação do texto.

#### Predefinição Média

O conjunto da barra de ferramentas 1 fornece duas linhas de botões como mostrado abaixo. O conjunto
é atribuído por padrão ao grupo de usuários Gerente e Registrados.

<img
src="https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/800px-Help-4x-editor-tinymce-advanced-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/1200px-Help-4x-editor-tinymce-advanced-en.png 1.5x, https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/1600px-Help-4x-editor-tinymce-advanced-en.png 2x"
data-file-width="1977" data-file-height="236" width="800" height="95"
alt="tinymce medium preset toolbar" />

Essa opção fornece todos os mesmos botões documentados na Barra de Ferramentas 2
acima. Além disso, as seguintes opções estão disponíveis.

#

#### Médio: Primeira Linha

- Conteúdo CMS: A lista suspensa fornece acesso para linkar a um Artigo,
  Contato, Campo, Mídia, Menu ou Módulo.

Artigo: O exemplo mostra como criar facilmente um link para qualquer artigo no
site atual.

<img
src="https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/600px-Help-4x-article-quick-link-button-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/900px-Help-4x-article-quick-link-button-en.png 1.5x, https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/1200px-Help-4x-article-quick-link-button-en.png 2x"
data-file-width="2304" data-file-height="1321" width="600" height="344"
alt="article selection dialog" />

Para criar um link para o artigo desejado:

- Coloque o cursor no ponto do artigo onde deseja inserir o título do artigo com link.
- Clique no botão Artigo para abrir a janela.
- Clique no título para selecionar o artigo desejado na janela. Você
  pode usar a busca e os filtros para ajudar a encontrar o artigo desejado.
- Um link com o título do artigo será inserido na localização atual do cursor.
- Se necessário, você pode editar o texto do link.

Da mesma forma, você pode vincular outros itens como Mídia, Módulos, e assim por diante.

Quebra de Página: Este botão permite inserir uma quebra de página dentro de um
artigo. Uma quebra de página permite a navegação por páginas quando o artigo é
exibido em um layout. Isso é útil para artigos longos. Quando este
botão é pressionado, uma janela é exibida como mostrado abaixo:

<img
src="https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/600px-Help-4x-editor-pagebreak-button-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/900px-Help-4x-editor-pagebreak-button-en.png 1.5x, https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/1200px-Help-4x-editor-pagebreak-button-en.png 2x"
data-file-width="1542" data-file-height="862" width="600" height="335"
alt="pagebreak button" />

- **Título da Página**. Insira o título a ser exibido para a nova página (por
  exemplo, 'Página 2').
- **Alias do Índice**. Campo opcional para exibir no índice
  para esta página. Em um artigo de várias páginas, o Joomla exibe um
  'índice' para a página que permite ao usuário selecionar qualquer
  página. Se este campo estiver em branco, será utilizado o Título da Página. Se você quiser
  um título diferente no índice, insira-o aqui.
- **Inserir Quebra de Página**. Clique neste botão para inserir a quebra de página com
  os campos preenchidos. A quebra de página será exibida como uma linha cinza tracejada
  no artigo. Note que uma quebra de página não pode ser editada. Se precisar
  alterar um campo na quebra de página, clique no artigo logo
  após a quebra de página, pressione Backspace até que a quebra de página seja excluída,
  depois insira uma nova quebra de página com as informações desejadas.
- A configuração é feita no plugin
  Conteúdo - Page Break
  .

Ler Mais: Este botão insere uma quebra de Ler mais no artigo. Isto
será mostrado como uma linha vermelha pontilhada no artigo.

- Se um artigo tiver uma quebra de Ler mais, apenas o texto antes da quebra,
  chamado de Texto de Introdução, será inicialmente exibido, junto com um link de Ler mais. Se o usuário clicar neste link, ou o artigo completo ou apenas
  a parte após o link de Ler mais será exibida. Isso depende da
  configuração dos parâmetros do
  Texto de Introdução
  para o artigo.
- A quebra de Ler mais permite que você economize espaço nas páginas, mostrando apenas
  o Texto de Introdução.
- Se você quiser inserir quebras para um artigo exibido em um Layout de Artigo,
  use o botão Quebra de Página.

Os botões na lista suspensa de conteúdo do CMS podem ser desativados em
Plugins - editors-xtd.

- Botões no canto superior esquerdo permitem deixar o texto: em itálico. Ao lado desses botões
  estão os botões para alinhar à esquerda, direita, centro e justificado.
- Formatos: Selecionar formatos predefinidos para Títulos, Inline, Blocos, e assim por diante.
- Recuar à esquerda e Recuar à direita.
- 3 pontos: Mostrar segunda linha da Barra de ferramentas.

#### Médio: Segunda Linha

- Inserir/editar Link: Para inserir ou editar um link, selecione o texto vinculado e
  pressione este botão. Um pop-up é exibido permitindo que você insira detalhes
  sobre o link.
- Remover Link: Para remover um link, destaque o texto vinculado e pressione
  este botão.
- Âncora: Uma âncora é um marcador dentro de um artigo que permite
  linkar diretamente a esse ponto no artigo.
- Código fonte: Um pop-up é exibido mostrando o código fonte HTML, permitindo
  que você edite o código fonte HTML.
- Inserir uma linha horizontal: Para inserir uma linha horizontal, mova o cursor
  para a localização desejada dentro do artigo e clique nesse botão.
- Tabela: Inserir Nova Tabela, Propriedades da Linha da Tabela, Propriedades da Célula da Tabela,
  Inserir Linha Antes, Inserir Linha Depois, Excluir Linha, Inserir Coluna Antes,
  Inserir Coluna Depois, Excluir Coluna, Dividir Células Mescladas da Tabela, Mesclar
  Células da Tabela.
- Subscrito, Sobrescrito, Caractere Especial.
- Visualizar texto em pop-up.

#### Predefinição Avançada

O conjunto da barra de ferramentas 0 oferece as opções de edição mais extensas, como mostrado
abaixo. O conjunto é atribuído por padrão ao grupo de usuários Administrador, Editor e
Super Usuários.

<img
src="https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/800px-Help-4x-editor-tinymce-extended-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/1200px-Help-4x-editor-tinymce-extended-en.png 1.5x, https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/1600px-Help-4x-editor-tinymce-extended-en.png 2x"
data-file-width="1977" data-file-height="393" width="800" height="159"
alt="tinymce advanced preset toolbar" />

Essa opção fornece todos os mesmos botões documentados na Barra de Ferramentas 1
acima. Além disso, as seguintes opções estão disponíveis.

#### Avançado: Primeira Linha

- Blocos: Parágrafo, Títulos, Pré-formatado.
- Fontes: Selecione a fonte desejada.
- Tamanho da Fonte: Selecione o tamanho da fonte desejado.
- Localizar e Substituir.
- Inserir/editar imagem: Para inserir uma imagem, coloque o cursor na localização
  desejada e pressione este botão. Um pop-up será exibido permitindo
  que você insira a Fonte, Largura ou Altura e outras informações
  sobre a imagem.

#### Avançado: Segunda Linha

- Selecionar cor do Texto ou cor do Fundo.
- Tela cheia.
- Emoticons.
- Inserir mídia: Para inserir mídia, coloque o cursor na localização
  desejada e pressione este botão. Um pop-up será exibido permitindo
  que você insira o Tipo, Arquivo ou URL, e outras informações sobre
  a mídia.
- Direção da Esquerda para a Direita ou Direção da Direita para a Esquerda: Esses botões
  permitem que você insira ou altere a direção do texto, por exemplo para
  idiomas que são lidos da direita para a esquerda.
- Cortar, Copiar, Colar.
- Mostrar caracteres invisíveis (como fim de parágrafo).
- Mostrar blocos.
- Espaço inquebrável.
- Bloco de citação.
- Inserir Modelo.

#### Avançado: Terceira Linha

- Imprimir o texto do artigo.
- Inserir/editar exemplo de código.
- Inserir data/hora.
- Limpar formatação.

### Acessibilidade

TinyMCE é compatível com leitores de tela como
<a href="https://www.freedomscientific.com/products/software/jaws/"
rel="nofollow noreferrer noopener">JAWS</a> e
<a href="https://www.nvaccess.org/"
rel="nofollow noreferrer noopener">NVDA</a>. Você pode usá-lo
efetivamente mesmo sem usar o mouse.

| Tarefa                                   | PC                     | macOS                  |
|------------------------------------------|------------------------|------------------------|
| Focar/pular para a barra de menu         | Alt+F9                 | âŒ¥+F9                 |
| Focar/pular para a barra de ferramentas  | Alt+F10                | âŒ¥+F10                |
| Focar/pular para o caminho do elemento   | Alt+F11                | âŒ¥+F11                |
| Fechar menu/sub-menu/diálogo             | Esc                    | esc                    |
| Retornar para a área de conteúdo do editor | Esc                    | esc                    |
| Navegar esquerda/direita pelo menu/barra de ferramentas | Tab e as Setas | Tab e as Setas   |

Atalhos de teclado

Veja para mais informações:

- <a href="https://www.tiny.cloud/docs/advanced/accessibility/"
  rel="nofollow noreferrer noopener">TinyMCE - Acessibilidade</a>
- Uma lista dos
  <a href="https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/"
  rel="nofollow noreferrer noopener">atalhos de teclado</a> disponíveis (pc, mac)
  dentro do corpo do editor.


## CodeMirror

O 'Editor - CodeMirror' foi projetado para facilitar a entrada de código HTML em um artigo ou descrição. O CodeMirror suporta realce de sintaxe e autocompletação, como mostrado nesta captura de tela.

<img
src="https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/800px-Help-4x-screenshot-editor-codemirror-example-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/1200px-Help-4x-screenshot-editor-codemirror-example-en.png 1.5x, https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/1600px-Help-4x-screenshot-editor-codemirror-example-en.png 2x"
data-file-width="1977" data-file-height="905" width="800" height="366"
alt="exemplo do codemirror" />

- Os botões mostrados abaixo da janela de edição fornecem acesso para vincular a qualquer item do site.
- O CodeMirror oferece algumas das mesmas vantagens de usar o 'Editor - Nenhum', mas torna um pouco mais fácil trabalhar com código HTML bruto.
- A configuração é feita no plugin Editor - CodeMirror.


## Nenhum

Se 'Editor - Nenhum' for selecionado para um Usuário, então um editor de texto simples é exibido. Isso permite que você insira HTML bruto e não formatado. Você pode usar o botão 'Visualizar' da barra de ferramentas para visualizar como o HTML será exibido.

Observe que a opção 'Nenhum' pode ser útil se você estiver inserindo 'boilerplate' ou HTML personalizado, por exemplo, para criar um link do PayPal. O TinyMCE reformata automaticamente e remove parte do HTML quando um arquivo é salvo. Isso pode fazer com que HTML complexo não funcione corretamente.

Se isso acontecer, você pode temporariamente mudar o editor para 'Nenhum' e criar o conteúdo desejado. Note que se você desejar editar este conteúdo no futuro, deve ter cuidado para alterar o editor para 'Nenhum'. Caso contrário, se você abrir e salvar o conteúdo com o TinyMCE, pode perder seu HTML personalizado.

O plugin 'Editor - Nenhum' não possui configuração.

*Traduzido por openai.com*

