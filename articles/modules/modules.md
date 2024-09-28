<!-- Filename: Help6.x:Modules  / Display title: Módulos -->

## Descrição

Módulos são extensões leves e flexíveis usadas para renderizar trechos de informação em caixas dispostas em torno de um componente em uma página. Um exemplo bem conhecido é o módulo *Login*. Os módulos são atribuídos por item de menu, então você pode decidir mostrar ou ocultar um módulo dependendo de qual página o usuário está visualizando no momento.

Alguns módulos são vinculados a componentes. Por exemplo, o módulo *Últimas Notícias* está vinculado ao componente de conteúdo para exibir links para os artigos mais novos. Os módulos não precisam estar vinculados a componentes. Eles nem mesmo precisam estar vinculados a nada e podem ser apenas HTML ou texto estático.

Pode haver várias instâncias do mesmo módulo. Por exemplo, você pode usar uma instância do módulo *Imagem Aleatória* para algumas páginas e outra instância para outras páginas, cada uma usando uma pasta de imagens diferente para selecionar imagens.

As listas *Módulos (Site)* e *Módulos (Administrador)* mostram os módulos atualmente instalados em cada interface e fornecem acesso para adicionar novos módulos ou editar módulos existentes.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos das Colunas da Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens da Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação da Lista](jdocmanual?article=help/common-elements/list-pagination).
* [Processo em Lote da Lista](jdocmanual?article=help/common-elements/list-batch-process).

Para ver listas de módulos instalados e módulos disponíveis, selecione uma das seguintes opções:

* [Módulos do Site](jdocmanual?article=help/modules-site/site-modules-site)
* [Módulos do Administrador](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## Como acessar

- Selecione **Conteúdo → Módulos do Site** no menu do Administrador. Ou...
- Selecione **Conteúdo → Módulos do Administrador** no menu do Administrador.

## Filtros de Lista

* **Site ou Administrador** Seleciona os módulos de Site ou Administrador.

## Cabeçalhos de Colunas

Esta é uma lista curta dos cabeçalhos exclusivos para listas de módulos.

- **Posição** A posição na página onde este módulo é exibido.
- **Tipo** O nome do sistema do Módulo.
- **Páginas** Os Itens do Menu onde este Módulo será exibido. Este item não está 
  presente nas listas de módulos do Administrador.
  - *Todos* Exibido em todas as páginas
  - *Nenhum* Não exibido em nenhuma página
  - *Selecionado* Exibido apenas nas páginas selecionadas
  - *Exceto selecionado* Exibido em todas as páginas, exceto as selecionadas
- **Acesso** O nível de Acesso de visualização para este módulo.
- **Idioma** Idioma dos módulos, o padrão é *Todos*. Este item não está presente 
  nas listas de módulos do Administrador.

### Posições dos Módulos

Para visualizar as posições dos módulos em um site ao vivo, vá para **Sistema  → Templates** e selecione
o botão **Opções** na Barra de Ferramentas. Defina *Visualizar Posições dos Módulos* para
habilitado e *Salvar*. Essa configuração é válida tanto para templates de site quanto para templates do administrador. Em seguida, adicione `?tp=1` ao final de uma URL que ainda não contenha uma
string de consulta ou `&tp=1` ao final de uma URL que já contenha uma string de consulta. A página irá mostrar todas as posições de módulo disponíveis, mesmo aquelas às quais 
não foram atribuídos módulos. As posições também são exibidas no formulário de edição do Módulo.

## Dicas

- Sites Joomla requerem pelo menos um módulo de Menu.
- Outros Tipos de Módulo (por exemplo, Banners) são opcionais.
- Alguns Módulos estão vinculados a componentes. Por exemplo, cada Módulo de Menu está relacionado a um Menu.
- Outros Módulos (por exemplo, Breadcrumbs) não dependem de nenhum outro conteúdo.
- Múltiplas ocorrências de um Módulo são permitidas e comuns.

*Traduzido por openai.com*

