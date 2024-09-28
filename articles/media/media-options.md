<!-- Filename: Help4.x:Media:_Options  / Display title: Mídia: Opções -->

## Descrição

A página *Mídia: Opções* é usada para definir os parâmetros globais de mídia.

### Elementos Comuns

Alguns aspectos desta página são cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

- Selecione **Conteúdo → Mídia** no menu do Administrador.
- Selecione o botão **Opções** na Barra de Ferramentas.

## Captura de Tela

![Opções de Mídia](../../../ptbr/imagens/midia/opcoes-de-midia.png)

## Campos de Formulário

### Mídia

- **Tamanho Máximo (em MB)** Use zero para sem limite. Nota: O servidor tem
  um limite máximo.
- **Caminho para a Pasta de Arquivos** Insira o caminho para a pasta de arquivos relativo
  à raiz do seu espaço web. Não comece o caminho com uma barra.
  Alterar para outro caminho que não o padrão *images* pode quebrar seus links.
- **Caminho para a Pasta de Imagens** Insira o caminho para a pasta de imagens
  relativo à raiz do seu espaço web. Não comece o caminho com uma barra.
- **Restringir Envios** Restringir envios para usuários com permissão inferior à de gerente para
  imagens se `Fileinfo` ou `MIME Magic` não estiver instalado.
  - **Extensões Permitidas** Restringir envios para usuários com permissão inferior à de gerente
    para arquivos na lista.
  - **Verificar Tipos MIME** Use `Fileinfo` ou `MIME Magic` para tentar
    verificar arquivos. Tente desativar isso se você receber erros de tipo MIME inválido.
- **Extensões de Imagem Legais (Tipos de Arquivo)** Extensões de imagem (tipos de arquivo)
  que você tem permissão para enviar (separadas por vírgulas). Estas são usadas para verificar
  cabeçalhos de imagem válidos e para selecionar imagens.
- **Extensões de Áudio Legais (Tipos de Arquivo)** Extensões de áudio (tipos de arquivo)
  que você tem permissão para enviar (separadas por vírgulas). Estas são usadas para verificar
  cabeçalhos de áudio válidos e para selecionar arquivos de áudio.
- **Extensões de Vídeo Legais (Tipos de Arquivo)** Extensões de vídeo (tipos de arquivo)
  que você tem permissão para enviar (separadas por vírgulas). Estas são usadas para verificar
  cabeçalhos de vídeo válidos e para selecionar vídeos.
- **Extensões de Documentos Legais (Tipos de Arquivo)** Extensões de documentos (tipos de arquivo)
  que você tem permissão para enviar (separadas por vírgulas). Estas são usadas para
  verificar cabeçalhos de documentos válidos e para selecionar documentos.
- **Extensões Ignoradas** Extensões de arquivo ignoradas para verificação de tipo MIME
  e envios restritos.
- **Tipos MIME Legais** Uma lista separada por vírgulas de tipos MIME legais para envio.

## Dicas

- Se você é um usuário iniciante, pode apenas manter os valores padrão aqui
  até aprender mais sobre como usar as opções globais.
- Se você é um usuário avançado, pode economizar tempo criando bons
  valores padrão aqui.

*Traduzido por openai.com*

