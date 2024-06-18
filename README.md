# instruction

## Git и GitHub

* Git — система контроля версий. Технология, которую можно скачать на компьютер.
* Github — сервис, который позволяет работать с Git проектами. Это
называется репозитории. Помимо Github существуют другие сервисы (например
Bitbucket, GitLab).

## Как установить Git

* Скачать можно по ссылке https://git-scm.com/downloads.
* Запускается через командную строку или терминал с команды git. Все команды git выполняются в терминале, или командной строке. в VS Code вызывается командой "Ctrl + ~"

## Подготовка

1. Регистрация на GitHub - сервисе для хранения репозиториев.
2. Установить git с официального сайта.
3. Настройка git. Задать имя и email командами: 
*git config ­­global user.name "Maria"*
*git config ­­global user.email belbera@mail.ru*

## Основные команды

*git init* позволяет проинициализировать репозиторий в текущей папке
*git status* показывает текущий статус
*git add* отслеживает изменения файлов
*git add file_name.md* добавляет file_name.md
*git add .* добавляет все файлы

*git commit* cохраняет изменения в коммит
*git commit -m "commit message"* создает коммит с сообщением

## Работа с ветками в репозитории

*git branch* показывает список веток
*git branch branch_name* создает новую ветку branch_name
*git branch -D branch-name* удаляет ветку branch_name

*git checkout* переключает на другую ветку
*git checkout branch_name* переключает на последний коммит в ветке branch_name
*git checkout -b branch_name* создает и переключает на ветку branch_name

*git merge* совмещает текущую ветку с выбранной
*git merge branch_name* совмещает текущую ветку с branch_name

*git config* - конфигурация и параметры git
*git config --global user.name* показывает имя пользователя
*git config --global user.name "new user"* изменяет имя пользователя
*git config --global user.email* показывает email пользователя
*git config --global user.email "noname@mail.ru"* изменяет email пользователя

## Создание репозитория на GitHub

1. Dойти в систему
2. В правом верхнем углу выбрать "+" и "New repository".
3. Заполнить поля:
* Repository name: test 
* Description: Test repository 
* Пункт "Public" делает репозиторий публичным, "Private" делает репозиторий приватным
* Можно добавить файл README, в котором можно записать описание проекта (если нужно).
* Нажать "Создать репозиторий"

## Команды для удаленного репозитория
*git push* заливает текущие локальные коммиты в удаленный репозиторий
*git pull* забирает изменения с удаленного репозитория в локальный
*git clone* клонирует проект с удаленного репозитория