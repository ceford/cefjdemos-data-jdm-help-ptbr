<!-- Filename: Help4.x:Tags:_New_or_Edit  / Display title: Tags: Nova ou Editar -->

## Descrição

A página *Tags: Nova ou Editar* é usada para adicionar ou editar tags que podem ser usadas para exibir o conteúdo do site pelo nome da tag.

### Elementos Comuns

Alguns aspectos desta página estão cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como Acessar

- Selecione **Componentes → Tags** no menu do Administrador. Em seguida,
  - Selecione o botão '**Novo'** na Barra de Ferramentas para criar uma nova Tag.
  - Selecione o Título de uma Tag na coluna **Título** da lista para editar
    uma tag existente.

## Captura de Tela

![tags edit tag details tab](../../../ptbr/images/tags/tags-edit-tag-details-tab.png)

## Campos de Formulário

- **Título** O Nome deste item. Este campo é obrigatório.
- **Alias** O nome interno do item. Normalmente, você pode deixar este
  campo em branco e o Joomla preencherá um valor padrão com o Título em minúsculas e
  com hifens em vez de espaços.

### Aba de Detalhes da Tag

#### Painel esquerdo

- **Descrição** Informe o propósito desta tag.

#### Painel direito

- **Principal** O item (categoria, item de menu, etc.) que é o
  pai do item que está sendo editado.
- **Status** O status de publicação do item.
- **Acesso** O Nível de Acesso de visualização para este item.
- **Idioma** Idioma do item.
- **Nota** Isso é normalmente para uso do administrador do site (por
  exemplo, para documentar informações sobre este item) e não aparece no
  Frontend do site.
- **Nota da Versão** Campo opcional para identificar esta versão do item
  na janela de Histórico de Versões do item.

### Aba de Opções

![tags edit tag options tab](../../../ptbr/images/tags/tags-edit-options-tab.png)

#### Painel de Opções

- **Layout** Use um layout da visão do componente fornecido ou substituições
  nos templates.
- **Classe CSS para link da tag** Adicione classes CSS específicas para o link da tag.
  Se vazio, *label label-info* será adicionado pelo layout padrão da tag.

#### Painéis de Imagens

- **Imagem de Destaque** A imagem que será exibida como parte da lista.
- **Float** Atributo float para a imagem.
- **Alt** Texto alternativo para a imagem.
- **Legenda** A legenda para a imagem.
- **Imagem Completa** Uma imagem que será exibida na visualização única da tag.

### Aba de Publicação

![tags edit tag publishing tab](../../../ptbr/images/tags/tags-edit-publishing-tab.png)

#### Painel de Publicação

- **Data de Criação** Data em que o item (Artigo, Categoria, etc.) foi criado.
- **Criado Por** Nome do Usuário do Joomla que criou este item. Este
  campo por padrão é preenchido com o usuário que está atualmente logado. Se você quiser mudar
  para um usuário diferente, clique no botão Selecionar Usuário para selecionar um
  usuário diferente.
- **Criado por Alias** Este campo opcional permite que você insira um
  alias para este Autor deste Artigo. Isso permite exibir um
  nome de Autor diferente para este Artigo.
- **Data de Modificação** Data da última modificação.
- **Modificado Por** Nome de usuário que realizou a última modificação.
- **Revisão** ...
- **Visualizações** O número de vezes que um item foi visualizado.
- **ID** Este é um número de identificação único para este item, atribuído
  automaticamente pelo Joomla. Ele é usado para identificar o item internamente,
  e você não pode mudar este número. Ao criar um novo item, este
  campo exibe "0" até que você salve a nova entrada, momento em que um novo
  ID é atribuído a ele.

#### Painel de Metadados

- **Meta Descrição** Um parágrafo opcional para ser usado como a
  descrição da página na saída HTML. Isso geralmente
  é exibido nos resultados dos motores de busca. Se inserido, isso cria um
  elemento meta HTML com um atributo name `<description>` e um atributo content
  igual ao texto inserido.
- **Palavras-chave** Entrada opcional para palavras-chave. Devem ser inseridas separadas
  por vírgulas (por exemplo: gatos, cães, animais de estimação) e podem ser inseridas em
  maiúsculas ou minúsculas. (Por exemplo: *GATOS* corresponderá a *gatos* ou
  *Gatos*). As palavras-chave podem ser usadas de várias maneiras:
  1.  Para ajudar os Motores de Busca e outros sistemas a classificar o conteúdo do
      Artigo.
  2.  Em combinação com tags de Banner, para exibir Banners específicos com base
      no conteúdo do Artigo. Por exemplo, suponha que você tenha um Banner com
      um anúncio de produtos para cães e outro Banner com produtos para gatos. Você
      pode ter seu Banner de cães exibido quando um Usuário estiver visualizando um
      Artigo relacionado a cães e seu Banner de gatos exibido para um Artigo relacionado
      a gatos. Para isso, você:
      - Adicione as palavras-chave "cão" e "gato" aos Artigos apropriados.
      - Adicione as Tags "cão" e "gato" aos Banners apropriados em
        Banners: Editar.
      - Defina o parâmetro do módulo de Banner 'Pesquisar por Tags' como "Sim" na
        lista de Módulos do Site: Banners.
  3.  Para artigos apenas, em combinação com o módulo Artigos - Relacionados,
      para exibir Artigos que compartilham pelo menos uma palavra-chave em comum. Por
      exemplo, se o Artigo atual exibido tiver as palavras-chave "gatos,
      cães, macacos", quaisquer outros Artigos com pelo menos uma dessas
      palavras-chave aparecerão no módulo 'Artigos - Relacionados'.
- **Autor** Entrada opcional para um nome de Autor dentro dos metadados. Se
  inserido, isso cria um elemento meta HTML com o atributo name
  'author' e o atributo content conforme inserido aqui.
- **Robôs** As instruções para os 'robôs' da web que acessam esta
  página.
  - *index, follow* Indexar esta página e seguir os links nela contidos.
  - *noindex, follow* Não indexar esta página, mas seguir os
    links nela contidos. Por exemplo, você pode fazer isso para uma página de mapa do site
    onde você quer que os links sejam indexados, mas não deseja que esta
    página apareça em motores de busca.
  - *index, nofollow* Indexar esta página, mas não seguir nenhum link nela contidos. Por exemplo, você pode querer fazer isso para um calendário de eventos, onde você quer que a página apareça em motores de busca, mas não deseja indexar cada evento.
  - *noindex, nofollow* Não indexar esta página nem seguir nenhum link nela contidos.
  - *Usar Global* Definido na Configuração Global: Configurações de Metadados.

*Traduzido por openai.com*

