<!--
{
    "source": "https://docs.joomla.org/Help5.x:Site_Modules:_Articles",
    "title": "M\u00f3dulos: Artigos",
    "description": " ",
    "author": ""
}
-->

## Descrição

O módulo **Artigos** exibe uma lista de artigos. Ele foi projetado para substituir
cinco outros módulos de artigos:

* [Módulos: Artigos - Arquivados](jdocmanual?article=help/modules-site/site-modules-articles-archived).
* [Módulos: Artigos - Categoria](jdocmanual?article=help/modules-site/site-modules-articles-category).
* [Módulos: Artigos - Mais Recentes](jdocmanual?article=help/modules-site/site-modules-articles-latest).
* [Módulos: Artigos - Mais Lidos](jdocmanual?article=help/modules-site/site-modules-articles-most-read).
* [Módulos: Artigos - Destaques](jdocmanual?article=help/modules-site/site-modules-articles-newsflash).

As opções do módulo **Artigos** são configuradas principalmente por meio de quatro abas:

- A *Aba de Opções de Filtragem* é usada para especificar quais artigos são exibidos.
- A *Aba de Opções de Exibição* especifica como os artigos são exibidos no módulo e quais detalhes são incluídos.
- A *Aba de Opções de Ordenação* é usada para configurar a precedência dos artigos.
- A *Aba de Opções de Agrupamento* é usada para configurar a precedência dos artigos.

**Importante:** O módulo só aparece quando há um ou mais artigos correspondentes para exibir. Se estiver vazio, o módulo não aparecerá.

### Elementos comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A aba Módulos: Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [A aba Módulos: Atribuição de menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [A aba Módulos: Avançado](jdocmanual?article=help/modules/modules-advanced-tab).
* [A aba Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como acessar

- Selecione **Conteúdo → Módulos do site** ou **Sistema → Painel de gerenciamento → Módulos do site**
  no menu do Administrador ou **Painel do site → Módulos** no Painel inicial.
  Em seguida...
  - Para criar um novo módulo: selecione o botão **Novo** na Barra de ferramentas da lista
    *Módulos*. Em seguida...
     - Selecione o módulo **Artigos**.
  - Para editar um módulo existente: localize o módulo na lista de módulos instalados
    e selecione o link do título na coluna **Título**.

## Captura de tela

![Aba do módulo do formulário do módulo Artigos](../../../ptbr/images/modules-site/site-modules-articles/01-module-tab.png)

## Campos do formulário

### Aba Módulo

#### Painel esquerdo

- **Modo**
  - O *Modo normal* configura o módulo para exibir uma lista estática de artigos.
  - O *Modo dinâmico* configura o módulo para detectar se ele está usando ou não uma visualização de categoria e exibirá a lista de artigos dentro dessa categoria de acordo com isso. Quando o Modo dinâmico é escolhido, é melhor deixar o módulo configurado para exibir em todas as páginas, pois ele decidirá dinamicamente se deve ou não exibir algo.
- **Artigos a exibir** O número máximo de artigos a serem exibidos.
- **Tipo de filtragem de categoria** Especifica como os artigos são filtrados com base nas categorias fornecidas no campo *Categoria*.
  - *Inclusivo* Somente artigos das categorias especificadas são exibidos.
  - *Exclusivo* Artigos das categorias especificadas são excluídos.
- **Categoria** Exibe ou exclui artigos das categorias selecionadas. Isso funciona juntamente com outros parâmetros de filtragem.
- **Artigos de categorias filhas** Visível somente quando o parâmetro *Excluir ou incluir artigos* está definido como *Incluir*. Inclui ou exclui artigos de categorias que são subcategorias das categorias fornecidas no campo *Categoria*.
- **Profundidade da categoria** Visível somente quando o parâmetro *Artigos de categorias filhas* está definido como *Incluir*. Especifica quantos níveis de subcategorias são usados.
- **Excluir ou incluir artigos** Inclui ou exclui artigos específicos.
- **Artigos a incluir** Visível somente quando o parâmetro *Excluir ou incluir artigos* está definido como *Incluir*. Se estiver vazio, todos os artigos serão incluídos; caso contrário, somente os artigos selecionados serão incluídos.
- **Excluir artigo atual** Visível somente quando o parâmetro *Excluir ou incluir artigos* está definido como *Excluir*. Exclui ou inclui o artigo atual.
- **Artigos a excluir** Visível somente quando o parâmetro *Excluir ou incluir artigos* está definido como *Excluir*. Especifica os artigos a serem excluídos da lista.

### Aba Opções de Exibição

![Aba do módulo de formulário do módulo de artigos](../../../ptbr/images/modules-site/site-modules-articles/02-display-options-tab.png)

- **Somente título (listas)** (*Sim/Não*). Se *Sim*, a lista de artigos consiste apenas nos títulos dos artigos, vinculados ao artigo. Todas as outras opções ficam ocultas.
- **Layout**
  - *Vertical* Os artigos aparecem em uma única coluna vertical.
  - *Horizontal* Os artigos aparecem em no máximo 1 a 4 colunas verticais, dependendo da largura do módulo; a largura do módulo é determinada pela posição do módulo, pelo layout da página, pelo template, pela largura da tela, pela largura de visualização do navegador e por outros fatores.
- **Número máximo de colunas** Esta opção aparece somente quando o Layout está definido como Horizontal. Ela especifica o número máximo de colunas em um layout horizontal (*2–4*).
- **Título do artigo** Mostra ou oculta o título do artigo.
- **Nível do cabeçalho** Esta opção aparece somente quando *Título do artigo* está definido como *Mostrar*. Ela especifica o nível do título HTML do artigo (*h1–h5, nenhum*).
- **Link do título** Esta opção aparece somente quando *Título do artigo* está definido como *Mostrar*.
  - *Sim* O título é um hiperlink para o artigo.
  - *Não* O título não é um hiperlink para o artigo.
- **Autor** Mostra ou oculta o autor do artigo.
- **Categoria** Mostra ou oculta a categoria do artigo.
- **Link da categoria** Aparece somente se *Categoria* estiver sendo exibida.
  - *Mostrar* Vincula o título da categoria à página da categoria.
  - *Ocultar* Mostra o título da categoria, mas não o vincula.
- **Data** Mostra ou oculta a data do artigo.
- **Campo de data** Esta opção aparece somente quando *Data* está definida como *Mostrar*. Ela especifica qual data do artigo será exibida: *Data de criação/Data de modificação/Data de início da publicação*.
- **Formato da data** Esta opção aparece somente quando *Data* está definida como *Mostrar*. Ela especifica o formato da data, por exemplo, Y-m-d H-i-s. Consulte o [manual do PHP](https://www.php.net/manual/en/datetime.format.php) para obter informações sobre formatação.
- **Visualizações** Mostra ou oculta o número de vezes que o artigo foi visualizado.
- **Layout das informações do artigo** Aparece somente se um dos campos de metadados acima (*Autor, Categoria, Data ou Visualizações*) estiver sendo exibido. Especifica como os metadados do artigo são exibidos:
  - *Multilinha* Cada parâmetro é exibido em sua própria linha.
  - *Linha única* Os parâmetros aparecem lado a lado em uma única linha, que pode ser quebrada dependendo do tamanho deles e da largura do módulo.
- **Tags** Mostra ou oculta as tags de um artigo.
- **Acionar eventos de plugins** Defina como *Sim* para acionar eventos adicionais de plugins e exibir conteúdo adicional, como campos personalizados ou informações de votação.
- **Texto introdutório** Mostra ou oculta o texto introdutório do artigo. A quantidade de texto exibida é controlada pelo *parâmetro Limite do texto introdutório (caracteres)*.
- **Limite do texto introdutório (caracteres)** Esta opção aparece somente quando *Texto introdutório* está definido como *Mostrar*. Ela especifica o número de caracteres introdutórios exibidos. Se definida como 0, o texto do artigo inteiro é exibido.
- **Mostrar imagens do artigo** Esta opção aparece somente quando *Texto introdutório* está definido como *Mostrar* e o *Limite do texto introdutório (caracteres)* está definido como zero (o que exibe o texto completo do artigo). Se definida como *Mostrar*, as imagens do artigo são exibidas junto com o texto.
- **Mostrar imagem introdutória/completa** Exibe a imagem introdutória do artigo, a imagem completa ou nenhuma imagem acima do título e dos detalhes do artigo.
- **Link "Leia mais"** Mostra ou oculta um link "Leia mais" abaixo dos detalhes do artigo.
- **Leia mais com título** Esta opção aparece somente quando a opção *Leia mais* está definida como *Mostrar*. Ela adiciona o título ao link *Leia mais*.
- **Limite de "Leia mais" (caracteres)** Esta opção aparece somente quando a opção *Leia mais com título* está definida como *Mostrar*. Ela especifica o número máximo de caracteres do título que aparecerão no link *Leia mais*.

### Aba Opções de Filtragem

![Aba do módulo de formulário do módulo de artigos](../../../ptbr/images/modules-site/site-modules-articles/03-filtering-options-tab.png)

- **Artigos em Destaque**
  - *Exibir* Permite que artigos em destaque apareçam na lista.
  - *Ocultar* Exclui artigos em destaque da lista.
  - *Somente* Exibe somente artigos em destaque na lista.
- **Artigos Arquivados** Especifica como os artigos arquivados aparecem na lista.
  - *Nenhum* Exclui artigos arquivados da lista.
  - *Somente* Exibe somente artigos arquivados na lista.
- **Tags** Se especificado, restringe a lista somente aos artigos que têm uma ou mais das tags especificadas.
- **Tipo de Filtragem por Autor** Filtra a lista por autor.
  - *Inclusivo* Restringe a lista somente aos artigos dos autores especificados.
  - *Exclusivo* Exclui artigos do autor especificado.
  - *Somente do usuário atual* Exibe somente artigos de autoria do usuário atual.
- **Autores** Lista de autores a incluir ou excluir. 
- **Tipo de Filtragem por Alias do Autor** Filtra a lista por alias do autor.
  - *Inclusivo* Restringe a lista somente aos artigos dos aliases de autor especificados.
  - *Exclusivo* Exclui artigos dos aliases de autor especificados.
- **Aliases de Autor** Lista de aliases de autor a incluir ou excluir. 
- **Filtragem por Data** Especifica como os artigos são filtrados por data.
  - *Desativada* Nenhuma filtragem por data.
  - *Intervalo de Datas* Restringe a lista aos artigos com datas dentro do intervalo de datas especificado. 
  - *Data Relativa* Restringe a lista aos artigos que estejam dentro de um número especificado de dias da data atual.
- **Campo do Intervalo de Datas** Esta opção aparece somente quando *Filtragem por Data* está definida como *Intervalo de Datas* ou *Data Relativa*. Especifica qual data do artigo deve ser usada na filtragem por data (*Data de Criação/Data de Modificação/Data de Início da Publicação*).
- **Início do Intervalo de Datas** Esta opção aparece somente quando *Filtragem por Data* está definida como *Intervalo de Datas*. Especifica a data e a hora de início do filtro de intervalo de datas.
- **Até a Data** Esta opção aparece somente quando *Filtragem por Data* está definida como *Intervalo de Datas*. Especifica a data e a hora de término do filtro de intervalo de datas.
- **Data Relativa** Esta opção aparece somente quando *Filtragem por Data* está definida como *Data Relativa*. Especifica o número de dias relativos à data atual a serem incluídos na lista de artigos.

### Aba Opções de Ordenação

![Aba do módulo de formulário do módulo de artigos](../../../ptbr/images/modules-site/site-modules-articles/04-ordering-options-tab.png)

- **Campo do Artigo para Ordenação**
  - *Ordem do Artigo* A ordem na qual os artigos são organizados manualmente na tela *Conteúdo > Artigos* da área administrativa.
  - *Ordem dos Artigos em Destaque* A ordem na qual os artigos em destaque são organizados na tela *Conteúdo > Artigos em Destaque* da área administrativa.
  - *Visualizações* Ordenados pelo número de visualizações da página.
  - *Título* Ordenados pelo título do artigo.
  - *ID* Ordenados pelo número de ID do artigo.
  - *Alias* O alias de navegação do artigo.
  - *Data de Criação/Data de Modificação/Data de Início da Publicação/Data de Término da Publicação* Ordenados pela data do artigo.
  - *Aleatório* Ordenação aleatória sempre que a página é acessada ou atualizada. *Direção da Ordenação* é ignorada.

### Aba Opções de Agrupamento

![Aba do módulo de formulário do módulo de artigos](../../../ptbr/images/modules-site/site-modules-articles/05-grouping-options-tab.png)

Os campos *Campo de Agrupamento por Data* e *Formato de Exibição do Mês e Ano* ficam visíveis somente quando um agrupamento relacionado a datas é selecionado.

- **Agrupamento de Artigos**
  - *Nenhum* Sem agrupamento.
  - *Ano* Exibe o ano como título.
  - *Mês e Ano* Exibe o mês e o ano como título.
  - *Autor* Exibe *Alias do Autor* ou *Autor* como título. 
  - *Categoria* As categorias aparecem como títulos.
  - *Tags* As tags aparecem como títulos. Artigos com várias tags aparecem sob vários títulos.
- **Campo de Agrupamento por Data** Exibido somente quando *Ano* ou *Mês e Ano* está selecionado. A data do artigo pela qual agrupar (*Data de Criação/Data de Modificação/Data de Início da Publicação*).
- **Formato de Exibição do Mês e Ano** Exibido somente quando *Ano* ou *Mês e Ano* está selecionado. Especifica como exibir o título do mês e do ano. Consulte o [manual do PHP](https://www.php.net/manual/en/datetime.format.php) para obter informações sobre formatação.
- **Direção do Agrupamento** Especifica como ordenar os títulos dos grupos (*Crescente/Decrescente*).

## Captura de tela do front-end

*As imagens de exemplo do site do front-end foram obtidas com o template Cassiopeia.*

Módulo de artigos na barra lateral direita mostrando apenas os títulos.

![Captura de tela do site com o módulo mostrando apenas os títulos dos artigos](../../../en/images/modules-site/site-modules-articles/06-site-titles.png)

Módulo de artigos na barra lateral direita mostrando título, autor e data.

![Captura de tela do site com o módulo mostrando título, autor e data dos artigos](../../../en/images/modules-site/site-modules-articles/07-title-author-date.png)

Módulo de artigos na posição principal superior mostrando texto introdutório e imagem, além de um botão *Leia mais*.

![Captura de tela do site com o módulo na posição superior e o botão leia mais](../../../en/images/modules-site/site-modules-articles/08-top-text-image-readmore.png)

Módulo de artigos na posição principal superior configurado para um layout horizontal com texto introdutório e imagem, além de um botão *Leia mais*.

![Captura de tela do site com o módulo mostrando o texto introdutório do artigo, a imagem e o botão leia mais](../../../en/images/modules-site/site-modules-articles/09-text-image-readmore.png)

## Exemplos de configuração

O módulo de artigos exibe uma lista de artigos em uma variedade de formatos e layouts. Ele foi projetado com o objetivo de criar um único módulo altamente configurável, capaz de substituir a funcionalidade limitada de cinco módulos de artigos separados. Esta seção oferece exemplos simples de como configurar o módulo para cada uma dessas funções.

## Artigos - Arquivados

O módulo *Artigos - Arquivados* exibe uma lista de títulos de mês/ano para os meses que contêm artigos arquivados. O título é um link para a visualização de artigos arquivados, na qual os artigos individuais são exibidos. O módulo *Artigos* pode ser configurado para obter um resultado semelhante.

**Configurações**

| Aba               | Parâmetro          | Configuração |
|-------------------|--------------------|---------|
| Opções de exibição   | Apenas título (listas) | Sim     |
| Opções de filtragem | Artigos arquivados  | Somente    |
| Opções de agrupamento  | Agrupamento de artigos   | Mês e ano |
| Opções de agrupamento  | Formato de exibição de mês e ano | F, Y |

![Comparação de artigos arquivados usando cada método](../../../en/images/modules-site/site-modules-articles/10-config-archived.png)

<big>*Observações*</big>

O módulo *Artigos - Arquivados* exibe um único link para uma página de artigos arquivados que mostra a lista de artigos arquivados, além da possibilidade de ajustar a data do arquivo. O módulo *Artigos* exibe a lista de artigos diretamente — o agrupamento por mês e ano é opcional. A lista pode ser filtrada com precisão usando os vários controles disponíveis, e há uma ampla variedade de opções de exibição para mostrar detalhes adicionais dos artigos. 

## Artigos - Categoria

O módulo *Artigos - Categoria* exibe uma lista de links para artigos dentro de uma categoria especificada.

**Configurações**

| Aba             | Parâmetro          | Configuração |
|-----------------|--------------------|----|
| Módulo          | Categoria           | [especifique a categoria e as subcategorias desejadas]|
| Opções de exibição | Apenas título (listas) | Sim |

![Comparação de artigos por categoria usando cada método](../../../en/images/modules-site/site-modules-articles/11-config-category.png)

## Artigos - Mais recentes

O módulo *Artigos - Mais recentes* exibe uma lista de links para os artigos mais recentes.

**Configurações**

| Aba              | Parâmetro          | Configuração |
|------------------|--------------------|----|
| Opções de exibição  | Apenas título (listas) | Sim |
| Opções de ordenação | Campo do artigo para ordenar por | Data de início da publicação|
| Opções de ordenação | Direção da ordenação | Decrescente |

![Comparação dos artigos mais recentes usando cada método](../../../en/images/modules-site/site-modules-articles/12-config-latest.png)

<big>*Observações*</big>

O módulo *Artigos* não oferece a ordenação por *Acessado*, encontrada no módulo *Artigos - Mais recentes*, mas oferece várias opções de ordenação que não estão disponíveis no módulo *Artigos - Mais recentes*. 

## Artigos - Mais lidos

O módulo *Artigos - Mais lidos* exibe uma lista de links para os artigos com mais acessos.

**Configurações**

| Aba              | Parâmetro          | Configuração |
|------------------|--------------------|----|
| Opções de exibição  | Apenas título (listas) | Sim |
| Opções de ordenação | Campo do artigo para ordenar por | Acessos |
| Opções de ordenação | Direção da ordenação | Decrescente |

![Comparação dos artigos mais lidos usando cada método](../../../en/images/modules-site/site-modules-articles/13-config-most-read.png)

## Artigos - Newsflash

O módulo *Artigos - Newsflash* exibe o texto de um ou mais artigos. Por padrão, somente o texto do artigo é exibido; no entanto, ele pode ser configurado para exibir o título, imagens, links de leia mais e muito mais. Aqui, ele está configurado para exibir o título título e o texto de vários artigos. Neste exemplo, o módulo *Artigos* está configurado para replicar esse comportamento básico.

**Configurações**

| Aba              | Parâmetro          | Configuração |
|------------------|--------------------|----|
| Opções de ordenação | Campo do artigo para ordenar por | Data de início da publicação |
| Opções de ordenação | Direção da ordenação | Decrescente |
| Opções de exibição  | Somente título (listas) | Não |
| Opções de exibição  | Link do título         | Não |
| Opções de exibição  | Texto introdutório          | Exibir |
| Opções de exibição  | Limite do texto introdutório (caracteres) | 0 (para texto ilimitado) |

![Comparação de artigos em formato newsflash usando cada método](../../../en/images/modules-site/site-modules-articles/14-config-news-flash.png)

*Traduzido por openai.com*