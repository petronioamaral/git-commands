```
#Na pasta
~git init

# ver status
~git status

#setar pasta atual
~git add .

~git remote add <SOMENAME> <URL>

# onde está apontando
~git remote -v 

#fazer commit com descrição
~git commit -m "Descricao"

#enviar realmente
~git push <NAMESERVER> master 

#ver quem alterou arquivos
~git blame -w -L 1,12 nome-do-arquivo

#listar branchs (tipo nome de usuario)
~git branch -a 

#listar branchs (tipo nome de usuario)
~git branch 

#apagar branch remota (tipo nome de usuario)
~git push origin -d minha-branch 

# renomear branch 01
~git branch -m nome-atual novo-nome 

# fazer o push com o novo nome branch 02
~git push origin :nome-atual novo-nome 

# finalizar a alteração do nome branch 03
~git push origin -u novo-nome 

#renomear repositorio
~git remote rename nome-atual novo-nome 

#remove repositorio remoto
~git remote rm origin 

#enviando novos
~git add -A
~git commit -m "DESCRICAO"
~git push <SOMENAME> master

************************************************************************

# criar nova branch
~git checkout -b funcionalidade_x 

# voltar para master
~git checkout master 

# remover branch
~git branch -d funcionalidade_x 

#listar branchs
~git branch 

Fazer o commit sempre antes de começar a usar os arquivos.

# criar nova branch
~git checkout -b funcionalidade_x 
~git add .
~git commit -m "Descriçao"

#voltar para master
~git checkout master 

#listar branchs
~git branch 

#merge
~git merge funcionalidade_x  

# remover branch
~git branch -d funcionalidade_x 
