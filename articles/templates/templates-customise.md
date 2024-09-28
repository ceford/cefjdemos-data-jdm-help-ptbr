<!-- Filename: Help4.x:Templates:_Customise  / Display title: Modelos: Personalizar -->

## Descrição

A página *Templates: Customise* é utilizada para editar o código fonte de um modelo. Você pode criar substituições para arquivos php e criar arquivos user.css e user.js para adicionar às versões do sistema. Você pode criar modelos filhos para permitir a edição dos arquivos mestre do modelo de substituições.

## Como Acessar

- Selecione **Sistema → Painel de Templates → Templates do Site** no
  menu do Administrador. Ou...
- Selecione **Sistema → Painel de Templates → Templates do Administrador**
  no menu do Administrador. Então...
  - Selecione um nome de template na coluna **Template**.

## Captura de Tela

As telas de Administrador e Templates do Site utilizam o mesmo layout. A tela de Template do Site está ilustrada aqui.

![modelos personalizar aba do editor cassiopeia](../../../ptbr/images/templates/templates-customise-cassiopeia-editor-tab.png)

## Campos do Formulário

### Aba Editor

- Selecione um arquivo para editar. A área de edição mostra o texto com destacamento de sintaxe para a maioria dos tipos de arquivos.

### Aba Criar Substituições

![aba criar substituições cassiopeia](../../../ptbr/images/templates/templates-customise-cassiopeia-create-overrides-tab.png)

- Selecione um item para substituir. Itens marcados com um ícone de arquivo sólido abrem para revelar uma lista de itens. Itens marcados com ícones de página aberta e preenchida sobrepostos criam uma substituição imediatamente, sem solicitação de confirmação. A substituição é colocada no local apropriado. Há uma mensagem de confirmação, por exemplo:
  *Substituição criada em /templates/cassiopeia/html/mod_whosonline*.

### Aba Arquivos Atualizados

![aba arquivos atualizados cassiopeia](../../../ptbr/images/templates/templates-customise-cassiopeia-updated-files-tab.png)

Se não houver atualizações no template desde que as substituições foram criadas, esta aba conterá uma mensagem simples:

<div class="alert alert-success">
Os arquivos substituídos estão atualizados. Nada foi mudado na última atualização da extensão ou do Joomla.
</div>

Se houver atualizações, uma tabela mostrará uma lista de substituições que precisam ser revisadas.

### Aba Descrição do Template

![aba descrição do template cassiopeia](../../../ptbr/images/templates/templates-customise-cassiopeia-template-description-tab.png)

- **Miniatura e Descrição** Informações sobre este template.

## Barra de Ferramentas

Note que os botões da Barra de Ferramentas mudam quando um arquivo é selecionado para edição.

### Nenhum arquivo selecionado

No topo da página você verá a barra de ferramentas mostrada na captura de tela acima. As funções são:

- **Criar Template Filho** Selecione para criar um novo template filho completo. Você será solicitado a fornecer um novo nome para o template filho. Há também a oportunidade de Fechar sem criar um novo template filho. Para remover o novo template filho: selecione o botão **Fechar**, selecione o botão Estilos na lista de Templates da Barra de Ferramentas, marque a caixa de seleção do novo template filho e selecione Excluir na barra de ferramentas.
- **Visualizar Template** Selecione para abrir a visualização padrão do Site usando este template.
- **Gerenciar Pastas** Selecione para criar uma nova pasta dentro da hierarquia do template. Aparece uma janela pop-up. **Importante:** selecione a pasta na qual a nova pasta deve aparecer antes de criar a nova pasta.
- **Novo Arquivo** Selecione para criar um novo arquivo ou para fazer upload de um arquivo do seu computador para a hierarquia do template do Joomla!. Aparece uma janela pop-up. **Importante** Selecione a pasta na qual o novo arquivo deve aparecer antes de criar o novo arquivo.
- **Verificar Sobrescritas** Ativado quando um Override é selecionado na aba *Overrides*. As opções são:
  - Marcar Verificado
  - Marcar Não Verificado
  - Remover Registro
- **Fechar** Fecha a tela atual e retorna à tela anterior sem salvar quaisquer modificações que você possa ter feito. Este ícone da barra de ferramentas não é mostrado se você estiver criando um novo item.
- **Ajuda** Abre esta tela de ajuda.

### Arquivo selecionado

- **Salvar** Salva o item e permanece na tela atual.
- **Salvar & Fechar** Salva o item e fecha a tela atual.
- **Renomear Arquivo** Selecione um arquivo para editar. Selecione o botão Renomear para solicitar um novo nome.
- **Excluir Arquivo** Você será solicitado a Confirmar ou Cancelar.
- **Verificar Sobrescritas** Ativado quando um Override é selecionado na aba *Overrides*.
- **Fechar Arquivo** Fecha o arquivo aberto e retorna à Aba do Editor.
- **Ajuda** Abre esta tela de ajuda.

## Dicas

- Antes de editar o arquivo HTML e CSS do modelo, é uma boa ideia fazer
  um backup do arquivo que você está editando. Além disso, você pode
  editar esses arquivos fora do Joomla! usando o editor de HTML ou CSS da sua preferência.

*Traduzido por openai.com*

