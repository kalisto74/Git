# Git
список команд и понятий по каждой из пройденных тем; инструкции по инициализации проекта, работе с коммитами и регистрации на GitHub или просто поурочные конспекты в свободной форме.
git init

# глобально 
git config --global user.name 'вашеимя'
git config --global user.email 'вашапочта'

# в локальном проекте
git config --local user.name 'вашеимя'
git config --local user.email 'вашапочта'

git status

git add -A
git add --all
git add . # добавить всю текущую папку

git commit -a -m'что изменено'


git log #посмотреть коммиты

git remote add origin git@github.com:вашникнеймнагихабе/репозиторий
git branch -M main
git push -u origin main

ls -la .ssh/ # вывели список созданных ключей 
ssh-keygen -t ed25519 -C "постагитхаба" 

git push -u origin main
