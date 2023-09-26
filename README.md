# Команды GIT
## Создание репозитория
```
git init
```
> создает репозиторий в выбранной папке
```
git add .
```
> добавляет файлы в репозиторий
```
git status
```
> показывает статус репозитория
```
git commit -m "commit"
```
> сохраняет изменения
```
ls -la
```
> покажет все файлы в текущей директории
```
pwd
```
> покажет в какой папке мы находимся
```
git log
```
> показывает истрию комитов
## Создание удaленного репозитория
```
git remote add origin ссылка на репозиторий в GitHub
```
> добавляет по URL удаленный репозиторий
```
git branch -M main
```
> создает основную ветку
```
git push -u origin main
```
> переносит локальный репозиторий
```
git remote -v
```
> показывает какой репозиторий подключен
## Ветвление
```
git checkout -b имя ветки
```
> переходит на указанную ветку
```
git merge имя ветки
```
> создает слияние между указанной и используемой веткой
## Авторизация в GitBash
```
git config --global user.name "имя_пользователя"
```
> ввод имени пользователя
```
git config --global user.email "свой_email"
```
> ввод электронной почты

