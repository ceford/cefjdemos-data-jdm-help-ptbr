<!-- Filename: Help4.x:Glossary  / Display title: Glossário -->

O Glossário do Joomla! é útil para explicar termos comuns usados em tutoriais, telas de ajuda e documentação avançada do Joomla!.

## Lista de Controle de Acesso

## Apelido

## Âncora

Uma âncora é criada usando a tag `<a>` em HTML. Uma âncora permite que você coloque um marcador dentro de uma página HTML. No Joomla!, você pode colocar uma âncora dentro de um artigo (por exemplo, usando o editor TinyMCE). Isso permite que você crie um link que levará diretamente a esse ponto no artigo.

O código fonte HTML para uma âncora é o seguinte:

    <a name="minha_âncora" title="Minha Âncora"></a>

Você pode linkar para uma âncora dentro da mesma página usando o código HTML

    <a href="#minha_âncora" ></a>

Clicar nesse link o levará diretamente para a localização da tag da âncora.

Você pode linkar para uma âncora em uma página diferente adicionando "#" mais o nome da âncora ao final da URL. No exemplo acima, se a URL do artigo fosse `http://www.meusite.com/meu_artigo.html`, então você poderia linkar diretamente para a âncora nessa página com a URL `http://www.meusite.com/meu_artigo.html#minha_âncora`.

## Artigo

## Folha de Estilo em Cascata (CSS)

Uma Folha de Estilo em Cascata, ou CSS, é usada para controlar a apresentação de uma
página XHTML. Por exemplo, um arquivo CSS frequentemente controlará a fonte,
margens, cores, gráficos de fundo e outros aspectos da aparência de uma página web.
CSS permite que você separe o conteúdo de uma página XHTML de sua aparência.
No Joomla!, arquivos CSS (por exemplo, template.css) são normalmente parte do template.

**Veja também:** Template, Sufixo de Classe da Página, Sufixo de Classe do Módulo

## Categoria

Cada parte de um site alimentado pelo Joomla! ou qualquer tipo de site CMS precisa de um método para exibir e armazenar seu conteúdo de forma lógica. O método usual é por categorias e subcategorias. O Joomla! permite múltiplas maneiras de exibir e utilizar conteúdo controlado por categorização. Alguns dos tipos de conteúdo que possuem categorização são Artigos (o conteúdo principal das páginas web), Banners e Contatos.

Uma categoria chamada *Sem Categoria* é a categoria padrão atribuída à maioria dos tipos de conteúdo. A categoria *Sem Categoria* não é descritiva e deve ser usada apenas conforme necessário para tipos de conteúdo que não se enquadram em uma categoria específica.

Ao criar e atribuir categorias, você deve ter uma estrutura planejada. Como exemplo, esta é uma maneira de categorizar vários artigos sobre pássaros:

- Crie duas categorias de artigos de nível superior chamadas *Animais* e *Plantas*.
- Sob a categoria *Animais*, crie subcategorias chamadas *Pássaros* e *Mamíferos*.
- Sob a subcategoria de *Pássaros*, crie categorias intituladas *Falcões*, *Papagaios* e *Pardais*. Esta é a estrutura de categoria resultante:

```
- Animais
  - Pássaros
    - Falcões
    - Papagaios
    - Pardais
  - Mamíferos
```

Agora você pode criar vários artigos nas subcategorias Falcão, Papagaio e Pardal, utilizando os diferentes gêneros ou nomes comuns dos tipos específicos desses pássaros.

## Chrome

Os recursos visíveis da interface gráfica de um aplicativo são às vezes
referidos como *chrome*.

## Componente

## Núcleo

A palavra *núcleo* no Joomla! refere-se aos arquivos distribuídos que são necessários para criar e administrar um site alimentado pelo CMS Joomla. O núcleo do Joomla contém todas as funcionalidades necessárias para criar e gerenciar um novo site de forma rápida e fácil.

## Prefixo da Tabela do Banco de Dados

O prefixo da tabela do banco de dados é uma string (com alguns caracteres de comprimento) adicionada
ao nome das tabelas do Joomla!. Usar um prefixo permite que você execute várias 
instalações do Joomla! usando um único banco de dados.

O prefixo da tabela do banco de dados pode ser definido durante a instalação. Mudá-lo
posteriormente é possível, mas requer acesso ao banco de dados por meio de um
método fora do Joomla ou uma Extensão do Joomla, como o Akeeba Admin Tools, e
causará algum tempo de inatividade.

Os desenvolvedores de extensões precisam usar a string `#__` para representar o prefixo.
Esta será substituída pelo prefixo real em tempo de execução.

## Extensão

## LDAP

## Idioma

Idiomas são talvez o tipo de extensão mais básico e crítico. Idiomas são empacotados como um pacote de idioma núcleo ou um pacote de idioma de extensão. Esses pacotes consistem em arquivos INI que contêm pares de chave/valor para fornecer a tradução de cadeias de texto estático dentro do código-fonte do Joomla!. Isso permite que tanto o núcleo do Joomla! quanto os componentes e módulos de terceiros sejam internacionalizados. Pacotes de idioma núcleo também incluem um arquivo meta XML descrevendo o idioma e fornecendo informações sobre as fontes a serem usadas para a geração de conteúdo PDF.

## Menu

No Joomla!, um **Menu** é um módulo que contém um conjunto de **itens de menu** usados para navegação. Cada item de menu define uma URL para uma página no site. Ele possui configurações que controlam a exibição do conteúdo da página e o estilo.

## Model-View-Controller

O Joomla faz uso extensivo do padrão de design
<a href="http://en.wikipedia.org/wiki/Model-view-controller"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Model-View-Controller</a>.

Quando o Joomla é iniciado para processar uma solicitação de um usuário, como um GET para uma página específica, ou um POST contendo dados de formulário, uma das primeiras coisas que o Joomla faz é analisar a URL para determinar qual componente será responsável pelo processamento da solicitação e passar o controle para esse componente.

Se o componente foi projetado de acordo com o padrão MVC, ele passará o controle para o controlador. O controlador é responsável por analisar a solicitação e determinar quais modelos serão necessários para atender à solicitação e qual visualização deve ser usada para retornar os resultados ao usuário.

O modelo encapsula os dados usados pelo componente. Na maioria dos casos, esses dados virão de um banco de dados, seja o banco de dados do Joomla ou algum banco de dados externo, mas também é possível que o modelo obtenha dados de outras fontes, como via uma API de serviços web executada em outro servidor. O modelo também é responsável por atualizar o banco de dados quando necessário. O propósito do modelo é isolar o controlador e a visualização dos detalhes de como os dados são obtidos ou alterados.

A visualização é responsável por gerar a saída que será enviada ao navegador pelo componente. Ela chama o modelo para qualquer informação que precise e a formata adequadamente. Por exemplo, uma lista de itens de dados extraídos do modelo poderia ser moldada em uma tabela HTML pela visualização.

Como o Joomla é projetado para ser altamente modular, a saída do componente é geralmente apenas parte da página completa da web que o usuário verá no final. Uma vez que a visualização gerou a saída, o componente devolve o controle para o framework do Joomla, que então carrega e executa o template. O template combina a saída do componente e quaisquer módulos que estejam ativos na página atual, para que possa ser entregue ao navegador como uma única página.

Para fornecer poder e flexibilidade adicionais aos designers web, que podem estar apenas preocupados em criar novos designs ao invés de manipular o código subjacente, o Joomla divide a visualização tradicional em uma visualização e layout separados. A visualização extrai dados do modelo, como em um padrão MVC tradicional, mas simplesmente torna esses dados disponíveis para o layout, que é responsável por formatar os dados para apresentação ao usuário. A vantagem de ter essa divisão é que o sistema de templates do Joomla fornece um mecanismo simples para layouts serem substituídos no template. Essas substituições de layout (frequentemente chamadas de "substituições de template" porque fazem parte do template, embora na verdade seja o layout que está sendo substituído) são incluídas com o template e dão ao designer do template controle completo sobre toda a saída do núcleo do Joomla e quaisquer extensões de terceiros instaladas que cumpram com o padrão de design MVC.

## Módulo

## Sufixo de Classe de Módulo

Um Sufixo de Classe de Módulo é um parâmetro usado em módulos para adicionar uma nova classe CSS a um módulo. Ele é utilizado em conjunto com estilos definidos em um arquivo user.css para alterar a aparência padrão de um módulo.

O novo nome da classe pode ser usado para adicionar qualquer estilo desejado ao módulo sem a necessidade de recriar todo o código CSS existente. Observe que, se você criar um novo nome de classe, certifique-se de que ele tenha um nome único e não conflite com nenhum nome de classe existente.

## Posição do Módulo

## Módulo chrome

## PHP

PHP é uma linguagem de script de computador projetada para criar páginas web dinâmicas. PHP é amplamente utilizado para desenvolvimento web e pode ser incorporado ao HTML. Ele geralmente é executado em um servidor web, recebendo código PHP como entrada e criando páginas web como saída. Joomla! é escrito principalmente usando a linguagem PHP.

## Sufixo de Classe da Página

Um Sufixo de Classe da Página é um parâmetro usado em itens de menu de conteúdo para adicionar uma nova classe CSS ao layout da página. Ele é utilizado em conjunto com estilos definidos em um arquivo user.css para alterar a aparência padrão de um módulo.

O novo nome de classe pode ser usado para adicionar qualquer estilo desejado à página sem a necessidade de recriar todo o código CSS existente. Observe que, se você criar um novo nome de classe, certifique-se de que ele tenha um nome único e não entre em conflito com nomes de classe existentes.

## Patch

## Plugin

## URLs Amigáveis para Motores de Busca

URLs amigáveis para motores de busca é um termo comumente abreviado como URLs SEF
ou simplesmente SEF. URLs normais do Joomla! parecem algo assim:

    http://www.seusite.org/index.php?option=com_content&view=section&id=3&Itemid=41

Opcionalmente, você pode fazer com que as URLs se pareçam com páginas HTML estáticas, como
isto:

    http://www.seusite.org/faq.html

Existem opções integradas para gerar URLs SEF. Estas opções são ativadas nas
*Configurações de SEO* (Otimização para Motores de Busca) na aba Site da
página de Configuração Global. Existem também extensões de terceiros que criam
URLs SEF para Joomla!.

## Menus divididos

Um menu dividido é onde diferentes níveis de um único menu são exibidos em dois ou mais locais em uma única página da web.

Por exemplo, um requisito comum é que um menu de itens de nível superior apareça no topo da página. Quando um dos itens é clicado, o usuário é levado a uma página onde um menu secundário, digamos à esquerda da página, mostra itens de segundo nível dentro do escopo do item de nível superior.

Os menus aparecem em locais separados na página, mas estão relacionados porque um mostra apenas itens de nível superior, enquanto o outro mostra itens de segundo nível. Essa ideia pode ser estendida para incluir menus para itens de terceiro nível e além.

Isso pode ser implementado no Joomla usando um único menu de múltiplos níveis e depois criando mais de um módulo de menu, cada um referindo-se a um nível diferente.

## Template

Um template é um tipo de extensão do Joomla! que controla a aparência da página.
- Um template de Site controla a aparência pública do conteúdo do site.
- Um template de Administrador controla a aparência do site para tarefas 
  administrativas, tais como: gestão de usuário, menu, artigo, categoria, 
  módulo, componente, plugin e template.

## Estilo de template

## Pacote de Atualização

Um Pacote de Atualização no Joomla! é um pacote de arquivos que contém os
arquivos que foram alterados entre as versões do Joomla!. Quando este arquivo é
descompactado, ele substitui a versão antiga dos arquivos modificados pela nova
versão. Por exemplo, se cinquenta arquivos foram alterados entre a versão 5.1
e 5.2, o pacote de atualização conteria esses cinquenta arquivos e instruções
sobre como executar a atualização. Às vezes, isso inclui atualizações de banco de dados e
remoção de arquivos que não são mais utilizados.

*Traduzido por openai.com*


