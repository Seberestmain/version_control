# Инструкция по работе с Git

## Создание репозитория

 Для создания репозитория необходимо в папке с репозиторием выполнить команду *git init*. 
 
## Создание коммитов

### git add
Для добавления изменений в коммит используется команда *git add*. Например: *git add <имя файла>*
### Просмотр состояния репозитория 
Для того, чтобы посмотреть состояние репозитория используется команда *git status*.
### Создания коммитов
Для того, чтобы создать коммит необходимо выполнить команду *git commit*. Пример: *git commit -m <Текст>* 
## Работа с ветками и логами
### Просмотр веток
Для того, чтобы посмотреть ветки необходимо выполнить команду *git branch*
### Создание новых веток 
Для того, чтобы создавать новые ветки необходимо выполнить команду *git branch <Название ветки>*
### Переключение на другую ветку
Для того, чтобы переключится на новую ветку необходимо выполнить команду *git checkout <Название ветки>*
### Просмотр логов
Для просмотра логов нужно выполнить команду *git log*. Также есть вариант упрощённого вывода логов для этого нужно ввести *git log --oneline*
### Объединение веток 
Для того, чтобы выполнить слияние веток нужно ввести команду *git merge <Название ветки>*
### Просмотр логов графом
Для того, чтобы посмотреть логи графом необходимо ввести команду *git log --oneline --graph*
## Работа с Github
### Клонирование репозитория
Для того, чтобы создать репозиторий на локалке на основе удалённого репозитория нужно выполнить команду *git clone <Ссылка на репозиторий>"
### Информация о репозитории
Для того, чтобы получить информацию о репозитории нужно ввести команду *git remote show origin*

Также можно использовать *git remote show origin -v* для большей информации
### Запрос информации с удалённого сервера
Для запроса нужно выполнить команду *git pull*
### Выталкивание информации на сервер
Для выталкивание нужно выполнить команду *git push*