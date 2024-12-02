Módulo 4 - Primeiros COmando com Git

iniciando o Git e Criando um commit 

Iniciar o GIT			git init
Iniciar o versionamento	git add
Criar um Commit		git commit

Iniciar um repositório Git			git init
Iniciar o versionamento			git add
Criar um commit				git commit


	qual lidar com o terminal sempre colocar o nome do programa na frente, no caso o git usa git e o comando referente logo a frente.

 Criando um repositório:
	mkdir livro-receitas
após criado entrar na pasta
	cd livro-receitas
iniciar o repositório ( este comando cria uma pasta oculta que é utilizada pelo git para gerenciar para visualizar precisa de uma fleg específica ls -a
	git init

Realizando uma configuração inicial:

	caso seja a primeira vez precisa fazer umas primeiras configurações básicas.
	git config –global user.email “cbsouzasilva13@gmail.com
	git config –global user.name IvanMSS

Adicionando um arquivo ( markdown): .md
tamanho da fonte neste caso é definido desta forma:
	# Título nível 1
	## Título nível 2
	### Título nível 3
	#### Título nível 4
##### Título nível 5


Flags para pasta oculta = ls -a

Configurando o email do autor do projeto:
git config –global user.email “cbsouzasilva13@gmail.com”
git config –global user.name Ivan

git add *
git commit -m “commit inicial”
[master (root-commit) 815cc64] commit inicial
 1 file changed, 34 insertions(+)
 create mode 100644 strogonoff.md
