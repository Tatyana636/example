git branch tatyan
git checkout tatyan
git branch --set-upstream-to=origin/tatyan tatyan
git push --set-upstream origin tatyan


#новый код
git pull
git add file.txt
git commit -m "text"
git push


#внедрить новый код
git checkout main
git pull
git merge tatyan
git checkout tatyan



Факт дня:
Антон любит накатывать на сервер и на грудь
