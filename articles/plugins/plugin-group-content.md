<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group  / Display title: Grupo de Conteúdo -->

## Descrição do Grupo

### Conteúdo - Confirmar Consentimento

![Plug-in de confirmação de consentimento de conteúdo](../../../en/images/plugins/plugin-group-content-confirm-consent.png)

- **Política de Privacidade Resumida** Aviso breve do texto que será exibido acima da Caixa de Seleção de Consentimento de Privacidade.
- **Artigo de Privacidade** Se necessário, selecione ou crie seu Artigo de Privacidade para vincular ao seu formulário.

Para mais informações, veja Configuração do Plug-in - Consentimento de Privacidade

### Conteúdo - Contato

![Plug-in de contato de conteúdo](../../../en/images/plugins/plugin-group-content-contact.png)

- **Redirecionamento** Você pode vincular o nome do autor a:
  - Página de contato associada.
  - Página web especificada no perfil de contato associado.
  - E-mail especificado no perfil de contato associado.
- **Aplicar link também ao nome de alias** Vincula aos dados reais do usuário mesmo se um alias de autor estiver definido nas opções do artigo.

### Conteúdo - Ocultação de E-mail

Este plug-in oculta todos os e-mails no conteúdo usando JavaScript para dificultar a ação dos spambots. Isso ajuda a prevenir que os e-mails contidos nos artigos sejam adicionados em listas de e-mails de spam. Você pode desativar a Ocultação de E-mail dentro de um artigo inserindo {emailcloak=off} em qualquer parte do texto do artigo. Nesse caso, nenhum endereço de e-mail no artigo será ocultado por este plug-in.

![Plug-in de ocultação de e-mail de conteúdo](../../../en/images/plugins/plugin-group-content-email-cloaking.png)

- **Modo** Como os e-mails serão exibidos. As opções são: *Como endereço mailto clicável* ou como *Texto não clicável*.

### Conteúdo - Campos

Este plug-in permite exibir um campo personalizado que foi inserido com o plug-in *Botão - Campos* ou usando a Sintaxe: `{field #}` diretamente na área do editor. Sintaxe:

- **`{field 1}`** exibirá o campo com o ID 1.
- **`{field 1,foo}`** exibirá o campo selecionado usando o layout alternativo `foo`.
- **`{fieldgroup 2}`** exibirá todos os campos dentro do grupo de campos com o ID 2.

### Conteúdo - Joomla

![Plug-in de conteúdo Joomla](../../../en/images/plugins/plugin-group-content-joomla.png)

- **Verificação de Exclusão de Categoria** Verifique se as categorias estão totalmente vazias antes de serem excluídas.
- **E-mail sobre Novo Artigo no Site** Envia e-mails aos usuários se *Enviar e-mail* estiver *Ativado* quando um novo artigo for enviado pelo Frontend.

### Conteúdo - Carregar Módulos

Este plug-in permite que você coloque um Módulo dentro de um Artigo com a sintaxe: `{loadposition xx}`, onde `xx` é um código de posição definido pelo usuário. Por exemplo, se você criar um Módulo com o valor de Posição `myposition1`, então digitar o texto `{loadposition myposition1}` dentro de um Artigo fará com que esse Módulo seja exibido naquele ponto do Artigo.

![Plug-in de carregamento de módulos de conteúdo](../../../en/images/plugins/plugin-group-content-load-modules.png)

- **Estilo** O Estilo do Módulo carregado.

### Conteúdo - Quebra de Página

Este plug-in adiciona funcionalidade de índice a um Artigo paginado. Isso é feito automaticamente através do uso do botão Quebra de Página adicionado à parte inferior do painel de texto em um Artigo. O código HTML é incluído aqui como referência do que está disponível. A Quebra de Página será exibida na janela de texto como uma simples linha horizontal.

![Plug-in de quebra de página de conteúdo](../../../en/images/plugins/plugin-group-content-page-break.png)

- **Mostrar Título do Site** Se o título e os atributos de cabeçalho do plug-in serão adicionados ou não à tag Título do Site.
- **Cabeçalho de Índice do Artigo** Mostrar ou ocultar Cabeçalho de Índice do Artigo. O Cabeçalho é exibido no topo do Índice de Conteúdo.
- **Cabeçalho de Índice do Artigo Personalizado** Insira um texto personalizado para o Cabeçalho de Índice do Artigo. Se vazio, o padrão será usado.
- **Índice de Conteúdos** Ocultar ou Mostrar um índice de conteúdos para Artigos de várias páginas.
- **Mostrar tudo** Se os Usuários terão ou não a opção de mostrar todas as páginas de um Artigo.
- **Estilo de Apresentação** Exibir o artigo com páginas separadas, abas ou sliders.

![Descrição da quebra de página de conteúdo](../../../en/images/plugins/plugin-group-content-page-break-description.png)

### Conteúdo - Navegação de Página

Este plug-in permite que você adicione links de navegação Próxima & Anterior aos Artigos, por exemplo, ao usar um layout de blog ou lista. Esta funcionalidade pode ser controlada com os seguintes parâmetros do Joomla!:

- **Mostrar Navegação** no Artigo - Tela de Configuração Global
- **Mostrar Navegação** nos Parâmetros - Seção Componente da Tela de Novo/Editar Item de Menu - Parâmetros - Componente para layouts de Artigos.

Note que, se o plug-in de Navegação de Página estiver desativado nesta tela, nenhuma Navegação de Página será exibida e as configurações dos parâmetros acima não terão efeito.

![Plug-in de navegação de página de conteúdo](../../../en/images/plugins/plugin-group-content-page-navigation.png)

- **Posição** Posição do link de navegação. As opções são *Acima* do Artigo ou *Abaixo* do Artigo.
- **Relativo a** Assinala a localização relativa para os parâmetros de Posição. Texto a colocará diretamente acima ou abaixo do conteúdo do artigo. Artigo Completo a colocará acima ou abaixo da exibição completa, incluindo título e ler mais.
- **Texto do Link** Escolha o que exibir como texto do link.

### Conteúdo - Pesquisa Inteligente

As mudanças no conteúdo não atualizarão o índice de Pesquisa Inteligente se você não ativar este plug-in.

### Conteúdo - Votação

![Plug-in de votação de conteúdo](../../../en/images/plugins/plugin-group-content-vote.png)

- **Posição** Posição da votação.

*Traduzido por openai.com*

