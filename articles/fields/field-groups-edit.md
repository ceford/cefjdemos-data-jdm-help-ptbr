<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group  / Display title: Componente: Editar Grupo de Campos -->

## Descrição

Grupos de Campos são usados para coletar campos relacionados sob uma Aba nomeada em um
formulário de entrada de dados. O Componente: Editar Grupo de Campo é semelhante para todos os componentes
que implementam campos, mas o título da página muda dependendo do contexto: 
Artigos: Editar Grupo de Campo, Contatos: Editar Grupo de Campo ou Usuários: Editar Grupo de
Campo.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Aba Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

* Selecione **Conteúdo → Grupos de Campos** no menu do Administrador. Ou...
* Selecione **Contato → Grupos de Campos** no menu do Administrador. Ou...
* Selecione **Usuários → Grupos de Campos** no menu do Administrador. Então...
  * selecione o botão **Novo** na Barra de Ferramentas para criar um novo campo. Ou...
  * Selecione um **Título** da lista para editar um campo existente.

**Nota:** Há uma lista suspensa que permite a criação de Campos para uma
Categoria e Correio no componente de Contato. Eles exigem alguma
experiência em codificação para preparar substituições adequadas de template.

## Captura de Tela

Este exemplo é uma página de *Artigos: Editar Grupo de Campos*. *Contatos: Editar Grupo de Campos* e *Usuários: Editar Grupo de Campos* são semelhantes.

![artigos editar grupo de campos](../../../ptbr/images/fields/articles-edit-field-group.png)

## Campos do Formulário

- **Título** O Título para este grupo de campos.

### Geral

#### Painel Esquerdo

- **Descrição** Texto que será exibido como uma dica de ferramenta ao pairar 
  sobre a caixa de texto enquanto cria um artigo ou um contato, ou um 
  componente de terceiros que suporte campos personalizados. Este texto não é 
  traduzível. Você não vê esta descrição no Frontend.

#### Painel Direito

- **Status** O status publicado deste grupo de campos.
  - *Publicado* O grupo de campos é visível enquanto edita um artigo ou um 
    contato. E é visível no Frontend.
  - *Não Publicado* O grupo de campos não será visível para os usuários 
    enquanto editam um artigo ou um contato.
  - *Arquivado* O grupo de campos não será mais exibido na edição de um artigo 
    ou um contato. Você pode abri-lo em Grupos de Campos quando definir o filtro 
    para arquivado.
  - *Lixeira* O grupo de campos é deletado, mas ainda está no banco de dados. Ele 
    pode ser deletado permanentemente do banco de dados em Grupos de Campos com a 
    função de Limpar Lixeira.
- **Acesso** Selecione o nível de acesso de visualização para este grupo de campos. Os 
  níveis de acesso dependem do que foi configurado em Usuários: Níveis de Acesso.
- **Idioma** Selecione o idioma para este grupo de campos. Se você não estiver 
  usando o recurso de multi-idiomas do Joomla, mantenha o padrão como *Todos*.
- **Nota** Um campo opcional para fazer suas anotações pessoais para o grupo 
  de campos.

### Opções

- **Exibir Quando Somente Leitura** Se o grupo de campos for somente leitura (talvez 
  o usuário não tenha o nível de acesso) o grupo de campos deve ser exibido ou ocultado.

*Traduzido por openai.com*

