<!-- Filename: Help4.x:Redirects:_Links  / Display title: Redirecionamentos: Links -->

## Descrição

A página *Redirects: Links* mostra uma lista de redirecionamentos atuais do site.

O componente de redirecionamento é usado para redirecionar URLs de páginas da web que não existem mais no seu site para páginas da web que estão funcionando. A URL da qual você deseja redirecionar não deve estar funcionando e realmente carregando uma página da web. Pode ser a URL de uma página da web que você desativou.

A *URL Expirada* que você especificar ao criar o redirecionamento deve ser a URL completa, como se você a digitasse em seu navegador. O componente exibirá apenas a última parte da URL de origem na lista de redirecionamentos.

A *Nova URL* que você especificar ao criar um redirecionamento precisa ser a URL completa também. Você deve ter a opção *Usar Reescrita de URL* habilitada nas opções de *Configuração Global* da sua instalação Joomla! para que os redirecionamentos que você criar funcionem.

### Elementos Comuns

Alguns elementos desta página são cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas da Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginação da Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como acessar

- Selecione **Sistema → Gerenciar painel → Redirecionamentos** no menu do Administrador.

## Captura de Tela

![Links de redirecionamento](../../../ptbr/images/redirects/redirects-links.png)

## Cabeçalhos de Coluna

- **URL Expirada** A URL que está sendo redirecionada em seu site.
  Apenas a porção da página web da URL é exibida nesta listagem.
- **Nova URL** A URL de destino para o redirecionamento.
- **Página de Referência** A página web de referência para o redirecionamento.
- **Data de Criação** Data em que o item (Artigo, Categoria, etc.) foi
  criado.
- **Hits 404** Número de Hits 404 que houve nesta URL.
- **Código de Status** O Código de Status da página.

## Dicas

- Para que seus redirecionamentos funcionem, você deve habilitar a opção
  **Usar Reescrita de URL** nas opções de **Configurações Globais** da sua
  instalação do Joomla!. Observe também que apenas ativar a opção *Usar
  Reescrita de URL* não é suficiente. É necessário dar o passo adicional de
  renomear o arquivo `htaccess.txt` no diretório do site onde você
  instalou o Joomla! para `.htaccess` ou para qualquer nome de arquivo que seu 
  servidor web Apache exigir para diretivas de configuração adicionais. No
  arquivo de configuração do Apache, essa configuração é chamada `AccessFileName` e
  por padrão, está definida como `.htaccess`.

*Traduzido por openai.com*

