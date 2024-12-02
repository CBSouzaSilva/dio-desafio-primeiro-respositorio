Módulo 5 Ciclo de vida dos arquivos no Git 

Passo a Passo no ciclo de vida

git init = inicializa um conceito do git chamado repositório

Tranked ou Untracked 

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcPQcbukMcmSX5WkI43p_sXxMtigCa507hPUxd8X3F71CJuuYLjLyv339Pz0Y_QwVsX28GzkLRgk8Vs-SK7pOY2-rHHO841pU4Yqb91-QoMFS9dvUEznt6_XVJS6jHiEvnCFOsUKg?key=RMwI6KQ_VHu_azibnE-SFwkP)

- Unmodified é o arquivo que ainda não foi modificado
- modified é o arquivo Unmodified que sofreu modificação
- Staged é um conceito chave - “aguardando para entrar em ação” - preparado para receber o commit após receber o commit ele o arquivo volta para Unmodified 

O que é um repositório?

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeTaNoyyOvUwRvzqQH6GGG-mJAqf5qq9_zJr3lXX3uJnupkzxAqNEJfS4lQx3Btb9Vd28TQ3CbCGnFyRySalTHItGyQst2m58xSokmlITSOpHfrnFJOTs-8g2FQ-Ua5xTatdNFdBA?key=RMwI6KQ_VHu_azibnE-SFwkP)

comando:

git status

​		On branch master

nothing to commit, working tree clean

criar outra pasta

mkdir receitas

mover a receita existente para dentro da pasta nova

​	mv strogonoff.md ./receitas/

após criar a pasta nova refazer os comando:

​	git status

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeKQ9mD0jaiPof-VWlp35NFq0lgaM3_aPOs4WYhFZCpkqDEBk_Pnoe5OY2IWfwsVvyPiTb6_hoKLoKIlIKmK1VOwO-a0b8bFBgtymMYlGsoUU0auM798-hvytwQA2gWU-HSU2_uwQ?key=RMwI6KQ_VHu_azibnE-SFwkP)	

Fizemos os comandos, movemos pastas e ainda não fizemos commit então o sistema ainda não reconhece todas as mudanças que fizemos, estão aguardando para tomar destino.

comando:

​	git add strogonoff.md receitas/

​	git status

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfPItPXE_hPYTAYeG4YSAOakrG3xubeDxGsBVQnKeD2u7BduzTOLpN5X9niBgkcVSeMC4bU2HQK0Ga4tpDfpw772AtcdrGPXamsSgipt2u_oXAkudwFg-rmZiJ9HaOBXyTnd-0W?key=RMwI6KQ_VHu_azibnE-SFwkP)

git commit -m “cria pasta receitas, move arquivos para receitas”

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfNiIYck5gHTFN0KTzHABmCkeRxA9CLJyukQTD63AmdifVb63UwBfldNpKBjFbQmH7yN21qB3mU-5H-sl6e6t6AjxL8RB7zcXOl_22YIYID5c_VbQ_yxW2r5AW7NUpLgF4YU9Vnzg?key=RMwI6KQ_VHu_azibnE-SFwkP)

adicionando mais 1 arquivo para fixar conhecimento:

​	echo > README.md

abrir o arquivo é digitar a capa da nossa pasta de receitas

mover o arquivo Untracked para stage 

​	git add * ( com o * pega tudo que está na zona de trabalho)

​	git status

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfVFJv8L1c3vWQN0-jr8Yj2Uh7127UNaudQxScrIfJ03AN69LSQ7G2dRIZBAqG_6ZcHsvqfqi2N7visHwSZ1cpy_YM-i8xK9W9Kktd4rnleBf7sBP-UBw7Gsa3lAumdrTy5qRbF?key=RMwI6KQ_VHu_azibnE-SFwkP)

​	git commit -m “adiciona indes”

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXesRhus8Q3FhpEenQCxprZs1hgdsNSDDpU7zmhQjRbFkKDXoqEC8dateP4H74awtpSwijxVigc_7HzbPQo361fCS1FXAoXMZ_Y-fjHjVng2aX6veZjzjKMHInHcUUw9m0xyr3tcMQ?key=RMwI6KQ_VHu_azibnE-SFwkP)

​	git status

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeB6LM7X1xLAPcO6BzmqB0ub2XPtYRLOyeeI8HAAoFaSEnCK7gFd9shk5nsAXIfd0maWG-dgq0kc0VG0NcKojI90yZ-9daLqcbkzxsC7Us3ld2g_8zcK-m3fIGZfifn9VeJ1isXpw?key=RMwI6KQ_VHu_azibnE-SFwkP)