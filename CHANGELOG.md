# Changelog

Todas as mudancas relevantes deste projeto estao documentadas aqui.

## [v1.0] - 05/10/2026
### Adicionado
- Pagina de mensagem de erro (msg.html) exibida quando o usuario fica em branco.
- Pagina inicial do operador (pg002.html).
- Validacao do campo usuario no login: vazio -> erro; "admin" -> administrador;
  qualquer outro valor -> operador.
### Corrigido
- Usuario contendo apenas espacos em branco era aceito como preenchido (trim).

## [v0.2] - 05/10/2026
### Adicionado
- Pagina inicial do administrador (pg001.html).
- Login chamando o administrador sem validacao de campos.

## [v0.1] - 05/10/2026
### Adicionado
- Pagina de login (index.html).
- Pagina de aviso "em construcao" (working.html).
