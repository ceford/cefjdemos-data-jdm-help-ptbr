<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Tour  / Display title: Tours Guiados: Editar Tour -->

## Descrição

Esta página é usada para adicionar um novo Tour ou editar um Tour existente. Um Tour deve incluir pelo menos um passo. Uma vez que um Tour tenha sido recém-criado, vá para a lista de Tours e selecione o botão com o rótulo *0* da coluna Passos. O primeiro passo do Tour é automaticamente criado a partir do título e da descrição do Tour.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).

## Como Acessar

- Selecione **Sistema -> Gerenciar -> Tours Guiados** no menu do Administrador.
- Selecione o botão de ferramenta **Novo** para adicionar um tour.
- Selecione um **Título** da lista para editar um tour.

## Captura de Tela

![Guias de Tours Editar Tour](../../../ptbr/images/guided-tours/guided-tours-edit-tour.png)

## Campos do Formulário

- **Título** O Título desta excursão. Se o título é uma chave de idioma, um campo adicional é exibido, representando a tradução dessa chave para o idioma do usuário.
- **Identificador da Excursão** Um identificador único para a excursão. Ao *Salvar*, ou *Salvar como Cópia*, um valor é fornecido por padrão. Um formato sugerido seria *nomedoautor-nomedoexcurso*, *nomedaempresa-nomedoexcurso* ou *dominio-nomedoexcurso*. Esse identificador tem múltiplos propósitos: iniciar uma excursão de qualquer lugar (não apenas a partir do módulo de Excursões Guiadas), diferenciar excursões de diferentes origens, e em sites multilíngues, ele dita a estrutura dos nomes dos arquivos de idioma.

### Guia Editar Excursão

#### Painel Esquerdo

- **URL Relativa** O caminho relativo obrigatório de onde a excursão começa. Por exemplo, para iniciar uma excursão a partir da página da excursão, insira `administrator/index.php?option=com_guidedtours&view=tours`.
- **Descrição** Aqui você insere a descrição da excursão. A descrição da excursão pode ser uma chave de idioma. Quando esse é o caso, um campo secundário apresenta a descrição traduzida dessa chave para o idioma do usuário.

#### Painel Direito

- **Seletor de Componente** A excursão será visível prioritariamente nas páginas das extensões selecionadas. Use *Todos* para mostrar a excursão em todas as páginas. Quando configurado para *Todos*, a excursão é colocada por último na lista de excursões contextuais no menu suspenso do módulo. Este é um campo obrigatório.
- **Início Automático** Permite que a excursão inicie automaticamente quando um usuário alcançar o contexto no qual a excursão deve ser exibida.

## Dicas

- Existem 2 métodos para inserir uma imagem na descrição do tour usando o
  editor TinyMCE.
  1. A lista suspensa **Conteúdo CMS** fornece acesso à tela de **Mídia**
     que permite navegar pelos arquivos de imagem e fazer upload de imagens.
  2. A lista suspensa *Inserir* é um formulário simples para o qual você precisa
     conhecer a URL da imagem. É utilizada para imagens externas.
- Existem 2 maneiras de criar tours para ambientes multilíngues:
  1. Criar um tour para cada idioma suportado.
  2. Criar um único tour para todos os idiomas e usar chaves de idioma para o título
  e a descrição.
- Use **GUIDEDTOUR** nas chaves de idioma como convenção onde quer que as chaves
  de idioma sejam utilizadas (para título e descrição).

