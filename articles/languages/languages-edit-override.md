<!-- Filename: Help4.x:Languages:_Edit_Override  / Display title: Idiomas: Editar Substituição -->

## Descrição

No código do Joomla, as cadeias de texto que devem aparecer na Interface do Usuário, seja a interface do Site ou a interface do Administrador, são expressas como constantes de cadeia. Por exemplo, a cadeia de texto *Sua sessão expirou. Por favor, faça login novamente.* é expressa como `JLIB_ENVIRONMENT_SESSION_EXPIRED`. A cadeia de texto pode ser traduzida para qualquer idioma. O idioma padrão é o inglês britânico. Existem milhares dessas cadeias em uma instalação do Joomla.

Se uma cadeia não for adequada para o seu site, você pode usar o recurso de Substituição de Idioma para substituir a original. A página *Idiomas: Substituições* mostra uma lista de substituições existentes, portanto, ela está vazia inicialmente.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como Acessar

- Selecione **Sistema → Gerenciar Painel → Substituições de Idioma**. Em seguida...
  - Selecione um **Idioma e Cliente** na lista suspensa. Em seguida...
    - Selecione o botão **Novo** na Barra de Ferramentas para criar uma nova substituição.
      Ou...
    - Selecione o link da constante na coluna **Constante** para editar uma
      substituição existente.

## Captura de Tela

![Substituição de Edição de Idiomas](../../../ptbr/images/languages/languages-edit-override.png)

## Campos de Formulário

### Painel Direito: Pesquisar texto que você deseja alterar

- **Procurar Por** Comece aqui! Você provavelmente conhece o Valor
  (expirado) mais do que a Constante (`_EXPIRED`). Em qualquer caso, a busca é
  insensível a maiúsculas e minúsculas para a string parcial.
- **Texto de Busca** Insira o texto para pesquisar e selecione o botão *Buscar*.
- **Resultados da Busca** Uma lista de strings contendo o termo de busca
  aparece em um painel de Resultados separado abaixo do painel Direito. Selecione o 
  que você está procurando. A constante e o texto serão copiados para o 
  *painel esquerdo* para serem atualizados e salvos.

### Painel Esquerdo: Criar uma Nova Substituição ou Editar esta Substituição

- **Idioma** e **Localização** Estes foram selecionados antes de abrir este
  formulário de edição e não podem ser alterados.
- **Constante de Idioma** Esta é a string usada no código pelo
  desenvolvedor. Se o valor não existir no código, a string nunca será
  utilizada.
- **Texto** É aqui que você substitui o termo padrão pela sua
  versão.
- **Para Ambas as Localizações** Selecione para aplicar a substituição tanto no front-end quanto
  no back-end.
- **Arquivo** Isso mostra onde o arquivo de substituição está localizado no sistema de arquivos.
  Você pode precisar saber disso para a resolução de problemas.

*Traduzido por openai.com*

