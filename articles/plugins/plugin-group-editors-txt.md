<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group  / Display title: Grupo de Editores -->

## Descrição do Grupo

Plugins de editor ajudam usuários a inserir texto com marcação ou layouts para fins especiais, como fragmentos de HTML ou código. Para usar um Editor, o desenvolvedor de software marca o campo de entrada de dados como tipo `Editor`. Se nenhum plugin de editor estiver habilitado, ele será exibido como um campo de área de texto simples. Com um ou mais plugins de editor habilitados, o plugin padrão do site será usado, definido na Configuração Global, a menos que substituído pelo plugin preferido do usuário, definido no Perfil do Usuário. O Joomla tem os três plugins de editor principais listados abaixo. Plugins de editor adicionais de terceiros podem estar disponíveis. Alguns editores possuem uma seleção muito grande de opções.

### Editor - CodeMirror

O editor CodeMirror é um editor de código que fornece um editor mais adequado para código-fonte. Ele possui realce de sintaxe de código para muitas linguagens de programação. Ele pode mostrar tags incompatíveis e também ajudar a manter a indentação de código consistente.

![Opções do CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror.png)

- **Listar números** Exibe números de linha no editor.
- **Dobramento de Código** Permite dobrar blocos de código.
- **Gutters** Marcador de Código e Dobramento de Código.
- **Destacar Linha Ativa** Adiciona um destaque à linha onde o cursor está.
- **Destacar Correspondências de Seleção** Destaca instâncias da palavra selecionada em todo o documento.
- **Correspondência de Tags** Destacar tags correspondentes.
- **Correspondência de Colchetes** Destacar colchetes correspondentes.
- **Conclusão de Tags** Conclusão automática de tags.
- **Conclusão de Colchetes** Conclusão automática de colchetes.
- **Mapa de Teclas** Faz o CodeMirror funcionar como outros editores populares.
- **Alternar para Tela Cheia** Seleciona a tecla de função para usar para alternar para o modo de tela cheia.
- **Usar Modificadores** Seleciona qualquer tecla modificadora para usar com a tecla de alternar para tela cheia.

![Opções avançadas do CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror-advanced.png)

- **Tema** Define as cores para o editor.
- **Cor da Linha Ativa** A cor a ser usada para destacar a linha ativa. Será exibida com 50% de opacidade.
- **Cor da Tag Correspondente** A cor de fundo a ser usada para destacar tags correspondentes. Será exibida com 50% de opacidade.
- **Fonte** A fonte a ser usada no editor. Se não estiver instalada, será carregada de https://www.google.com/fonts/.
- **Tamanho da Fonte (px)** O tamanho da fonte no editor.
- **Altura da Linha (em)** A altura de uma linha de texto. Isto está em ems, o que significa que 1.0 é igual ao tamanho da fonte e 2.0 é igual a 2x o tamanho da fonte.
- **Estilo da Barra de Rolagem** Seleciona o estilo da barra de rolagem que você deseja que o CodeMirror use.
- **Prévia** Um exemplo de como os campos do seu editor CodeMirror aparecerão com as configurações atuais (salve para atualizar).

### Editor - Nenhum

Este plugin carrega um editor de texto básico. Esta opção pode ser usada quando você está colando código HTML de outra fonte e não deseja que o HTML seja alterado por um editor WYSIWYG. Este plugin não possui opções.

### Editor - TinyMCE

O editor TinyMCE é um editor WYSIWYG e é o editor padrão para entrada de HTML no Joomla!.

![Opções do plugin TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce.png)

- **Selecionar aba de seleção** Selecione *Set 2*, *Set 1* ou *Set 0* funcionalidade. Com *Set 2* selecionado, você vê o editor para uso *Público*. *Set 1* selecionado é o padrão para Gerentes e Registrados, *Set 0* selecionado é o padrão para Administradores, Editores e Super Usuários.

Cada aba tem uma longa lista de opções que não são ilustradas aqui. A lista a seguir é uma seleção.

- **Tema do Site** Escolha o tema que será aplicado ao editor TinyMCE quando exibido em seu site.
- **Tema do Administrador** Escolha o tema que será aplicado ao editor TinyMCE quando exibido em seu Backend de Administrador.
- **Modo da Barra de Ferramentas** Controla como exibir os botões da barra de ferramentas que não estão na primeira linha.
- **Arrastar e Soltar Imagens** Habilitar arrastar e soltar para fazer upload de imagens.
- **Diretório de Imagens** O diretório com os arquivos de imagens a serem listados em relação à pasta padrão de imagens (definida em Mídia > Opções).
- **Codificação de Entidades** Controla como as entidades HTML são codificadas. A configuração recomendada é `raw`. `named` = usa codificação de entidade nomeada (por exemplo, `<`). `numeric` = usa codificação HTML numérica (por exemplo, `%03c`). raw = Não codificar entidades HTML. Observe que a pesquisa de conteúdo pode não funcionar corretamente se a configuração não for `raw`.
- **Seleção Automática de Idioma** Se Sim, o idioma do editor corresponderá automaticamente ao idioma da interface do usuário selecionado. Se o idioma tiny não existir, o idioma do editor será o padrão em inglês.
- **Direção do Texto** Se a linguagem é lida da *Esquerda para Direita* ou *Direita para Esquerda* (por exemplo, como o árabe). O padrão é *Esquerda para Direita*.
- **Classes de CSS do Template** Carregar ou não o arquivo *editor.css*. Se nenhum arquivo desse tipo for encontrado para o template padrão, o arquivo *editor.css* do template do sistema será usado. O padrão é *Sim*.
- **Classes de CSS Personalizadas** Caminho URL completo opcional para um arquivo CSS personalizado. Se inserido, isso substitui a configuração de Classes de CSS do Template.
- **URLs** Se deve usar URLs Relativos ou Absolutos para links. O padrão é *Relativo*.
- **Novas Linhas** Se deve interpretar novas linhas como *Elementos P* ou *Elementos BR*. O padrão é *Elementos P*.
- **Usar Filtro de Texto do Joomla** Se ativado, o filtro de texto da Configuração Global do Joomla para cada grupo de usuários será aplicado. Se desativado, os filtros definidos aqui serão usados para todos os grupos de usuários.
- **Elementos Proibidos** Os elementos que serão limpos do texto. O padrão é *applet*, que removerá elementos de applet do texto.
- **Elementos Válidos** Define quais elementos permanecerão no texto editado quando o editor salvar (o conjunto de regras padrão para esta opção é uma mistura das especificações completas do HTML5 e HTML4).
- **Elementos Válidos Estendidos** Lista opcional de elementos HTML válidos para adicionar ao conjunto de regras existente.
- **Redimensionamento** Habilitar/desabilitar o redimensionamento da área do editor (verticalmente e também horizontalmente se *Redimensionamento Horizontal* estiver habilitado).
- **Redimensionamento Horizontal** Habilitar/desabilitar o redimensionamento horizontal.
- **Caminho do Elemento** Se configurado como ATIVADO, exibe as classes definidas para o texto marcado.
- **Contagem de Palavras** Ativar/desativar contagem de palavras.
- **Markdown** Permite o uso de sintaxe de estilo Markdown para criar links, listas e outros estilos. Esta sintaxe especial é convertida e salva como HTML regular. Por exemplo, o usuário pode digitar # texto para produzir um cabeçalho ou **texto** para deixar o texto em negrito.
- **Imagem Avançada** Ativar/desativar uma caixa de diálogo de imagem mais avançada.
- **Lista Avançada** Ativar/desativar a capacidade de definir formatos de número e tipos de marcadores em listas ordenadas e não ordenadas.
- **Menu de Contexto** Ativar/desativar o menu de contexto.
- **Plugin Personalizado** Adicionar plugins personalizados TinyMCE ao editor especificando-os aqui.
- **Botão Personalizado** Adicionar botões personalizados TinyMCE ao editor especificando-os aqui.

#### Aba Avançada do TinyMCE

![Opções Avançadas do TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce-advanced.png)

- **Número de Conjuntos** Número de conjuntos que podem ser criados. Mínimo 3.
- **Altura do HTML** A altura, em pixels, da janela pop-up do modo HTML.
- **Largura do HTML** A largura, em pixels, da janela pop-up do modo HTML.

*Traduzido por openai.com*

