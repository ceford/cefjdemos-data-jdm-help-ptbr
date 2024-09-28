<!-- Filename: Help4.x:Menus  / Display title: Menus -->

## Descrição

Os menus permitem que um usuário navegue pelo site. Um menu é um objeto que contém um ou mais itens de menu. Cada item de menu aponta para uma página lógica no site. Um módulo de menu é necessário para colocar o menu na página. Um menu pode ter mais de um módulo. Por exemplo, um módulo pode mostrar apenas os itens do primeiro nível do menu e um segundo módulo pode mostrar os itens do menu de nível 2.

A página *Menus* fornece uma visão geral dos menus disponíveis em um site Joomla. Isso inclui os detalhes do número de itens publicados, não publicados e excluídos de cada menu individual, e os nomes dos módulos vinculados.

O processo para adicionar um menu ao site normalmente é o seguinte:

1. Criar um novo menu (usando esta página).
2. Criar um ou mais novos itens de menu para o menu. Cada item de menu terá um tipo específico de item de menu.
3. Criar um ou mais módulos de menu para exibir o menu no site.
    - Selecionar os itens de menu (páginas) que irão exibir o módulo.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos das Colunas da Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens da Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação da Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como Acessar

- Selecione **Menus → Gerenciar** no menu do Administrador.

## Captura de Tela

![lista de menus](../../../ptbr/images/menus/menus-list.png)

## Cabeçalhos das Colunas

- **Título** O nome do menu.
- **Items do Menu** Um link para os itens do menu.
- **\# Publicados** Número de itens do menu publicados neste menu.
- **\# Não Publicados** Número de itens do menu não publicados neste menu.
- **\# Excluídos** Número de itens do menu excluídos neste menu.
- **Módulos Vinculados** Uma lista suspensa mostra o nome, nível de acesso e posição do template
  de qualquer módulo de menu associado ao menu.

## Dicas
- Os botões numerados levam a uma lista filtrada dos itens do menu para esse menu.
- Um menu deve ter um título descritivo curto, adequado para uso em listas e 
  listas suspensas.
- A *Descrição* é uma lembrança útil do propósito pelo qual o menu 
  foi criado.
- Se um menu não tiver módulos associados, o botão da coluna *Módulos vinculados* 
  é um link para um diálogo modal *Adicionar um módulo para este menu*.
- Se você excluir um menu existente, não se esqueça de que todos os itens do menu 
  do respectivo menu também serão excluídos. Há uma mensagem de aviso:

  **Tem certeza de que deseja excluir esses menus? Confirmar excluirá os 
  tipos de menu selecionados, todos os itens de menu e os módulos de menu associados.**
- O Menu Principal tem o item de menu padrão do site. Ele **não deve ser 
  excluído**! O item de menu padrão define a página que é exibida ao 
  visitar o URL do domínio do site, como `www.example.com`. O site não 
  funcionará se ele for excluído. Geralmente, é o item de menu *Home*, mas ele pode ser 
  definido para qualquer item de menu, incluindo um item de menu em um menu oculto. Se o item de menu padrão for alterado, certifique-se de que esse item de menu também não seja excluído!

*Traduzido por openai.com*

