Hello
Привет, GitHub и мир
Avetik

# Инструкция и команды для применения Git

- git init – инициализация локального репозитория

- git status – получить информацию от git о его текущем состоянии

- git add – добавить файл или файлы к следующему коммиту

- git commit -m “message” – создание коммита.

- git log – вывод на экран истории всех коммитов с их хеш-кодами

- git log --graph – журнал коммитов с визуализацией

- git commit -a -m “текст_коммита” – создание изменения и его коммит

Чтобы просмотреть список веток, используем команду:

- git branch

Чтобы создать новую ветку, используем команду:

- git branch <название ветки>

Чтобы удалить ветку, используем команду:

- git branch -d <название ветки>

Чтобы перейти в другую ветку, используем команду:

- git checkout <название ветки>

Также можно создать ветку и одновременно перейти в нее, для этого используем команду:

- git checkout -b branch_name
- git clone <url-адрес репозитория> – клонирование внешнего репозитория на локальный ПК

- git pull – получение изменений и слияние с локальной версией

- git push – отправляет локальную версию репозитория на внешний
