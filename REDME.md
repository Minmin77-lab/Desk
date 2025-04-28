mkdir (les)
cd (ls)
git init
git status
git remote add origin (ссылка на гитхаб)
git remote -v
touch REDME.md //создать
explorer . // открыть проводник с REDME и написать там что-нибудь
git add .
git commit -m "(...)"

//если ошибка
git config --global user.name "(name)"
git config --global user.email "(email)"
git commit -m "(...)"

git status
git push

//при ошибке запушить
git push -u origin master

//history - история запросов



///Страпи

git clone (ссылка на гитхаб)
cd (desk)
npx  create-strapi-app test(name) --quickstart
