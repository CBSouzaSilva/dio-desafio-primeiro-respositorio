Módulo 6 - introdução ao GitHub

​	Trabalhando com o Github

comando para verificar a lista de todas as configurações e o autor registrado e o email:

​	git config –list

Como para desatribuir o autor e o email do autor:

​	git config –global –unset user.email

​	git config –global –unset unser.name

Comandos para configurar o autor e o email:

git config –global user.email “cbsouzasilva13@gmail.com”

​	git config –global unser.name “CBSouzaSilva”

Após criar a conta no GitHub, fazer as devidas adequações do nome do autor e email seguimos.

Criar um repositório no Github e indicar o repositório que estamos trabalhando na maquina local via https

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcbmeNeDkZSlmT5pRw2qtQQRwtHqxBSeTh5KSGM4IbiZJCtVl8lHezHxQB8oPseb2esL4EzpP0Zt2b8FevQd7PmPvetT8W9gZf-fMAZH8aL3l1IB4Ssyn6_rdbdTSFayqqr4G2-HA?key=4DZlgj9eXLod8yPXfvMCkC3r)

comando no pc, primeiro adicionar a origem:

​	git remote add origin [git@github.com](mailto:git@github.com):CBSouzaSilva/livro-receitas.git

Comando para listar a lista de repositórios remotos:

​	git remote -v

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd_pgkUtR-eKzD4LJV8ysQk_eAILUsAq5_IuJM1NMfdF4FtGK6SdwwNYyKpRyABFez9dBwkKSgx7N91PmPNLH7MNTa8KI-ZJCeNJnEHyRypw_Uk-PMJ1PXnoEE9iLlZyjlB1cB3?key=4DZlgj9eXLod8yPXfvMCkC3r)

Comando para levar o código do repositório local para o remoto:

​	git push origin master

vai pedir a senha cadastrada (no meu caso para teste 123456)

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdScBwd9nccXeMLi2NOo98xasKBfc8FbRbHSHFhKZpmNBVgp5DkRQ0bpRLVSgbzJu3J52WT0pOXHLgRTVaZ7DFXSDxcMMsfmFFwqCSRyyceVCbV-b-9k0Pqk5mXjU48B-duzsrVqw?key=4DZlgj9eXLod8yPXfvMCkC3r)