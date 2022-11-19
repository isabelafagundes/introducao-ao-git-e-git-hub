GIT PUSH - SCRIPT PARA SUBIR ARQUIVOS PARA O GIT HUB !!!

git init
git remote add origin https://github.com/isabelahidalgo/Projetos-Botcamp-JAVA-DIO.git
git commit -m "primeiro commit"
git add .
git commit -m "primeiro commit"
git branch -m master main
git pull origin main --allow-unrelated-histories (ou git pull origin main)
git push -u origin main