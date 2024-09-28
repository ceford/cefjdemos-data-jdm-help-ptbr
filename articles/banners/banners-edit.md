<!-- Filename: Help4.x:Banners:_Edit  / Display title: Banners: Editar -->

## Descrição

Usado para adicionar ou editar banners que podem ser exibidos no seu site Joomla!
Lembre-se de criar pelo menos um Cliente de Banner e uma Categoria de Banner
antes de criar qualquer Banner.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [O Popup de Histórico de Versão](jdocmanual?article=help/common-elements/edit-version-history).

## Como Acessar

No menu do Administrador:
- Selecione **Componentes → Banners** para ir para a página de lista de Banners.
- Selecione o botão **Novo** na Barra de Ferramentas para criar um novo Banner.
- Selecione um **nome** de Banner na coluna *Nome* para editar um Banner existente.

## Captura de Tela

Um banner pode ser uma imagem clicável ou algum código personalizado. O Tipo de Imagem é exibido na captura de tela abaixo. O tipo personalizado possui a caixa de seleção de imagens substituída por uma área de texto para código.

![Aba de edição de detalhes de banners](../../../ptbr/images/banners/banners-edit-details-tab.png)

## Campos do Formulário

- **Nome** O nome do Banner. Este é o nome que será exibido
  na coluna *Nome* da lista de Banners.
- **Alias** O nome interno do item. Normalmente, você pode deixar este
  campo em branco e o Joomla preencherá um valor padrão derivado do Nome,
  mas em letras minúsculas e com traços em vez de espaços.

## Aba de Detalhes

### Painel Esquerdo

- **Tipo** O tipo de banner a ser exibido. As opções são um arquivo de imagem ou
  código HTML personalizado.
  - **Imagem** Arquivo de imagem a ser exibido para o banner. Clique no botão *Selecionar*
    para procurar e selecionar o arquivo de imagem a ser usado. Utilize a página de Mídia
    para carregar arquivos de imagem do Banner no seu site. Imagens para Banners
    têm que estar no diretório /images/banners/.
    - **Largura** A largura fixa para redimensionar a imagem do banner. Deixe
      este campo vazio se quiser usar a largura real do arquivo de imagem do banner.
    - **Altura** A altura fixa para redimensionar a imagem do banner. Deixe
      este campo vazio se quiser usar a altura real do arquivo de imagem do banner.
    - **Texto Alternativo** Texto a ser exibido no lugar da imagem do banner
      caso a imagem não possa ser exibida.
    - **Texto Alternativo** Texto alternativo para a imagem do Banner.
  - **Personalizado** Selecione Personalizado se quiser inserir um código personalizado para
    seu banner.
    - **Código Personalizado** Use {CLICKURL} e {NAME} para mesclar os valores 'URL de Clique'
      e 'Nome' respectivamente no seu código personalizado. Por exemplo:<br>
      `<a href=`&#34;`{CLICKURL}"><img src=`&#34;`insira URL para a imagem" alt="{NAME}" title="{NAME}"></a>`.
      Outra opção é inserir um código HTML personalizado. Por exemplo:<br>
      `<div class="suaclasse"><a href=`&#34;`https://seudominio.com"><img src=`&#34;`caminhodasuimagem"></a></div>`
- **URL de Clique** A URL para navegar quando o Usuário clica no
  Banner.
- **Descrição** Insira uma descrição para o Banner.

### Painel Direito

- **Status** O status de publicação do item.
- **Fixado** Se o Banner está ou não *fixado*. Se
  um ou mais Banners em uma Categoria forem designados como *fixos*, eles terão
  prioridade sobre Banners que não são fixos.
    - Por exemplo, se dois Banners em uma Categoria estão fixados e um terceiro Banner
    não está fixado, o terceiro Banner não será exibido se a configuração do módulo de exibição
    do Banner estiver como *Fixado, Aleatório* ou *Fixado, Ordem*. Somente os
    dois Banners fixados serão exibidos. Se os banners fixados tiverem um número fixo
    de impressões, uma vez que essas impressões se esgotem, os banners fixados não
    serão mais exibidos, e os banners não fixados começarão
    a ser exibidos automaticamente.
- **Idioma** Idioma do item.
- **Nota da Versão** Campo opcional para identificar esta versão do item
  na janela de Histórico de Versão do item.

### Aba de Detalhes do Banner

![Aba de detalhes da edição de banners](../../../ptbr/images/banners/banners-edit-banner-details-tab.png)

- **Máx. Impressões** O número de Impressões adquiridas para este
  Banner. Impressões são o número de vezes que um Banner será exibido
  em uma página. Marque a caixa de seleção 'Ilimitado' se for permitido um número ilimitado de
  Impressões.
- **Total de Impressões** O número de vezes que este Banner foi
  exibido em uma página web para um usuário. Nenhuma entrada é permitida. Você pode redefinir
  este número para 0 pressionando o botão 'Redefinir Impressões'.
- **Total de Cliques** O número de vezes que este Banner foi clicado. Nenhuma
  entrada é permitida. Você pode redefinir este número para 0 pressionando o
  botão *Redefinir cliques*.
- **Cliente** O Cliente para este Banner. Selecione um na lista suspensa
  de Clientes existentes.
- **Tipo de Compra:** O tipo de compra do banner. Isto é usado para
  indicar como o cliente do banner adquiriu o tempo de exibição para o
  banner.
- **Rastrear Impressões** Se deve ou não rastrear o número de vezes que
  o banner é exibido para os visitantes do site.
- **Rastrear Cliques** Se deve ou não rastrear o número de vezes que
  o banner é clicado pelos visitantes do site.

## Dicas

- Os banners são colocados em páginas específicas ao adicionar Módulos do tipo *Banners* usando a lista de Módulos.
- Se você tem uma série de Banners que gostaria de exibir em uma ou mais páginas de forma aleatória:
  1. Crie os Banners que deseja incluir, certificando-se de que eles tenham o mesmo Cliente e Categoria.
  2. Crie um Módulo de Banner para esse Cliente e Categoria e, na Atribuição de Menu, escolha as Seleções de Menu para o módulo exibir.
  3. No Módulo de Banner, configure o valor *Randomise* para *Sticky, Randomise*.

  Com essas configurações, os diferentes Banners para esse Cliente e Categoria serão exibidos nas páginas selecionadas de forma aleatória.

*Traduzido por openai.com*

