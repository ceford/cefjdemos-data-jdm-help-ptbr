<!-- Filename: Help4.x:Templates:_Customise_Source  / Display title: Modelos: Personalizar Fonte -->

<div class="alert alert-warning">
Esta página aparece no índice das páginas de Ajuda, mas não é usada por meio de um botão de Ajuda.
Este é um bug que provavelmente será corrigido.
</div>

## Descrição

A página *Templates: Personalizar Fonte* é onde o código-fonte dos arquivos de template é editado. Ela fornece uma interface de texto simples para editar os arquivos de template. A sintaxe de programação HTML e PHP é destacada para tornar os arquivos de código-fonte mais fáceis de ler. Na barra de título, a palavra *Fonte* aparece como o nome do template, por exemplo *(Cassiopeia)*.

## Como Acessar

- Selecione **Sistema → Painel de Modelos → Modelos de Site** no
  menu do Administrador. Ou...
- Selecione **Sistema → Painel de Modelos → Modelos de Administrador**
  no menu do Administrador. Então...
  - Selecione um nome de modelo na coluna **Modelos**. Então...
    - Selecione um arquivo para editar na aba do Editor.

## Captura de Tela

![Modelos personalizar aba do editor cassiopeia](../../../ptbr/images/templates/templates-customise-cassiopeia-edit-component-editor-tab.png)

## Campos do Formulário

### Aba Editor

- Selecione um arquivo para editar. A área de edição mostra o texto com 
  realce de sintaxe para a maioria dos tipos de arquivos.

### Aba Criar Substituições

- Selecione um item para substituir. Se uma pasta for selecionada, ela será expandida 
  para exibir uma lista de arquivos. Se um arquivo for selecionado, ele é copiado 
  imediatamente para a pasta html sem pedir confirmação. A substituição é colocada 
  na localização apropriada. Há uma mensagem de confirmação, por exemplo: 
  *Substituição criada em /templates/cassiopeia/html/mod_whosonline*.

### Aba Arquivos Atualizados

Se não houver atualizações no template desde que as substituições foram
criadas, esta aba conterá uma mensagem simples:

- **Aviso** Os arquivos substituídos estão atualizados. Nada foi alterado
  na última atualização da extensão ou do Joomla.

Se houver atualizações, uma tabela mostrará uma lista de substituições que
precisam ser revisadas.

### Aba Descrição do Template

- **Miniatura e Descrição** Informações sobre este template.

## Barra de Ferramentas

Os ícones da Barra de Ferramentas mudam de acordo com a ação realizada. Você pode ver:

- **Salvar** Salva o item e permanece na tela atual.
- **Salvar e Fechar** Salva o item e fecha a tela atual.
- **Copiar Modelo** Copia o modelo atual. Uma caixa de diálogo solicita um novo nome.
- **Visualização do Modelo** Seleciona para abrir o Site em uma nova aba do navegador.
- **Gerenciar Pastas** Permite a criação e exclusão de pastas de modelo usando uma caixa de diálogo.
- **Novo Arquivo** Permite o upload de um arquivo do seu computador para a hierarquia de arquivos do modelo usando uma caixa de diálogo.
- **Renomear Arquivo** Selecione um arquivo para editar. Clique no botão Renomear para solicitar um novo nome.
- **Excluir Arquivo** Será solicitado que você Confirme ou Cancele.
- **Fechar Arquivo** Fecha o arquivo aberto e retorna à Aba do Editor.
- **Ajuda** Abre esta tela de ajuda.

## Dicas

- Importante: Não exclua os arquivos de modelo padrão usando FTP porque
  isso gera um erro tanto no frontend quanto no backend.
- Antes de editar o arquivo HTML e CSS do modelo, é uma boa ideia fazer
  um backup do arquivo que você está editando. Além disso, você pode
  editar esses arquivos fora do Joomla! usando o editor HTML ou CSS de
  sua escolha.

*Traduzido por openai.com*

