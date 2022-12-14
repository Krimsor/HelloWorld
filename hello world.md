Hello world!
=

# Шрифт

`Зачеркнутый цветом`

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*) или щнаком нижнего подчеркивания (_). Например *Курсив* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания(__). Например **Полужирный** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например: _текст может быть выделен курсивом и при этом быть **полужирным**_.

# Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+). Например, вот так:

* Элемент 1

* Элемент 2

* Элемент 3

+ Элемент 4

+ Элемент 5

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать, вот так :

1. Первый 
2. Второй

# Команды и настройки Git

* **Всегда проверять путь к репозиторию**

# Команды git

* "git init" - создание репозитория в нашем проекте.
* "git status" - нужен для сохранения состояния.
* "git diff" - показывает различия в файлах.
* "git branch" - показывает название ветки, в которой работаешь.
* "git ignore (название файла)" - игнорировать данный файл
* "git -- version" - проверить версию гита
* "git checkout (первые 4 символа из git log) - вернуться в нужное изменение в файле.
* "git checkout master" - вернуться в главную(актуальную) ветку.
* "cd (название папки) либо подобрать (TAB) - перейти в нужную папку.
* "cd .." - вернуться из папки выше.
* "git commit" - нужен для сохранения состояния
* "git commit -a -m (названия коммита) - закоммитить все предыдущие файлы.
* "git branch (название новой ветке) - создать новую ветку.
* "git branch -d (название ветки)" - удалить выбранную ветку.
* "git checkout -b (название новой ветки)" - сразу создать и перейти в новую ветку.
* "git merge (название ветки)" - слить выбранную ветку в ту ветку, в которой сейчас находишься.
* "git log --graph" - увидеть ветки и команды. 
* "git clone (скопированный адрес репозитория)" - клонировать нужный репозиторий (чужой).
* "git branch -M (название новой основной ветки)" - создание нового имени основной ветки.
* "git push origin(соединение) (название нужной ветки)" - обновить удаленные ссылки вместе со связанными объектами.
* "git pull" - получение и интеграция с другим репозиторием или локальной веткой.

# Команды настройки Git

* "git config --global user.name (свое имя).
* "git config --global user.email (свою почту).
* "git config --global core.editor (путь к папке с нужным редактором(VS Code) или название редактора(Vim и тд)).
* "git config --global init.defaultBranch master(либо свое название) - назначить имя для своей главной (актуальной) ветке.

# Работа с изображениями (картинками .jpg и т.д.)

ЧТобы вставить изображение в текст, достаточно написать следующее: 
![Привет, итс ми Александр!](Shpak.jpg)

# GitHub - создание нового репозитория

* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https:// ссылка с аккаунта
* git push -u origin main