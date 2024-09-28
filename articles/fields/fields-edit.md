<!-- Filename: Help4.x:Fields:_Edit  / Display title: Componente: Campo de Edição -->

## Descrição

A página *Componente: Editar Campo* é semelhante para todos os componentes que implementam
campos, mas o título da página muda dependendo do contexto: *Artigos: Editar Campo*,
*Contatos: Editar Campo* ou *Usuários: Editar Campo*.

A aba **Geral** muda para refletir o tipo de campo que está sendo editado e, uma vez
que um campo foi salvo, seu tipo não pode ser alterado. No entanto, é fácil
excluir campos e criar novos.

### Elementos Comuns

Alguns aspectos desta página são cobertos em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

* Selecione **Conteúdo → Campos** no menu do Administrador. Ou...
* Selecione **Contato → Campos** no menu do Administrador. Ou...
* Selecione **Usuários → Campos** no menu do Administrador. Então...
  * Selecione o botão **Novo** na Barra de Ferramentas para criar um novo campo. Ou...
  * Selecione um **Título** da lista para editar um campo existente.

**Nota:** Há uma lista dropdown que permite a criação de Campos para uma Categoria e Correio no componente de Contato. Eles exigem alguma experiência em codificação para preparar substituições adequadas de template.

## Captura de Tela

![Campo de edição de artigos](../../../ptbr/images/fields/articles-edit-field.png)

## Campos do Formulário

- **Título** O título para este campo.

### Aba Geral

#### Painel Esquerdo

Parâmetros para todos os campos:

- **Tipo** Se você criar um campo, poderá escolher um dos 16 tipos de campo. Quando você salvar o campo, esse tipo será permanente.
- **Nome** O nome será usado para identificar o campo. Deixe esse campo em branco e o Joomla irá preencher com um valor padrão do título.
- **Etiqueta** Use um texto descritivo do campo para a etiqueta do campo. Este texto não é traduzível. Se você não inserir nenhum texto para uma etiqueta, o texto do título também será usado como texto da etiqueta.
- **Descrição** A descrição do campo. Um texto que será exibido como uma dica de ferramenta quando o usuário mover o mouse sobre a caixa de texto enquanto a estiver usando no Backend, criando um artigo, um contato ou um componente de terceiros que suporte campos. Este texto não é traduzível. Você não verá essa descrição no Frontend.
- **Obrigatório** Este é um campo obrigatório? Nesse caso, o campo deve ser preenchido antes de enviar um artigo, um contato ou um componente de terceiros que suporte campos.

#### Painel Direito

- **Status** O status de publicação deste campo.
  - *Publicado* O campo é visível ao editar um artigo ou um contato. E é visível no Frontend.
  - *Não Publicado* O campo não será visível para os usuários ao editar um artigo ou um contato.
  - *Arquivado* O campo não será mais exibido na edição de um artigo ou um contato. Você pode abri-lo em Campos quando definir o filtro para arquivado.
  - *Excluído* O campo está excluído, mas ainda está no banco de dados. Ele pode ser excluído permanentemente do banco de dados em Campos com a função de Esvaziar Lixeira.
- **Grupo de Campos** Você pode atribuir um campo a um grupo de campos.
- **Categoria** Você pode atribuir um campo a uma ou mais categorias. Observe que o padrão *Todos* não inclui artigos *Não categorizados*.
- **Acesso** Selecione o nível de acesso de visualização para este campo. Os níveis de acesso dependem do que foi configurado em *Usuários: Níveis de Acesso*.
- **Idioma** Selecione o idioma para este campo. Se você não estiver usando o recurso multilinguagem do Joomla, mantenha o padrão *Todos*.
- **Nota** Um campo opcional para fazer suas anotações pessoais sobre o campo.

### Aba Opções

![Opções de edição de artigos na aba de campo](../../../ptbr/images/fields/articles-edit-field-options-tab.png)

#### Opções do Formulário

- **Placeholder** Um texto do placeholder que aparecerá dentro do campo como uma dica para o preenchimento. O placeholder está ativo no Backend ao criar um artigo, um contato ou um componente de terceiros que suporte campos. Você não o verá no Frontend.
- **Classe do Campo** Os atributos de classe do campo quando o campo é renderizado. Se for necessário diferentes classes, liste-as com espaços.
- **Classe da Etiqueta (Formulário)** Classe CSS a ser aplicada à etiqueta do campo quando ele estiver em modo de edição (inserindo dados em um campo).
- **Editável em** Em qual parte do site o campo deve ser exibido. No Backend, no Frontend ou em ambos?
- **Atributo Showon** Mostrar ou ocultar condicionalmente o campo dependendo do valor de outros campos. A sintaxe a ser usada aqui, por exemplo:
  `lista-de-itens:valor1[OU]lista-de-itens:valor2`
  - lista-de-itens: O *nome* de um campo já criado no qual este campo dependerá para ser exibido.
  - valor1: O valor necessário para exibir o campo do qual ele depende.
  - `[OU]`: Para criar uma escolha entre vários campos. No exemplo, este campo será exibido quando o campo *lista-de-itens* tiver o valor: *valor1* OU *valor2*
  - `[E]`: Para combinar vários campos. Este campo será exibido apenas quando o campo *lista-de-itens* tiver o valor: *valor1* E *valor2*
  - Você também pode usar o valor *não igual* como em *lista-de-itens!:valor1*. A sintaxe mostrará este campo apenas quando *lista-de-itens* não for igual a *valor1*
  - Para mostrar este campo quando o campo *lista-de-itens* tiver sido selecionado e não tiver um valor vazio, use a sintaxe *lista-de-itens!:* (sem um valor especificado).

**Nota:** Campos de subformulário lidam de maneira diferente com o identificador *nome* de *lista-de-itens*. Se você criar um campo personalizado de Subformulário e adicionar esse campo condicional lá, você precisa usar *campo\[ID\]* em vez de *lista-de-itens*, onde ID é o id do campo *lista-de-itens*. Portanto, o atributo *showon* para este campo condicional que você está criando precisa ser: `campo36:valor1[OU]campo36:valor2` onde 36 é o ID do campo 'Lista de itens'.

#### Opções de Exibição

- **Classe de Exibição** A classe do contêiner do campo na saída.
- **Classe do Valor** A classe do valor do campo na saída.
- **Etiqueta** Mostrar a etiqueta quando o campo for renderizado.
- **Classe da Etiqueta (Saída)** Classe CSS a ser aplicada à etiqueta do campo quando ele for exibido (mostrando a saída de um campo).
- **Exibição Automática** Joomla oferece alguns eventos de conteúdo que são acionados durante o processo de criação de conteúdo. Este é o lugar para definir como os campos devem ser integrados ao conteúdo. Você pode escolher
  - Após o Título
  - Antes do Conteúdo Exibido
  - Após o Conteúdo Exibido
  - Não exibir automaticamente
- **Prefixo** Texto fixo a ser exibido antes de um campo, por exemplo, &pound;.
- **Sufixo** Texto fixo a ser exibido após um campo, por exemplo, &euro;.
- **Layout** Se houver um layout personalizado, ele será selecionado aqui.
- **Exibir Quando Somente-Leitura** Se o campo for somente leitura (talvez o usuário não tenha o nível de acesso), o campo deve ser exibido ou ocultado.

#### Pesquisa Inteligente

- **Índice de Pesquisa** Aviso: Quando *Tornar pesquisável* estiver selecionado, o conteúdo do campo será indexado com as permissões de visualização do item de conteúdo. Isso pode levar à divulgação inesperada de informações.

*Traduzido por openai.com*

