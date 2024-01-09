Criar branch a partir da atual:
  git checkout -b <branch-name>

Listar branches:
  git branch --list
  git branch

Renomear branch:
  git branch -m <nome-antigo> <novo-nome>

Deletar branch (LOCAL):
  git branch -d <nome-da-branch>
  force: git branch -D <nome-da-branch>

Deletar branch (REMOTA):
  git push origin -d <nome-da-branch>

Subir uma branch:
  git push --set-upstream origin <nome-da-branch-nova>

Adicionar um arquivo para stagged:
  git add <caminho-do-arquivo>

Commitar arquivos em stagged:
  git commit -m "<sua-mensagem>"

Subir para a nuvem seus arquivos
  git push -u

