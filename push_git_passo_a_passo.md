GIT PUSH - SCRIPT PARA SUBIR ARQUIVOS PARA O GIT HUB !!!


git init

git remote add origin https://github.com/isabelahidalgo/Projetos-Botcamp-JAVA-DIO.git

git add .

git commit -m "primeiro commit"

git branch -m master main

git pull origin main --rebase
//ou
git pull origin main --allow-unrelated-histories

git push -u origin main
