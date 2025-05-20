# comandos_git
Comandos Git
git init -> inicia o repositório git localmente

git clone https://github.com/caaioces/comandos_git.git -> Clona o repositório do github

git branch nome-da-branch -> cria uma nova branch

git checkout nome-da-branch -> muda para outra branch

git status -> verifica quais arquivos pendentes para commit

git add . -> adiciona todos os arquivos modificados

git commit -m 'descricao do commit' -> envia o commit com a descricao

git push origin sua-branch -> envia o rep local para a branch remota

# MERGE da branch DEVELOP para a MAIN usando gitbash no windows

1 - Atualizar a branch develop local:

git checkout develop

git pull origin main

2 - Vá para a branch MAIN e atualize-a também

git checkout main

git pull origin main

3 - Faça o merge da develop na main

git merge develop

git add .
git commit

4 - Envie a main atualizada para o repositório remoto

git push origin main
