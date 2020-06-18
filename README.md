# seguranca-para-desenvolvedores
Livro de desenvolvimento seguro


# Desenvolvimento seguro

Diferença entre desenvolvimento seguro e devsecops
- oq é devops
- oq é appsec
- mindset de desenvolvimento seguro
- sobre o curso, não tem certificação, não tem uma sequencia logica baseado no SDLC nem nada relacionado a complice e afim, apenas melhorar o pensamento logico na hora de desenvolver software.

# OWASP e suas ferramentas

- OWASP
- Top 10
- Outra ferramentas interessantes

# Alinhar conceitos
- Introdução e Editor de texto favorito
- Linguagens, utilize a sua favorita, mas aqui teremos exemplos em Golang, javascript e python.
- Docker e Docker Compose
- Conceitos da web

# Conceitos da web
- HTML
- Protocolo HTTP
- REST??
- HTTP Headers
- Status Code
- http authentication
- Server Side Rendering
- o que é uma sessão
- Como o navegador se comporta
- Javascript e css
- SPA

# Introdução as atividades
Fazer cada item do Top 10 nesta sequencia, primeiro criamos uma aplicação vulneravel, depois exploramos a vuln e depois reescrevemos a aplicação para ser a prova das explorações.

# A1 - Injection
- Desenvolvendo um gerenciador de crushs(Nome, Minibio, Cel)
- Explorando SQL Injection no gerenciador(Descobrir os nomes e cel, baixar o banco)
- Automatizando o ataque
- Security Code Review (arruma o problema e depois testa com o ataque automatizado para ver se ainda esta vulneravel)

- Desenvolvendo um bot que faz contas(bot do telegram que executa contas matematicas)
- Explorando Command Injection no bot(eval, listando diretorios do servidor, pegando as variaveis de ambiente)
- Automatizando o ataque
- Security Code Review

- Desenvolvendo uma API REST de filmes
- Explorando NoSQL Injection(Baixar dados, drop no banco e deixar msg de resgate)
- Automatizando o ataque
- Security Code Review

# A2 - Broken Authentication
- Cookies e JWT
- Desenvolvendo paginas restritas por login
- Explorando Session Hijacking e Fixation(Token não expira apos o logout)
- Explorando JWT Brute Force
- Automatizando os ataques
- Security Code Review

# A3 - Sensiteve Data Exposure
- Desenvolvendo um sitezinho estatico(servindo arquivos publicos e outros nem tão publicos)
- Encontrando os arquivos nem tão ocultos assim
- Security Code Review

- Explorando o login(A1 e A3 ao mesmo tempo, sql injection e senha em plain text)
- Security Code Review

# 4 - XXE
