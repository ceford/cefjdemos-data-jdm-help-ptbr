<!-- Filename: Help4.x:Articles:_Edit / Display title:   Artigos: Editar -->

## Descrição

Esta tela é usada para adicionar um novo artigo ou editar um artigo
existente, geralmente usando um editor Wysiwyg. O editor padrão é o
TinyMCE, mas se outros editores estiverem instalados, o editor padrão
pode ser definido como qualquer outro para o site como um todo ou para
usuários individuais.

A maioria dos parâmetros tem padrões adequados, mas você pode querer
definir uma categoria específica ou fornecer metadados específicos para
o artigo.

## Tutorials

[Adding an Image to an Article](jdocmanual?article=user/articles/adding-an-image-to-an-article "Adding an Image to an Article")

## Como acessar
Selecione **Conteúdo → Artigos**

Para adicionar um artigo:

- clique no botão **Novo** na barra das ferramentas

Para editar um artigo:

- selecione um **Título** a partir da lista

## Captura da tela

![Articles edit screenshot](../../../ptbr/images/articles/articles-edit-content-tab.png "Articles edit")

## Campos do formulário

- **Título**. O título para este artigo.
- **Alias**. O nome interno deste artigo. Normalmente, você pode deixar
  isso em branco e o Joomla! preencherá com um valor padrão em letras
  minúsculas, e com hífens em vez de espaços, fundamentado no título.
  Aprender mais.

### Conteúdo guia

#### Painel esquerdo

- **Texto do artigo**. É aqui que você insere o conteúdo do artigo. O
  Joomla! inclui 3 editores, o padrão (Editor - TinyMCE
  é mostrado aqui.

  A lista suspensa do conteúdo no S.G.C. (CMS) fornece acesso aos links
  para artigos, contatos, campos, mídia, menus ou módulos. Aprender
  mais.
- **Alternar editor**. O botão "Alternar editor" é mostrado abaixo da
  janela para edição. Este botão permite alternar entre o TinyMCE e

#### Painel direito

- **Estado**. O estado da publicação deste artigo.
  - Publicado: O artigo torna-se visível no site (frontend).
  - Despublicado: O artigo não fica visível para os convidados no site
    (frontend). Ele pode ser visível para usuários que tenham iniciado
    suas sessões e que tenham [permissão para edição do
    estado](#permissions) no artigo.
  - Arquivado: O artigo não será mais mostrado nos itens dos menus que
    são blogs para categoria(s) ou listas para categoria(s).
  - Lixeira: O artigo é excluído do site, mas ainda fica no banco de
    dados.
- **Categoria**. Seleciona a categoria para este artigo.
- **Destacado**. Selecione "Sim" se o artigo deve ser mostrado no item
  dos menus para destacados.
- **Acesso**. Seleciona o nível do acesso para visualização para este
  artigo. Os níveis dos acessos dependem do que foi configurado em

- **Linguagem**. Seleciona a linguagem para este artigo. Mantenha o
  padrão "Todas" se você não estiver usando o recurso multilíngue.
- **Tags**. Atribui tags a este artigo. Você pode selecionar uma tag a
  partir de uma lista pré-definida< ou inserir uma nova tag digitando o nome 
  no campo e pressionando enter.
- **Nota**. Isso é normalmente para uso administrativo (por exemplo,
  para documentar informações sobre este artigo) e não aparece no site
  (frontend).
- **Nota da versão**. Campo opcional para identificar a versão deste
  artigo no

### Imagens e links guia

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em
Esta seção permite mostrar imagens e links em seus artigos usando
disposições padronizadas.

![Articles edit images and links tab](../../../ptbr/images/articles/articles-edit-images-tab.png "Articles edit images and links tab")

#### Imagem da introdução

- **Imagem da introdução**. Acione o (clique no) botão "Selecionar" para
  selecionar uma imagem que será mostrada em um local fixo no texto da
  introdução deste artigo. Isso abrirá uma janela que permite selecionar
  uma imagem da sua pasta de imagens.
- **Descrição da imagem (texto alternativo)**. Defina o atributo alt
  para esta imagem. Algumas palavras descritivas para os leitores de
  tela.
- **Nenhuma descrição**. Marque na rara instância de uma imagem
  puramente decorativa. Observe que, se a descrição da imagem estiver
  vazia e a caixa de seleção "Sem descrição" estiver desmarcada, a
  imagem não atenderá aos critérios de acessibilidade. Se uma descrição
  de imagem estiver presente, esta caixa de seleção não terá efeito.
- **Classe da imagem**. Você pode adicionar qualquer classe CSS para
  suas próprias ideias de estilo. Para a posição da imagem, use, por
  exemplo, float-start e float-end.
- **Legenda**. Cria uma legenda para esta imagem.

#### Imagem do artigo completo

- **Imagem do artigo completo**. Acione o (clique no) botão "Selecionar"
  para selecionar uma imagem que será mostrada em um local fixo no texto
  completo deste artigo. Isso abrirá uma janela que permite selecionar
  uma imagem da sua pasta de imagens.
- **Descrição da imagem (texto alternativo)**. Define o atributo alt
  para esta imagem. Algumas palavras descritivas para os leitores de
  tela.
- **Nenhuma descrição**. Marque na rara instância de uma imagem
  puramente decorativa. Observe que, se a descrição da imagem estiver
  vazia e a caixa de seleção "Sem descrição" estiver desmarcada, a
  imagem não atenderá aos critérios de acessibilidade. Se uma descrição
  de imagem estiver presente, esta caixa de seleção não terá efeito.
- **Classe da imagem**. Você pode adicionar qualquer classe CSS para
  suas próprias ideias de estilo. Para a posição da imagem, use, por
  exemplo, float-start e float-end.
- **Legenda**. Insira uma legenda opcional para esta imagem.

#### Link A

- **Link A**. O URL do primeiro link a ser mostrado em um local fixo no
  texto do artigo. Este deve ser um URL completo, não relativo. Por
  exemplo, normalmente começaria com `https:`.
- **Texto do link A**. O texto usado para o "Link A". Se estiver em
  branco, o URL será mostrado.
- **Janela de destino do URL**. Define o valor padrão para o destino do
  primeiro link neste artigo. As opções são:
  - Abrir na janela principal: Abre na janela principal do navegador,
    substituindo o artigo atual do Joomla!.
  - Abrir em uma nova janela: Abre o link em uma nova janela do
    navegador.
  - Abrir em pop-up: Abre o link em uma janela pop-up do navegador (sem
    os controles para navegação completos).
  - Modal: Abre o link em uma janela pop-up modal.
- **Link B**, **Link C**: Mesmas opções do "Link A."

### Opções guia

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em
Este é um conjunto de opções que você pode usar para controlar como este
artigo será mostrado no site (frontend).

![Options tab](../../../ptbr/images/articles/articles-edit-options-tab.png "Options Tab")

#### Disposição

- **Disposição**. Usa uma disposição da exibição do artigo fornecida ou
  das <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Templates:_Customize/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Templates: Customize/pt-br (page does not exist)">substituições
  nos temas</a>.
- **Título**. Mostra o título do artigo.
- **Títulos vinculados**. Mostra o título como um link para o artigo.
- **Tags**. Insere as tags para este artigo. Selecione as tags
  existentes inserindo as primeiras letras ou crie novas tags
  inserindo-as aqui. <a
  href="https://docs.joomla.org/index.php?title=J4.x:How_To_Use_Content_Tags_in_Joomla/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="J4.x:How To Use Content Tags in Joomla/pt-br (page does not exist)">Aprender
  mais</a>.
- **Texto da introdução**.
  - Mostrar: O texto da introdução do artigo será mostrado quando você
    detalhar o artigo.
  - Ocultar: Apenas a parte do artigo após a pausa "Leia mais" será
    mostrada.
- **Posição das informações do artigo**.
  - Acima: Coloca o bloco de informações do artigo acima do texto.
  - Em baixo: Coloca o bloco de informações do artigo em baixo do texto.
  - Dividido: Divide o bloco de informações do artigo em 2 blocos
    separados. Um bloco está acima e o outro está abaixo do texto.
- **Título das Informações do artigo**. Mostra "Detalhes" na parte
  superior do bloco de informações do artigo.

#### Categoria

- **Categoria**. Mostra o título da categoria do artigo.
- **Link da categoria**. Mostra o título como um link para aquela
  categoria.
- **Categoria parental**. Mostra o título da categoria parental do
  artigo.
- **Link da categoria parental**. Mostra o título como um link para
  aquela categoria.

#### Associações

- **Associações**. Mostra as bandeiras ou os códigos das linguagens
  associadas.

#### Autor

- **Autor**. Mostra o autor do artigo.
- **Link para a página de contato do autor**. Mostra isso como um link
  para uma disposição de contato desse autor.Nota: O autor deve ser <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Contacts/pt-br&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Contacts/pt-br (page does not exist)">configurado como um
  contato</a>.

#### Data

- **Data da criação**. Mostra a data da criação do artigo.
- **Data da modificação**. Mostra a data da modificação do artigo.
- **Data da publicação**. Mostra a data do início da publicação do
  artigo.

#### Opções

- **Navigação**. Mostra um link para navegação "Anterior" ou "Próximo"
  ao detalhar o artigo.
- **Acionamentos (acessos, cliques)**. Mostra a quantidade de vezes que
  o artigo foi mostrado por um usuário.
- **Links não autorizados**. Se definido como "Sim", o textos
  introdutórios dos artigos restritos serão mostrados. Acionar o (clicar
  no) link "Leia mais" exigirá que os usuários iniciem uma sessão para
  visualizar o conteúdo completo do artigo.
- **Posicionamento dos links.**
  - Acima: Os links são mostrados acima do conteúdo.
  - Em baixo: Os links são mostrados abaixo do conteúdo.
- **Texto "Ler mais"**. Personaliza o texto que é mostrado para o texto
  padrão "Ler mais".
- **Título da página no navegador**. Texto para o título da página no
  navegador que será usado quando o artigo for visualizado com um item
  dos menus não relacionado ao artigo. Se estiver em branco (vazio), o
  título do artigo será usado.

### Campos guia

Esta seção mostra os campos personalizados que foram definidos para este artigo.

![Fields tab](../../../ptbr/images/articles/articles-edit-fields-tab.png "Filds Tab")

### Schema tab

![Schema tab](../../../ptbr/images/articles/articles-edit-schema-tab.png "Schema Tab")

The schema mechanism allows you to enter metadata for individual articles,
choosing from the following schema types:

* None
* Article
* BlogPosting
* Book
* Event
* JobPosting
* Organisation
* Person
* Recipe
* Custom

Each is a plugin which can disable or enable as required. More schmema types
my be added later or available from third party sources.

### Publicado guia

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas no Esta seção permite que você insira parâmetros e
Metadados para este artigo.

![Publishing tab](../../../ptbr/images/articles/articles-edit-publishing-tab.png "Publishing Tab")

#### Publicação

- **Início da publicação**. Data e hora para iniciar a publicação.
  Insira o artigo com antecedência e, em seguida, publique-o
  automaticamente em um momento futuro.
- **Término da publicação**. Data e hora para terminar a publicação. O
  artigo é alterado automaticamente para o estado "Despublicado"
  posteriormente.
- **Início como destacado**. Data e hora para iniciar o estado como
  destacado. Insira o artigo com antecedência e, em seguida, apresente-o
  automaticamente em um momento futuro.
- **Término como destacado**. Data e hora para terminar o estado como
  destacado. O artigo é alterado automaticamente para o estado "Não
  destacado" em um momento futuro.
- **Data da criação**. A data no momento em que o artigo foi criado.
  Insira uma data e hora diferentes ou acione o (clique no) ícone do
  calendário para encontrar a data desejada.
- **Criado por**. Nome do usuário que criou este artigo. O padrão será o
  usuário conectado no momento. Se você quiser alterar isso para um
  usuário diferente, acione o (clique no) botão "Selecionar usuário".
- **Criado pelo alias**. Insira um alias (pseudônimo) para o autor deste
  artigo. Isso permite que você mostre um nome de autor diferente.
- **Data da modificação**. Data da última modificação.
- **Modificado por**. Nome de usuário que realizou a última modificação.
- **Revisão**. Quantidade de revisões para este artigo.
- **Acionamentos (acessos, cliques)**. A quantidade de vezes que este
  artigo foi visualizado.
- **ID**. Um número de identificação exclusivo para este artigo, você
  não pode alterar esse número. Ao criar um novo artigo, este campo
  mostra "0" até que você salve a nova entrada.

#### Metadados

- **Meta descrição**. Um parágrafo para ser usado como a descrição da
  página.
- **Palavras-chaves**. Entrada para palavras-chaves. <a
  href="https://docs.joomla.org/index.php?title=Using_Keywords/pt-br&amp;action=edit&amp;redlink=1"
  class="new" title="Using Keywords/pt-br (page does not exist)">Aprender
  mais</a>.
- **Robôs**. As instruções para os "robôs' da web que navegam nesta
  página. Defina "Usar global" nas
- **Autor**. Entrada para um nome de autor nos metadados.
- **Direitos do conteúdo**. Descreve quais direitos os outros têm para
  usar este conteúdo.

### Associações guia

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em A aba (guia) é mostrada apenas em

![Associations tab](../../../ptbr/images/articles/articles-edit-associations-tab.png "Associations Tab")

### Configurar a tela para edição guia

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em

![Configure edit screen tab](../../../ptbr/images/articles/articles-edit-editor-tab.png "Configure edit screen Tab")

- **Opções da publicação**. Se configurado para "Ocultar", a [aba (guia)
  "Opções da publicação"
  não aparecerá na área administrativa (backend). Isso significa que os
  usuários da área administrativa (backend) não poderão editar os campos
  nesta aba (guia). Esses campos sempre serão definidos com seus valores
  padrões.
- **Opções do artigo**. Se configurado para "Ocultar", a aba (guia)
  "Opções do artigo"
  não aparecerá na área administrativa (backend). Isso significa que os
  usuários da área administrativa (backend) não poderão editar os campos
  nesta aba (guia). Esses campos sempre serão definidos com seus valores
  padrões.
- **Imagens e links na administração (backend)**. Se configurado como
  "Sim", a aba (guia) "Imagens e links" será mostrada.
- **Imagens e links no site (frontend)**. Se configurado como "Sim", a
  aba (guia) "Imagens e links" será mostrada na tela do editor do artigo
  no site (frontend).

### Permissões guia

É aqui que você pode inserir as permissões para este artigo.

**Nota**: Isso pode ser ocultado por um usuário com permissões
administrativas em

![Permissions tab](../../../ptbr/images/articles/articles-edit-permissions-tab.png "Permissions Tab")

Para alterar as permissões deste artigo, faça o seguinte.

1.  Selecione o **grupo** acionando o (clicando em) seu título
    localizado à esquerda.
2.  Encontre a **ação** desejada.
    - **Excluir**. Os usuários podem excluir este artigo.
    - **Editar**. Os usuários podem editar este artigo.
    - **Editar estado**. O usuário pode alterar o estado da publicação e
      as informações relacionadas a este artigo.
3.  Selecione a permissão desejada para a ação que deseja alterar.
    - **Herdado**. Herdado para usuários neste grupo a partir das
      configurações
      globais,
      Opções de
      artigos,
      ou da
    - **Permitido**. Permitido para os usuários neste grupo.Nota: Se
      esta ação for negada em um dos níveis mais altos, a permissão
      permitida aqui não terá efeito. Uma configuração negada não pode
      ser substituída.
    - **Negado**. Negado para os usuários neste grupo.
4.  Acione (clique em) **Salvar** na **barra das ferramentas** na parte
    superior. Quando a tela for atualizada, a coluna "Configuração
    calculada" mostrará a permissão efetiva para este grupo e ação.

## Barra das ferramentas

No topo da página você verá a barra das ferramentas mostrada na [captura
de tela](#screenshot) acima.

- **Salvar**. Salva o artigo e permanece na tela atual.
- **Salvar e fechar**. Salva o artigo e fecha a tela atual.
  - **Salvar e novo**. Salva o artigo e mantém a tela de edição aberta e
    pronta para criar outro artigo.
  - **Salvar no menu**. Salva o artigo em um item dos menus e abre a
    tela do item dos menus.
  - **Salvar como cópia**. Salva suas alterações em uma cópia do artigo
    atual. Não afeta o artigo atual.
- **Fechar**. Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que você possa ter feito.
- **Versões**. Abre a janela "Histórico das versõe do artigo" para
  mostrar as versões anteriores deste artigo. Isso permite que você
  visualize as versões mais antigas deste artigo e, se desejar, restaure
  a partir de uma das versões mais antigas.
- **Prévia**. Abre uma caixa de diálogo modal mostrando uma visualização
  deste artigo no site. Requer sessões
  compartilhadas
  ou uma sessão iniciada no site (front-end).
- **Verificação de acessibilidade**. Abre uma janela que mostra os
  resultados da verificação de acessibilidade do artigo.
- **Associações**. Com uma linguagem específica definida para um artigo,
  permite a edição lado a lado em outra linguagem. Este ícone é mostrado
  apenas em
- **Alternar ajuda incorporada**. Mostra o texto de ajuda em baixo de
  algumas opções.
- **Ajuda**. Abre esta tela de ajuda.

## Dicas rápidas

- Existem 2 métodos para inserir uma imagem no artigo usando o editor
  TinyMCE.
  1.  A lista suspensa do conteúdo do
      S.G.C.
      fornece acesso à tela de
      mídia
      que permite procurar arquivos de imagens e fazer o envio
      (carregamento, upload) das mesmas.
  2.  A lista suspensa "Inserir" é um formulário simples para o qual
      você precisa saber o URL da imagem. É usado para imagens externas.
- As quebras "Ler
  mais"
  permitem que você economize espaço na página inicial ou em qualquer
  página com disposição para blogs mostrando apenas a primeira parte de
  um artigo. A quebras de
  páginas
  permitem que você forneça navegação em várias páginas para artigos
  longos. Você pode usar ambos em um artigo, se desejar.Por exemplo,
  você pode colocar uma quebra "Ler mais" após o primeiro parágrafo de
  um artigo de várias páginas e ter quebras de página após cada página.
  Nenhuma navegação de página seria mostrada na página inicial até que o
  usuário selecionasse o link "Ler mais". Naquela época, o sumário do
  artigo mostrava links para todas as páginas.
