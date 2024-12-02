Chave SSH e Token

Para jogar os códigos na nuvem tem necessidade de autenticar dados


Chave SSH
 É uma forma de fazer uma conexão segura e encriptada, com 2 chaves 1 pública e 1 privada.

Comando para gerar as chaves:

	ssh-keygen -t ed25519 -C cbsouzasilva13@gmail.com

Inicializar a chave
	eval $(ssh-agent -s)

Entregar a chave agora
	ssh-add id_25519 chave Privada

Para clonar um repositório da forma correta utilizando o SSH 
	git clone + chave SSH do repositório

Token de acesso virtual

neste caso para clonar usar o HTTPS ex: https://github.com/twentyhq/twenty.git