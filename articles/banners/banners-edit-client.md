<!-- Filename: Help4.x:Banners:_New_or_Edit_Client  / Display title: Banners: Editar Cliente -->

## Descrição

O formulário Banners: Editar Cliente é usado para inserir ou alterar dados do Cliente do Banner. Pelo menos um Cliente do Banner é necessário antes que um Banner possa ser criado.

### Elementos Comuns

Alguns aspectos desta página são cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [O Pop-up do Histórico de Versões](jdocmanual?article=help/common-elements/edit-version-history).

## Como Acessar

- Selecione **Componentes → Banners → Clientes** no menu do Administrador.
  - Para criar um novo Cliente, selecione o botão **Novo** na Barra de Ferramentas.
  - Para editar um Cliente existente, selecione o **nome** na coluna Cliente.

## Captura de tela

![Edição de detalhes do cliente nos banners](../../../ptbr/images/banners/banners-edit-client-details-tab.png)

## Campos do Formulário

- **Nome** O nome deste cliente.

### Aba de Detalhes

- **Nome do Contato** O nome da pessoa de contato para este cliente.
- **E-mail do Contato** O endereço de e-mail do cliente do banner.
- **Tipo de Compra** O tipo de compra do banner. Isto é usado para
  indicar como o cliente do banner adquiriu o tempo de exibição para o
  banner - mensal, anual, etc.
- **Rastrear Impressões** Se deve ou não rastrear o número de vezes que o
  banner é exibido aos visitantes do site.
- **Rastrear Cliques** Se deve ou não rastrear o número de vezes que o
  banner é clicado pelos visitantes do site.
- **Informações Adicionais** Insira qualquer informação extra que você
  queira salvar para este cliente.
- **Status** Status de publicação do item. Os valores possíveis são:
  - *Publicado*: O item está publicado. Este é o único estado que
    permitirá que os usuários regulares do site vejam este item.
  - *Não Publicado*: O item não está publicado.
  - *Arquivado*: O item foi arquivado.
  - *Na Lixeira*: O item foi enviado para a Lixeira.
- **Nota da Versão** Campo opcional para identificar esta versão do item
  na janela de Histórico de Versões do item.

### Aba de Metadados

![Aba de Metadados de Edição do Cliente de Banners](../../../ptbr/images/banners/banners-edit-client-metadata-tab.png)

- **Palavras-Chave** Entrada opcional para palavras-chave. Devem ser
  inseridas separadas por vírgulas (por exemplo, "gatos, cães, pets") e
  podem ser inseridas em letras maiúsculas ou minúsculas. (Por exemplo,
  "GATOS" corresponderá a "gatos" ou "Gatos"). As palavras-chave podem
  ser usadas de várias maneiras:
  1.  Para ajudar os mecanismos de busca e outros sistemas a classificarem
      o conteúdo do Artigo.
  2.  Em combinação com tags de Banner, para exibir Banners específicos
      com base no conteúdo do Artigo. Por exemplo, digamos que você tenha
      um Banner com um anúncio de produtos para cães e outro Banner para
      produtos para gatos. Você pode fazer o Banner de cães ser exibido 
      quando um Usuário estiver visualizando um Artigo relacionado a cães
      e fazer o Banner de gatos ser exibido para um Artigo relacionado a
      gatos. Para fazer isso, você deve:
      - Adicionar as palavras-chave "cão" e "gato" aos Artigos
        apropriados.
      - Adicionar as Tags "cão" e "gato" aos Banners apropriados em
        Banners: Editar.
      - Definir o Parâmetro do módulo de Banner 'Pesquisar por Tags' como
        "Sim" na lista de Módulos do Site: Banners.
  3.  Apenas para artigos, em combinação com o módulo Artigos - Relacionados,
      para exibir Artigos que compartilhem ao menos uma palavra-chave em
      comum. Por exemplo, se o Artigo atual exibido tiver as palavras-chave
      "gatos, cães, macacos", quaisquer outros Artigos com pelo menos uma
      dessas palavras-chave serão mostrados no módulo 'Artigos - Relacionados'.
- **Usar Prefixo Próprio** Se deve ou não usar o prefixo do banner ou
  do cliente. Selecione *Não* se você deseja usar o prefixo do cliente
  do banner.
- **Prefixo da Palavra-Chave Meta** Ao corresponder palavras-chave meta,
  procure apenas palavras-chave meta com esses prefixos opcionais. Isso
  melhora o desempenho.

*Traduzido por openai.com*

