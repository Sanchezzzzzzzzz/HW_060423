# Руководство пользователя Git

## 1. Локальный репозиторий
* git init - инициализирует локальный репозиторий
* git status - проверка состояния файлов
* git add <*имя файла*> - добавление файла для индексации (*все проиндексированные файлы будут выводиться в терминале под заголовком Changes to be commited*)
* git commit - фиксация изменений (*с параметром -m*) 
* git commit -am - позволяет добавиьт commit без предварительного использования git add
## История изменений
* git log - просмотр истории версий (*если ввести параметр --oneline, то выведет короткий log*)
* git log --graph - просмотр истории версий с графическим представлением веток
* git reflog - просмотр истории операций
* git reset <# хэша> - удаляет комиты до указанного хэша
## Работа с ветками
* git branch name - создает ветку name
* git branch - выводит список веток
* git branch -d  <имя ветки> - удаление ветки

## 2. Удаленный репозиторий
* git clone <*url*> - клонирование существующего репозитория (*например, из github.com в локальный*)
* git push - загружает данные в удаленный репозиторий
* git pull - перенос данных из удаленного репозитория на локальный репозиторий
* git fetch - подгружает обновления из репозитория
* git tag <имя тэга> - добавляет тэг (номер версии)