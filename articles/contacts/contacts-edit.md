<!-- Filename: Help4.x:Contacts:_New_or_Edit  / Display title: Contatos: Editar -->

## Descrição

O *Formulário de Edição de Contatos* é usado para adicionar um novo contato ou editar um contato existente.

**Atenção:** Se um contato tiver um item de menu, então as Configurações do Menu de Contatos substituirão algumas configurações disponíveis aqui. Tenha cuidado para não divulgar informações pessoais por engano!

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Esquema](jdocmanual?article=help/common-elements/edit-schema).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [O Pop-up de Histórico de Versões](jdocmanual?article=help/common-elements/edit-version-history).

## Como Acessar

- Selecione **Componentes → Contatos → Contatos** no menu do Administrador.
- Para **Adicionar** um novo Contato:
  - Selecione o botão **Novo** na Barra de Ferramentas.
- Para **Editar** um Contato existente:
  - Selecione um título de contato na coluna **Título**.

## Captura de tela

![Edição de contato - aba de contato](../../../ptbr/images/contacts/contacts-edit-contact-tab.png)

## Campos do Formulário

Nesta seção, você pode inserir informações sobre o Contato, como nome, endereço, e-mail, e assim por diante. As opções permitem controlar configurações como quais informações são exibidas para cada Contato.

- **Nome** O nome completo do Contato.
- **Alias** O nome interno do item. Normalmente, você pode deixar este campo em branco e o Joomla preencherá um valor padrão com o Título em letras minúsculas e com traços em vez de espaços.

### Aba Editar Contato

Aqui você insere as informações básicas sobre o contato.

- **Usuário Vinculado** Se este Contato estiver vinculado a um usuário, selecione o ícone *Selecionar Usuário* para revelar um formulário popup onde você poderá selecionar um dos usuários cadastrados. Um usuário vinculado pode ser removido com o botão *- Nenhum Usuário -* no formulário popup de Seleção de Usuários.
- **Imagem** Imagem a ser exibida para este Contato. Selecione um arquivo de imagem na caixa de seleção suspensa. Isso lista imagens na pasta 'images/stories'. Imagens podem ser enviadas usando o componente Media.
- **Posição:** A posição atual do Contato.
- **E-mail** O endereço de e-mail do Contato. Note que endereços de e-mail no Joomla! podem ser protegidos de "spambots" habilitando o Plugin "Content-Email Cloaking". Este está habilitado por padrão.
- **Endereço** O endereço do Contato.
- **Cidade ou Bairro** A cidade ou bairro do Contato.
- **Estado ou Província** O estado ou província do Contato.
- **Código Postal / CEP** O código postal do Contato.
- **País** O país do Contato.
- **Telefone** O número de telefone do Contato.
- **Celular** O número de celular do Contato.
- **Fax** O número de fax do Contato.
- **Website** O endereço do site do Contato.
- **Campos de Classificação** Para habilitar campos de classificação para listas de Categorias, vá para a tela **Contatos → Opções** e defina **Layouts de Lista → Classificar Por** como **Nome de Classificação**. Então você precisa usar palavras reais para classificação. Por exemplo, defina o Primeiro Campo de Classificação como **Doe**, o segundo campo como **John** para o primeiro contato; então o Primeiro Campo de Classificação como **Doe**, o segundo campo como **Jane** para o segundo contato. O terceiro campo não é usado neste caso. Os campos de classificação são campos de caracteres, então se você quiser classificar por idade, precisa inserir 0x para idades menores que 10, por exemplo, 08.
  - **Primeiro Campo de Classificação** O nome a ser usado como o primeiro campo de classificação.
  - **Segundo Campo de Classificação** O nome a ser usado como o segundo campo de classificação.
  - **Terceiro Campo de Classificação** O nome a ser usado como o terceiro campo de classificação.
- **Status**: Status de publicação do item. Os valores possíveis são:
  - *Publicado*: O item está publicado. Este é o único estado que permitirá que usuários regulares do site visualizem este item.
  - *Não Publicado*: O item não está publicado.
  - *Arquivado*: O item foi arquivado.
  - *Lixeira*: O item foi enviado para a Lixeira.
- **Categoria** A Categoria à qual este item pertence.
- **Destaque** Se o item será exibido ou não em vista de destaque.
- **Acesso** O Nível de Acesso de visualização para este item.
- **Idioma** Idioma do item.
- **Tags** Insira uma ou mais tags opcionais para este item. Você pode selecionar tags existentes digitando as primeiras letras. Você também pode criar novas tags digitando-as aqui. As tags permitem ver listas de itens relacionados em diferentes tipos de conteúdo (por exemplo, artigos, contatos e categorias).
- **Nota de Versão** Campo opcional para identificar esta versão do item na janela de Histórico de Versões do item.

### Aba Informações Diversas

![Aba Editar Contato](../../../ptbr/images/contacts/contacts-edit-miscellaneous-tab.png)

Outras informações sobre este Contato podem ser inseridas usando o editor.

### Aba Exibição

![Aba Editar Contato](../../../ptbr/images/contacts/contacts-edit-display-tab.png)

- **Mostrar Categoria** Exibir ou ocultar a categoria do Contato.
- **Mostrar Lista de Contatos** Exibir ou ocultar a lista de Contatos.
- **Formato de Exibição** Determina o estilo usado para exibir seções do formulário de contato.
- **Tags** Se deve ocultar ou mostrar quaisquer tags para este item.
- **Informações de Contato** Exibir ou ocultar as informações de Contato.
- **Informações Diversas** Exibir ou ocultar as informações diversificadas.
- **vCard** Exibir ou ocultar o link vCard para este Contato.
- **Mostrar Artigos do Usuário** Se este contato estiver mapeado para um usuário, e se isso estiver configurado para Mostrar, então uma lista de artigos criados por este usuário será exibida.
- **\# Artigos a Listar** Número de artigos a listar.
- **Perfil do Usuário** Se este contato estiver mapeado para um usuário, e se isso estiver configurado para Mostrar, então o perfil deste usuário será exibido.
- **Mostrar Grupos de Campos Personalizados do Usuário** Mostrar campos personalizados do usuário que pertencem a todos ou apenas aos grupos de campos selecionados.
- **Links de Contato** Exibir ou ocultar os links de contato.
- **Rótulo do Link A** Rótulo para um link adicional para este contato.
- **URL do Link A** A URL do link adicional para este contato.
- **Rótulo do Link B** Rótulo para um link adicional para este contato.
- **URL do Link B** A URL do link adicional para este contato.
- **Rótulo do Link C** Rótulo para um link adicional para este contato.
- **URL do Link C** A URL do link adicional para este contato.
- **Rótulo do Link D** Rótulo para um link adicional para este contato.
- **URL do Link D** A URL do link adicional para este contato.
- **Rótulo do Link E** Rótulo para um link adicional para este contato.
- **URL do Link E** A URL do link adicional para este contato.
- **Layout** Usar um layout diferente do fornecido na visualização do componente ou substituições nos templates.

### Aba Formulário

![Aba Editar Contato](../../../ptbr/images/contacts/contacts-edit-form-tab.png)

- **Formulário de Contato** Exibir ou ocultar o formulário de E-mail. Se Mostrar for selecionado, um formulário será exibido, permitindo que o usuário envie um e-mail para o Contato a partir do site.
- **Enviar Cópia para o Remetente** Exibir ou ocultar a caixa de seleção: *Enviar uma cópia desta mensagem para seu próprio endereço.*
- **Verificação de Sessão** Verificar a existência de cookie de sessão. Isso significa que usuários sem cookies habilitados não poderão enviar e-mails.
- **Resposta Personalizada** Desativa a resposta automatizada, permitindo que Plugins tratem da integração com outros sistemas.
- **Redirecionamento de Contato** Insira uma URL alternativa, para onde o usuário será redirecionado após o envio do e-mail.

*Traduzido por openai.com*

