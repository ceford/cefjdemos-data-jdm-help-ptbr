<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group  / Display title: Grupo de Autenticação -->

## Descrição do Grupo

Os plugins neste grupo são usados para o login padrão do usuário nas interfaces do Site ou do Administrador. O padrão é a Autenticação Joomla. O método *Cookie* é utilizado em conjunto com a função *Lembrar-me* apenas para o login no Site. O cookie é configurado após o primeiro login com um dos outros métodos.

## Autenticação - Cookie

![plugin de autenticação por cookie](../../../en/images/plugins/plugin-group-authentication-cookie.png)

- **Tempo de Vida do Cookie** O número de dias até que o cookie de autenticação expire. Outros fatores podem fazer com que ele expire antes disso. Durações maiores são menos seguras.
- **Comprimento da Chave** O comprimento da chave usada para criptografar o cookie. Comprimentos maiores são mais seguros, mas podem diminuir o desempenho.

## Autenticação - Joomla

Este plugin processa o método de Autenticação de Usuário padrão no Joomla. Ele não possui opções.

## Autenticação - LDAP

Este plugin processa a autenticação de usuário contra um servidor LDAP.

![plugin de autenticação ldap](../../../en/images/plugins/plugin-group-authentication-ldap.png)

- **Host** A URL do host. Por exemplo, `openldap.minhaempresa.org`.
- **Port** O número da porta. O padrão é 389.
- **LDAP V3** Se este host usa ou não a versão 3 do LDAP. O padrão é LDAP v2.
- **Negociar TLS** Se deve ou não usar criptografia TLS com este host. Se definido como *Sim*, todo o tráfego de e para este servidor deve ser criptografado.
- **Seguir Referências** Se deve definir o parâmetro LDAP_OPT_REFERRALS como Sim ou Não. Para hosts Windows 2003, isso deve ser definido como Não.
- **Método de Autorização** *Bind Directly as User* ou *Bind and Search*.
- **Base DN** O Base DN do seu servidor LDAP.
- **Cadeia de Busca** Uma string de consulta usada para buscar um determinado Usuário. A palavra-chave `[search]` é substituída pelo login digitado pelo Usuário. Por exemplo: `uid=[search]`. Mais de uma Cadeia de Busca pode ser inserida. Separe cada uma com um ponto e vírgula `;`. Isso é usado apenas durante a busca.
- **DN do Usuário** A palavra-chave [username] é dinamicamente substituída pelo nome de usuário digitado pelo Usuário. Uma string de exemplo é: `uid=[username], dc=[meu-dominio], dc=[com]`. Mais de uma string pode ser inserida. Separe cada uma com um ponto e vírgula `;`. Isso é usado apenas se o Método de Autorização acima estiver definido como *Bind Directly as User*.
- **Conectar Nome de Usuário e Conectar Senha** Estes definem os parâmetros de conexão para a fase de lookup do DN. Para busca anônima, deixe ambos os campos em branco. Para uma Conexão Administrativa, o *Conectar Nome de Usuário* é o nome de usuário de uma conta administrativa (por exemplo, *Administrador*). Neste caso, a *Conectar Senha* é a senha real dessa conta administrativa.
- **Mapear: Nome Completo** O atributo LDAP que contém o nome completo do Usuário.
- **Mapear: Email** O atributo LDAP que contém o endereço de e-mail do Usuário.
- **Mapear: ID do Usuário** O atributo LDAP que contém o ID de login do Usuário. Para Active Directory, isso é `sAMAccountName`.
- **Depurar** Ativa a depuração codificada no nível 7.

*Traduzido por openai.com*

