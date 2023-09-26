# команда git
## создание репозитория 
`git init`
>создает репозиторий в выбранной папке
>Логинимся 
`git` 
```
`cd "ссылка на папку/файл"`
```
`pwd`
```
>показывает путь к папке
```
`git init`
```
>инициируем гит в этой папке

`git status`
```
>статус папки

`ls -la`
```
>cписок содержимого папки

`git add .`
```
>добавить к отслеживанию все новые файлы из текущей папки и её подпапок, индексировать отслеживаемые файлы

`git commit -m "коментарий"`
```
>закоммитить отслеживаемые индексированные файлы 

`git log`
```
>показать последние комиты

`git config --list`
```
>проверка данных которые введины 

`git remote add origin "сайт"` 
```
>связывает сайт с нужной папкой

`git push -u origin main`
```
>добавляет всё изменения в папке на сайт. main может меняться на branch1 или что то ещё, если надо перекинуть с другой ветки, а не с main

`git remote -v`
```
>просмотр в какой вы находитесь ветке

`git remote rm origin`
```
>отлючение от репозитория, ветки

`git pull origin main`
```
>заносит изменение с сервера

`git clone`
```
> загружает репозиторий с сервера если его у тебя нет

`.gitignore` 
```
>сначала создаёшь файл, а после пишешь в файл gitignore

`git branch -d"branch1"`
```
>создание ветки

`checkout -b`
```
>создаёт и сразу переходит в новую ветку, выполняет эти две команды

`branch`
```
>создаёт новую ветку

`checkout`
```
>переход между ветками

`git checkout -b branch1`
```
>в первый раз пишется так и она создаёт новую временную ветку и сразу переходит туда

`git checkout branch1`
```
>во второй раз пишется без -b и просто переход

`git checkout main`
```
>чтобы вернуться обратно в ветку

`git branch`
```
>показывает сколько веток и выделит ту ветку, в которой вы находитесь

