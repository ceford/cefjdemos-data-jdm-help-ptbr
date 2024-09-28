<!-- Filename: Help4.x:Redirects:_New_or_Edit  / Display title: Redirecionamentos: Novo ou Editar -->

## Descrição

A página *Redirecionamentos: Novo ou Editar* é usada para adicionar um novo redirecionamento ou editar um existente. A URL da qual você quer redirecionar não deve ser uma URL funcional no seu site que carrega uma página web. Pode ser a URL de uma página web que você desativou na interface de administração do Joomla! A URL de origem que você especifica ao criar o redirecionamento deve ser a URL completa, como você a digitaria no seu navegador. A URL de destino que você especifica ao criar um redirecionamento também deve ser a URL completa.

### Elementos Comuns

Alguns elementos desta página estão cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como acessar

- Selecione **Sistema → Redirecionamentos** no menu do Administrador. Então...
  - Para criar um novo redirecionamento, clique no botão **Novo** na Barra de Ferramentas. Ou...
  - Para editar um redirecionamento existente, clique no seu link na coluna **URL Expirada**.

## Captura de Tela

![Links de Redirecionamento](../../../ptbr/images/redirects/redirects-edit.png)

## Campos do Formulário

### Editar/Novo Link \#1 aba

- **URL Expirado** A URL a ser redirecionada.
- **Nova URL** A URL para redirecionar.
- **Status** Status de publicação do item. Os valores possíveis são:
  - *Habilitado* O item está habilitado. Este é o único estado que permitirá 
    aos usuários regulares do site visualizarem este item.
  - *Desabilitado* O item está desabilitado.
  - *Arquivado* O item foi arquivado.
  - *Lixeira* O item foi enviado para a lixeira.
- **Comentário** Um comentário que é visualizável apenas por um administrador. 
  Destina-se principalmente para referência do administrador.
- **ID** Este é um número de identificação único para este item, atribuído 
  automaticamente pelo Joomla. É usado para identificar o item internamente, e 
  você não pode alterar este número. Ao criar um novo item, este campo exibe 
  "0" até que você salve a nova entrada, momento em que um novo ID é atribuído a ele.
- **Data de Criação** Data em que o item (Artigo, Categoria, etc.) foi criado.
- **Data da Última Atualização** Exibe a última data em que o item foi modificado.

## Como Criar um Redirecionamento

1. Primeiro, certifique-se de que você ativou a opção *Usar Reescrita de URL* nas opções de Configuração Global da sua instalação do Joomla!. Note que apenas ativar a opção *Usar Reescrita de URL* não é o suficiente. Você também deve renomear o arquivo `htaccess.txt` no diretório do servidor web onde você instalou o Joomla! para `.htaccess` ou para qualquer outro nome de arquivo que seu servidor web Apache requeira para diretrizes de configuração adicionais. No arquivo de configuração do Apache, essa configuração é chamada `AccessFileName` e, por padrão, está definida como `.htaccess`.

2. Em seguida, abra a página *Redirecionamento: Links* e selecione o botão da barra de ferramentas *Novo*.

3. Na página *Redirecionamentos: Novo*, insira as informações do redirecionamento. Ao inserir URLs nos campos *URL Expirado* e *URL Novo*, digite o URL completo como você o digitariam em seu navegador web para visualizá-lo. O *URL Expirado* deve ser um URL que não resolva para nenhuma página web válida em seu site. Você pode especificar um URL de origem para uma página web do Joomla! que você colocou em estado desabilitado no backend do administrador. Certifique-se de que a opção *Estado* esteja configurada como **Habilitado**.

4. Selecione o botão da barra de ferramentas **Salvar & Fechar** para salvar seu novo redirecionamento e colocá-lo em efeito.

## Dicas

- Ao inserir URLs nos campos *URL Expirada/Origem* e *Nova/Destino*, insira a URL completa como você digitaria no seu navegador para visualizar a página da web.

*Traduzido por openai.com*

