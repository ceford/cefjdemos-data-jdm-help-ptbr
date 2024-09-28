<!-- Filename: Help4.x:Components_Version_History  / Display title: Editar Histórico de Versões -->

## Descrição

Um popup de Histórico de Versão mostra versões anteriores do item que está sendo editado. Ele está disponível para Artigos, Banners e Clientes, Contatos, Feeds de Notícias, Notas de Usuário e todas as Categorias.

Cada vez que um item é salvo, uma nova versão é criada automaticamente. O número de versões a serem mantidas para cada item é definido nas Opções do componente. Uma ou mais versões podem ser marcadas para serem mantidas para sempre. Essas versões não serão deletadas automaticamente, mesmo que o número máximo de versões definido nas opções seja excedido.

**Nota:** Se o controle de versões for usado, campos personalizados não serão armazenados em versões diferentes.

## Como Acessar

Selecione o botão **Versões** na barra de ferramentas de uma página de edição de item.

## Captura de Tela

![Popup de histórico de versões](../../../ptbr/images/common-elements/articles-edit-versions.png)

## Cabeçalhos de Coluna

- **Checkbox** Marque esta caixa para selecionar um ou mais itens. Para selecionar todos os itens, marque a caixa no cabeçalho da coluna. Após marcar as caixas, selecione um botão na barra de ferramentas para realizar uma ação nos itens selecionados.
- **Data** A data e hora em que a versão foi salva. Selecionar este link abre a pré-visualização dessa versão em uma janela pop-up. Observe que uma das datas será seguida por um símbolo de estrela. Isso indica que esta é a versão que está atualmente salva e sendo editada.
- **Nota da Versão** Uma Nota da Versão pode ser usada para ajudar a identificar a natureza das alterações de uma versão para a outra. Uma Nota da Versão inserida antes de salvar um item aparecerá nesta coluna.
- **Manter Para Sempre** Esta coluna mostra se a versão foi marcada para Manter Para Sempre. Normalmente, cada versão será retida de acordo com as configurações na página de opções do componente. As configurações padrão são para manter no máximo 10 versões anteriores de um item. Quando um item é salvo e já tem 10 versões salvas, a versão mais antiga é excluída. Se uma versão estiver marcada como Manter Para Sempre, ela não será contada como uma das versões salvas e não será excluída quando o número máximo for atingido.
  - Para alternar o estado Manter Para Sempre, selecione um botão *Não* ou *Sim* ou marque a caixa de seleção da versão e depois selecione o botão Manter Ligado/Desligado na barra de ferramentas.
- **Autor** O usuário que salvou esta versão.
- **Contagem de Caracteres** O total de caracteres salvos nesta versão. Observe que isso inclui os nomes das colunas do banco de dados assim como os caracteres realmente digitados.

## Barra de Ferramentas

- **Restaurar** A versão atual do item é marcada com uma estrela à direita da Data. Para restaurar uma das outras versões salvas, marque a caixa de seleção para a versão desejada e selecione o botão Restaurar. A versão atual do item será substituída pela versão selecionada, e a tela de edição será recarregada com a versão restaurada carregada no editor.
- **Visualizar** Para visualizar uma versão, selecione a coluna Data para a versão desejada ou marque a caixa de seleção e depois o botão Visualizar. Uma janela pop-up separada será carregada, mostrando a versão selecionada do item.
- **Comparar** Para comparar duas versões e ver o que foi alterado, marque as caixas de seleção para cada uma das versões e depois o botão Comparar. Uma nova janela do navegador será aberta, mostrando uma lista de campos alterados e as mudanças feitas nesses campos.
  - A primeira coluna é o nome do campo, a segunda é a versão mais antiga, a terceira é a versão mais recente, e a última coluna destaca as diferenças entre as duas versões.
- **Manter Ligado/Desligado** Este botão alterna a funcionalidade Manter Para Sempre para uma versão. Normalmente, a versão mais antiga de um item será excluída automaticamente quando o número máximo de versões (definido nas Opções do componente) for excedido. Se você definir a propriedade Manter Para Sempre para uma versão, ela nunca será excluída automaticamente.
- **Excluir** Este botão permite a exclusão manual de uma ou mais versões. Marque a caixa de seleção para as versões a serem excluídas e depois selecione o botão Excluir. Note que isto *não* exclui o item que está sendo editado. Somente exclui o histórico de versões do item.

*Traduzido por openai.com*

