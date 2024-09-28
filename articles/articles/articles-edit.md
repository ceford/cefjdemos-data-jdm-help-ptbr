<!-- Filename: Help4.x:Articles:_Edit  / Display title: Artigos: Editar -->

## Descrição

Esta página é usada para adicionar um novo artigo ou editar um artigo existente, geralmente usando um editor Wysiwyg. O editor padrão é o TinyMCE, mas se outros editores estiverem instalados, o editor padrão pode ser configurado para algo diferente para o site como um todo ou para usuários individuais.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Guia de Esquema](jdocmanual?article=help/common-elements/edit-schema).
* [A Guia de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Guia de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Guia de Permissões](jdocmanual?article=help/common-elements/edit-permissions).
* [O Popup de Histórico de Versões](jdocmanual?article=help/common-elements/edit-version-history).

Ou em artigos do Usuário:

* [Adicionando uma Imagem a um Artigo](jdocmanual?article=user/articles/adding-an-image-to-an-article)

## Como Acessar

* Selecione **Conteúdo → Artigos** no menu do Administrador. Ou...
* Selecione **Artigos** no Painel Inicial. Em seguida...
    * Selecione um **Título** de artigo existente na lista para editá-lo. Ou...
    * Selecione o botão **Novo** na Barra de Ferramentas para criar um novo artigo.
Você também pode criar um novo artigo selecionando o ícone **+** no Menu ou no
Painel Inicial.

## Captura de Tela

![Captura de tela da edição de artigos](../../../ptbr/images/articles/articles-edit-content-tab.png)


## Campos do Formulário

- **Título** O título para este artigo.
- **Alias** O nome interno deste artigo. Normalmente, você pode deixar
  este campo em branco e o Joomla preencherá com um valor padrão baseado no título,
  mas em letras minúsculas e com hífens em vez de espaços.

### Aba Conteúdo

#### Painel Esquerdo

- **Texto do Artigo** Aqui é onde você insere o conteúdo do artigo.
    O Joomla inclui 3 editores, o Editor Padrão - TinyMCE é mostrado acima.

    A lista suspensa de Conteúdo do CMS fornece acesso para linkar a um Artigo,
    Contato, Campo, Imagem de Mídia, Menu, Módulo, Quebra de Página ou Quebra de Leia Mais.

    O símbolo de reticências (<span class="icon-ellipsis-h"></span>) alterna a visibilidade
    das ferramentas extras.
- **Alternar Editor** O botão abaixo da janela de edição permite que você alterne
    entre o editor TinyMCE e sem editor. Isso permite que você veja e
    às vezes corrija o código HTML.

#### Painel Direito

- **Status** O status de publicação deste artigo.
  - *Publicado* O artigo é visível na interface do site.
  - *Não Publicado* O artigo não será visível para visitantes na
    interface do site. Pode ser visível para usuários logados que tenham
    permissão de edição de estado para o artigo.
  - *Arquivado* O artigo não será mais exibido nos itens de menu ou na Lista de Categorias.
  - *Lixeira* O artigo é deletado do site, mas ainda está no banco de dados.
- **Categoria** Selecione a categoria para este artigo.
- **Destaque** Selecione Sim se o artigo será mostrado no item de menu Destaques.
- **Acesso** Selecione o nível de acesso de visualização para este artigo. Os
  níveis de acesso dependem do que foi configurado em Usuários: Níveis de Acesso.
- **Idioma** Selecione o idioma para este artigo. Mantenha o padrão
  'Todos' se você não estiver usando o recurso de multi-idiomas.
- **Tags** Atribua tags a este artigo. Você pode selecionar uma tag de uma
  lista predefinida ou
  inserir uma nova tag digitando o nome no campo e pressionando Enter.
- **Nota** Isso normalmente é para uso do administrador (por exemplo,
  para documentar informações sobre este artigo) e não aparece na
  interface do site.
- **Nota da Versão** Campo opcional para identificar a versão deste
  artigo no Histórico de Versões do artigo.

### Aba Imagens e Links

**Nota:** Esta aba pode ser ocultada nas *Opções do Artigo* por um usuário com
permissões de administrador. Ela permite a exibição de imagens e links em artigos usando
layouts padronizados.

![Aba de edição de imagens e links dos artigos](../../../ptbr/images/articles/articles-edit-images-tab.png)

#### Imagem de Introdução

- **Imagem de Introdução** Clique no botão Selecionar para escolher uma imagem a ser
  exibida em um local fixo no Texto de Introdução deste artigo. Isso
  abrirá uma janela que permite a seleção de uma imagem da pasta de imagens.
- **Descrição da Imagem (Texto Alt)** Defina o atributo alt para esta
  imagem. Algumas palavras descritivas para leitores de tela.
- **Sem Descrição** Marque no caso raro de uma imagem puramente decorativa.
  Observe que se a Descrição da Imagem estiver vazia e a
  caixa de seleção Sem Descrição estiver desmarcada, a imagem não atenderá aos
  critérios de acessibilidade. Se uma descrição da imagem estiver presente,
  esta caixa de seleção não terá efeito.
- **Classe da Imagem** Adicione qualquer classe CSS para estilização personalizada.
  Por exemplo, para posicionamento da imagem, use float-start ou float-end.
- **Legenda** Crie uma legenda para esta imagem.

#### Imagem do Artigo Completo

- **Imagem do Artigo Completo** Clique no botão Selecionar para escolher uma imagem a ser
  exibida em um local fixo no Texto Completo deste artigo.
  Isso abrirá uma janela que permite a seleção de uma imagem da
  pasta de imagens.
- **Descrição da Imagem (Texto Alt)** Defina o atributo alt para esta
  imagem. Algumas palavras descritivas para leitores de tela.
- **Sem Descrição** Marque no caso raro de uma imagem puramente decorativa.
  Observe que se a Descrição da Imagem estiver vazia e a
  caixa de seleção Sem Descrição estiver desmarcada, a imagem não atenderá aos
  critérios de acessibilidade. Se uma descrição da imagem estiver presente,
  esta caixa de seleção não terá efeito.
- **Classe da Imagem** Adicione qualquer classe CSS para estilização personalizada.
  Por exemplo, para posicionamento da imagem, use float-start ou float-end.
- **Legenda** Insira uma legenda opcional para esta imagem.

#### Link A

- **Link A** O URL para o primeiro link a ser exibido em um local fixo
  no texto do artigo. Deve ser um URL completo, não relativo.
  Por exemplo, normalmente começaria com `https:`.
- **Texto do Link A** O texto usado para o Link A. Se estiver em branco, o URL será
  exibido.
- **Janela de Destino do URL** Define o valor padrão para o destino do
  primeiro Link deste artigo. As opções são:
  - *Abrir na janela pai* Abre no navegador principal,
    substituindo o artigo atual do Joomla.
  - *Abrir em nova janela* Abre o link em uma nova janela do navegador.
  - *Abrir em pop-up* Abre o link em uma janela pop-up do navegador (sem
    controles de navegação completos).
  - *Modal* Abre o link em uma janela pop-up modal.

#### Link B, Link C

- Mesmas opções que Link A.

### Aba Opções

**Nota**: Esta aba pode ser ocultada por um usuário com permissões de administrador nas
Opções do Artigo. Trata-se de um conjunto de opções usadas para controlar como este
artigo será exibido na interface do site.

![Aba Opções](../../../ptbr/images/articles/articles-edit-options-tab.png)

#### Layout

- **Layout** Use um layout da visualização de artigo fornecida ou substituições nos templates.
- **Título** Exibir o título do artigo.
- **Títulos Linkados** Exibir o título como um link para o artigo.
- **Tags** Insira tags para este artigo. Selecione tags existentes digitando
  as primeiras letras ou crie novas tags digitando-as
  aqui.
- **Texto de Introdução**
  - *Mostrar* O Texto de Introdução do artigo será exibido em uma página exibindo o
    artigo completo.
  - *Esconder* Apenas a parte do artigo após a quebra de Leia Mais será
    exibida em uma página exibindo o artigo completo.
- **Posição das Informações do Artigo**
  - *Acima* Coloca o bloco de informações do artigo acima do texto.
  - *Abaixo* Coloca o bloco de informações do artigo abaixo do texto.
  - *Dividir* Divide o bloco de informações do artigo em 2 blocos separados.
    Um bloco fica acima e o outro abaixo do texto.
- **Título das Informações do Artigo** Exibe 'Detalhes' acima do bloco de
  informações do artigo.

#### Categoria

- **Categoria** Exibir o Título da Categoria do Artigo.
- **Link da Categoria** Exibir o título como um link para essa Categoria.
- **Categoria Pai** Exibir o Título da Categoria Pai do Artigo.
- **Link da Categoria Pai** Exibir o título como um link para essa Categoria.

#### Associações

- **Associações** Exibir as bandeiras associadas ou o Código do Idioma.
  Apenas para multilinguagem.

#### Autor

- **Autor** Exibir o autor do Artigo.
- **Link para a Página de Contato do Autor** Exibir como um link para um layout de Contato
  para esse autor. Nota: O autor deve estar configurado como um Contato.

#### Data

- **Data de Criação** Exibir a data de criação do Artigo.
- **Data de Modificação** Exibir a data de modificação do Artigo.
- **Data de Publicação** Exibir a data de início da publicação do Artigo.

#### Opções

- **Navegação** Exibir links de navegação, *Anterior* e/ou *Próximo*, quando
  exibindo uma página contendo o artigo completo.
- **Visualizações** Exibir o número de vezes que o artigo foi exibido por um usuário.
- **Links Não Autorizados** Se Sim, o Texto de Introdução para artigos restritos
  será exibido. Clicar no link Leia mais exigirá que os usuários façam login
  para ver o conteúdo completo do artigo.
- **Posicionamento dos Links**
  - *Acima* Os links são exibidos acima do conteúdo.
  - *Abaixo* Os links são exibidos abaixo do conteúdo.
- **Texto de Leia Mais** Personalize o texto que aparece para a palavra padrão
  'Leia mais'.
- **Título da Página do Navegador** Texto para o título da página do navegador a ser usado
  quando o artigo for visualizado com um item de menu não-artigo. Se estiver em branco,
  o título do artigo será usado em vez disso.

### Aba Campos

Esta seção mostra os campos personalizados que estão definidos para este artigo. Estes
são campos que não estão atribuídos a um Grupo de Campos. Cada Grupo de Campos, se definido,
aparecerá como uma aba separada.

![Aba Campos](../../../ptbr/images/articles/articles-edit-fields-tab.png)

### Aba Configurar Tela de Edição

**Nota:** Esta aba pode ser ocultada por um usuário com permissões de administrador nas
Opções do Artigo.

![Aba de configuração da tela de edição](../../../ptbr/images/articles/articles-edit-editor-tab.png)

- **Opções de Publicação** Se Ocultar, a aba Opções de Publicação
  não será exibida no Backend. Isso significa que os usuários do Backend não
  poderão editar os campos desta aba. Esses campos sempre serão
  definidos para seus valores padrão.
- **Opções do Artigo** Se Ocultar, a aba Opções do Artigo
  não será exibida no Backend. Isso significa que os usuários do Backend não
  poderão editar os campos desta aba. Esses campos sempre serão
  definidos para seus valores padrão.
- **Imagens e Links do Administrador** Se Sim, a aba Imagens e Links
  será exibida.
- **Imagens e Links da Interface** Se Sim, a aba Imagens e Links será
  exibida na tela do editor de artigo da interface do site.



## Dicas

- Existem 2 métodos para inserir uma imagem no artigo usando o editor TinyMCE.
  1. A lista suspensa *Conteúdo CMS* fornece acesso à tela de Mídia.
  2. A lista suspensa *Inserir* é um formulário simples que requer a URL da 
    imagem. Ela é usada para imagens externas.
- Um inserto *Leia Mais* economiza espaço em qualquer página de layout em 
  Destaque ou Blog, exibindo apenas a primeira parte de um Artigo. Insertos de
  *Quebra de Página* fornecem navegação em várias páginas para artigos longos.
  Ambos podem ser usados em um único artigo, se desejado. Por exemplo, uma 
  quebra *Leia Mais* pode ser colocada após o primeiro parágrafo e quebras 
  *Quebra de Página* podem ser colocadas após grupos posteriores de parágrafos 
  para criar um artigo de várias páginas. Nenhuma navegação de página seria 
  exibida na página em Destaque ou Blog até que o Usuário selecione o link Leia 
  mais. Nesse momento, o índice do Artigo seria exibido mostrando links para 
  cada página.

