<!--
{
    "source": "https://docs.joomla.org/Help4.x:Editors",
    "title": "Editores: Introdu\u00e7\u00e3o",
    "description": " ",
    "author": ""
}
-->

## TinyMCE

TinyMCE é o editor padrão para usuários do Frontend e do Backend. O editor
permite que os usuários tenham uma interface familiar de processamento de
texto para usar ao editar
Conteúdo.

O TinyMCE pode ser configurado com 3 conjuntos diferentes de botões da
barra de ferramentas. Isso é definido no plugin Editor - TinyMCE.

### Barras de ferramentas

#### Predefinição simples

O conjunto 2 da barra de ferramentas fornece uma linha de botões, conforme
mostrado abaixo. O conjunto é atribuído por padrão ao grupo de usuários
Público.

![Barra de ferramentas 2 do TinyMCE](../../../en/images/editors/editors/01-set-2.png)

- Os botões permitem formatar o texto como: negrito, sublinhado ou tachado.
- Desfazer e Refazer.
- Lista não ordenada, Lista ordenada.
- Colar como texto: frequentemente, ao copiar e colar texto de outras fontes,
  como arquivos PDF, documentos de texto ou páginas da web, o texto
  selecionado contém informações de formatação que não são necessárias ou
  desejadas. Usar a opção “Colar como texto” removerá toda a formatação do texto.

#### Predefinição média

O conjunto 1 da barra de ferramentas fornece duas linhas de botões, conforme
mostrado abaixo. O conjunto é atribuído por padrão aos grupos de usuários
Gerente e Registrado.

![Barra de ferramentas 1 do TinyMCE](../../../en/images/editors/editors/02-set-1.png)

Essa opção fornece todos os mesmos botões documentados acima na barra de
ferramentas do conjunto 2. Além disso, as seguintes opções estão disponíveis.

#### Médio: linha superior

- Conteúdo do CMS: a lista suspensa fornece acesso para criar links para um Artigo,
  Contato, Campo, Mídia, Menu ou Módulo.

Artigo: o exemplo mostra como criar facilmente um link para qualquer artigo no
site atual.

![Janela modal do seletor de links do TinyMCE](../../../en/images/editors/editors/03-link-button.png)

Para criar um link para o artigo desejado:

- Posicione o cursor no ponto do artigo onde deseja que o título do artigo
  vinculado seja inserido.
- Clique no botão Artigo para abrir a janela.
- Clique no título para selecionar o artigo desejado na janela. Você
  pode usar a pesquisa e os filtros para ajudar a encontrar o artigo desejado.
- Um link com o título do artigo será inserido no local atual do cursor.
- Se necessário, você pode editar o texto do link.

Da mesma forma, você pode criar links para outros itens, como Mídia, Módulos e assim por diante.

Quebra de página: este botão permite inserir uma quebra de página dentro de um
artigo. Uma quebra de página permite a navegação entre páginas quando o artigo é
exibido em um layout. Isso é útil para artigos longos. Quando este botão é
pressionado, uma janela é exibida conforme mostrado abaixo:

![Formulário de quebra de página do TinyMCE](../../../en/images/editors/editors/04-pagebreak-button.png)

- **Título da página**. Insira o título a ser exibido para a nova página (por
  exemplo, “Página 2”).
- **Alias do índice**. Campo opcional a ser exibido no índice desta página.
  Em um artigo com várias páginas, o Joomla exibe um “índice” da página que
  permite ao usuário selecionar qualquer página. Se este campo estiver em branco,
  o Título da página será usado. Se quiser um título diferente no índice,
  insira-o aqui.
- **Inserir quebra de página**. Clique neste botão para inserir a quebra de página
  com os campos preenchidos. A quebra de página será exibida como uma linha
  tracejada cinza ao longo do artigo. Observe que uma quebra de página não pode
  ser editada. Se precisar alterar um campo na quebra de página, clique no artigo
  logo após a quebra de página, pressione Backspace até que a quebra de página seja
  excluída e, em seguida, insira uma nova quebra de página com as informações desejadas.
- A configuração é definida no plugin Conteúdo - Quebra de página.

Leia mais: este botão insere uma quebra de Leia mais no artigo. Ela é exibida
como uma linha pontilhada vermelha ao longo do artigo.

- Se um artigo tiver uma quebra de Leia mais, somente o texto antes da quebra,
  chamado Texto de introdução, será exibido inicialmente, juntamente com um link
  Leia mais. Se o usuário clicar nesse link, o artigo inteiro ou apenas a parte
  posterior ao link Leia mais será exibida. Isso depende da configuração dos
  parâmetros de
  Texto
  de introdução do artigo.
- A quebra de Leia mais permite economizar espaço nas páginas mostrando apenas
  o Texto de introdução.
- Se quiser inserir quebras em um artigo exibido em um layout de artigo, use o
  botão Quebra de página.

Os botões da lista suspensa de conteúdo do CMS podem ser desativados em
Plugins - editors-xtd.

- Os botões no canto superior esquerdo permitem formatar o texto como: itálico. Ao lado
  deles estão os botões para alinhar à esquerda, à direita, ao centro e justificar.
- Formatos: selecione formatos predefinidos para Títulos, Inline, Blocos e
  assim por diante.
- Diminuir recuo (mover para a esquerda) e Aumentar recuo (recuar para a direita).
- 3 pontos: mostrar a segunda linha da barra de ferramentas.

#### Médio: Segunda linha

- Inserir/editar link: para inserir ou editar um link, selecione o texto vinculado e
  pressione este botão. Uma caixa de diálogo pop-up será exibida, permitindo inserir detalhes
  sobre o link.
- Remover link: para remover um link, realce o texto vinculado e pressione
  este botão.
- Âncora: uma âncora é um marcador dentro de um artigo que permite criar um link
  diretamente para esse ponto no artigo.
- Código-fonte: uma janela pop-up será exibida mostrando o código-fonte HTML, permitindo
  editar o código-fonte HTML.
- Inserir uma linha horizontal: para inserir uma linha horizontal, mova o cursor
  para o local desejado dentro do artigo e clique neste botão.
- Tabela: inserir nova tabela, propriedades da linha da tabela, propriedades da célula da tabela,
  inserir linha antes, inserir linha depois, excluir linha, inserir coluna antes,
  inserir coluna depois, excluir coluna, dividir células mescladas da tabela, mesclar
  células da tabela.
- Subscrito, sobrescrito, caractere especial.
- Visualizar texto em uma janela pop-up.

#### Predefinição avançada

O conjunto de ferramentas 0 fornece as opções de edição mais abrangentes, conforme mostrado
abaixo. O conjunto é atribuído por padrão aos grupos de usuários Administrador, Editor e
Superusuários.

![Conjunto de dados 0 do TinyMCE](../../../en/images/editors/editors/05-set-0.png)

Essa opção fornece todos os mesmos botões documentados na barra de ferramentas do Conjunto 1
acima. Além disso, as seguintes opções estão disponíveis.

#### Avançado: linha superior

- Blocos: parágrafo, títulos, pré-formatado.
- Fontes: selecione a fonte desejada.
- Tamanho da fonte: selecione o tamanho de fonte desejado.
- Localizar e substituir.
- Inserir/editar imagem: para inserir uma imagem, coloque o cursor no local desejado
  e pressione este botão. Uma caixa de diálogo pop-up será exibida,
  permitindo inserir a origem, a largura ou a altura e outras informações
  sobre a imagem.

#### Avançado: segunda linha

- Selecionar a cor do texto ou a cor do plano de fundo.
- Tela cheia.
- Emoticons.
- Inserir mídia: para inserir mídia, coloque o cursor no local desejado
  e pressione este botão. Uma caixa de diálogo pop-up será exibida,
  permitindo inserir o tipo, o arquivo ou a URL e outras informações sobre
  a mídia.
- Direção da esquerda para a direita ou direção da direita para a esquerda: estes botões
  permitem inserir ou alterar a direção do texto, por exemplo, para
  idiomas escritos da direita para a esquerda.
- Recortar, copiar, colar.
- Mostrar caracteres invisíveis (como finais de parágrafo).
- Mostrar blocos.
- Espaço sem quebra.
- Citação em bloco.
- Inserir modelo.

#### Avançado: terceira linha

- Imprimir o texto do artigo.
- Inserir/editar exemplo de código.
- Inserir data/hora.
- Limpar formatação.

### Acessibilidade

O TinyMCE é compatível com leitores de tela, como
<a href="https://www.freedomscientific.com/products/software/jaws/"
rel="nofollow noreferrer noopener">JAWS</a> e
<a href="https://www.nvaccess.org/"
rel="nofollow noreferrer noopener">NVDA</a>. Você pode usá-lo
com eficiência mesmo que não use o mouse.

#### Atalhos de teclado

| Tarefa                                     | PC                     | macOS                  |
|--------------------------------------------|------------------------|------------------------|
| Focar/ir para a barra de menus            | Alt+F9                 | ⌥+F9                   |
| Focar/ir para a barra de ferramentas      | Alt+F10                | ⌥+F10                  |
| Focar/ir para o caminho do elemento       | Alt+F11                | ⌥+F11                  |
| Fechar menu/submenu/caixa de diálogo      | Esc                    | esc                    |
| Retornar à área de conteúdo do editor     | Esc                    | esc                    |
| Navegar para a esquerda/direita pelo menu/barra de ferramentas | Tab e as teclas de seta | Tab e as teclas de seta |

Consulte mais informações em:

- <a href="https://www.tiny.cloud/docs/advanced/accessibility/"
  rel="nofollow noreferrer noopener">TinyMCE - Acessibilidade</a>
- Uma lista de
  <a href="https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/"
  rel="nofollow noreferrer noopener">atalhos de teclado</a> disponíveis (pc, mac)
  no corpo do editor.

## CodeMirror

O 'Editor - CodeMirror' foi desenvolvido para facilitar a inserção de código HTML
em um artigo ou descrição. O CodeMirror oferece realce de sintaxe
e preenchimento automático, conforme mostrado nesta captura de tela.

![formulário de edição do CodeMirror](../../../en/images/editors/editors/06-codemirror.png)

- Os botões exibidos abaixo da janela de edição permitem acessar links para qualquer
  item do site.
- O CodeMirror oferece algumas das mesmas vantagens de usar o 'Editor -
  None', mas torna um pouco mais fácil trabalhar com código HTML bruto.
- A configuração é definida no plugin
  Editor -
  CodeMirror.

## Nenhum

Se a opção 'Editor - Nenhum' estiver selecionada para um usuário, um editor de texto simples será exibido. Isso permite inserir HTML bruto e não formatado. Você pode usar o botão 'Visualizar' da barra de ferramentas para visualizar como o HTML será exibido.

Observe que a opção 'Nenhum' pode ser útil se você estiver inserindo HTML padrão ou personalizado, por exemplo, para criar um link do PayPal. O TinyMCE reformata e remove automaticamente parte do HTML quando um arquivo é salvo. Isso pode fazer com que HTML complexo não funcione corretamente.

Se isso acontecer, você poderá alterar temporariamente o editor para 'Nenhum' e criar o conteúdo desejado. Observe que, se quiser editar esse conteúdo no futuro, deverá ter cuidado para alterar o editor para 'Nenhum'. Caso contrário, se você abrir e salvar o conteúdo com o TinyMCE, poderá perder seu HTML personalizado.

O plugin 'Editor - Nenhum' não possui configuração.

*Traduzido por openai.com*