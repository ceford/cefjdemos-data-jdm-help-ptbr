<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step  / Display title: Tours Guiadas: Editar Etapa -->

## Descrição

Esta página é usada para adicionar um novo Passo ou editar um Passo existente de um tour.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Abada de Publicação](jdocmanual?article=help/common-elements/edit-publishing).

## Como Acessar

- Selecione **Sistema -> Gerenciar -> Tours Guiados** no menu do Administrador.
- Selecione o botão numerado de **Etapas** de um tour para abrir a página de etapas do tour.
- Selecione o botão da barra de ferramentas **Novo** para adicionar uma etapa.
- Selecione um **Título** da lista para editar uma etapa.

## Captura de Tela

![Guias turísticos edição de etapa](../../../ptbr/images/guided-tours/guided-tours-edit-step.png)

## Campos do Formulário

- **Título** O Título para esta etapa. Geralmente, é uma chamada para ação, por
exemplo, `Digite um título` se a etapa exigir interação do usuário. Se o título
for uma chave de idioma, um campo adicional é mostrado, representando a tradução
dessa chave para o idioma do usuário.

### Aba Editar Etapa

#### Painel Esquerdo

- **Descrição** É aqui que você insere a descrição da etapa, geralmente
  uma explicação detalhada ou ajuda para a etapa.
  A descrição da etapa pode ser uma chave de idioma. Quando este for o caso, um
  campo secundário apresenta a descrição traduzida dessa chave para o idioma do
  usuário.

#### Painel Direito

- **Posição** A posição da etapa em relação à informação que aponta.
  - **Inferior** A etapa aparece abaixo do alvo.
  - **Centro** A etapa aparece no centro da tela. Quando um alvo está
    ausente, esta é a posição padrão.
  - **Esquerda** A etapa aparece à esquerda do alvo.
  - **Direita** A etapa aparece à direita do alvo.
  - **Superior** A etapa aparece acima do alvo.
- **Alvo** O elemento da tela que a etapa aponta. Ele usa a sintaxe CSS.

  Por exemplo, *.button-new* irá apontar para o botão da página que tem a classe
  *button-new*.

  Se o alvo não for único, o primeiro alvo encontrado será usado. Ao criar
  etapas interativas, certifique-se de que o alvo é focável para acessibilidade. Você
  pode usar vários seletores, separados por vírgulas. O primeiro válido se
  tornará o alvo (um seletor é válido se: for encontrado na página, não estiver
  desativado, não for somente leitura e não estiver oculto). Se um alvo foi definido, mas
  não for encontrado ou for inválido, o tour não quebrará, mas mostrará a etapa
  no centro da tela.
- **Tipo** O tipo de etapa.
  - **Próximo** O usuário que está executando o tour passará para a próxima etapa.
  - **Redirecionar** A etapa será redirecionada para outra página.
  - **Interativa** A etapa requer interação do usuário, como inserir dados.
- **URL** O URL para redirecionar uma etapa do tipo *Redirecionar*.
  Por exemplo, *administrator/index.php?option=com_users&view=user&layout=edit*
  redirecionará a etapa para a tela de edição do usuário.
- **Tipo Interativo** O tipo de interação para uma etapa interativa.
  - **Envio de Formulário** O alvo é um botão que envia um formulário.
  - **Campo de Texto** O alvo é um campo de texto. Se o campo for obrigatório, 
    a pessoa que estiver realizando o tour não poderá prosseguir para a próxima 
    etapa até que os dados sejam inseridos.
  - **Botão** O alvo é um botão na tela.
  - **Outro** O alvo é qualquer outro elemento de formulário.

### Aba Opções

![Opções da aba de edição de etapas dos tours guiados](../../../ptbr/images/guided-tours/guided-tours-edit-step-options-tab.png)

## Dicas

- Use **GUIDEDTOUR** nas chaves de idioma como uma convenção onde quer que chaves de idioma sejam usadas (para título e descrição).

*Traduzido por openai.com*

