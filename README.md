\# Лабораторная работа №1



\*\*Коровников Георгий Александрович\*\*

Группа: \*\*221141\*\*

Вариант: \*\*5\*\*



\## Выполненные задания



\### Средняя сложность



1\. \*\*Настройка Git\*\*

&#x20;  - Git установлен и настроен.

&#x20;  - Указаны имя пользователя и email.



2\. \*\*Создание ветки feature\*\*

&#x20;  - Создана ветка `feature`.

&#x20;  - В ветке добавлен новый файл `text\_utils.py`.

&#x20;  - Ветка слита с `main` через `git merge --no-ff`.



3\. \*\*Файл .gitignore\*\*

&#x20;  - Добавлен `.gitignore` для Python-проекта.



\### Повышенная сложность



1\. \*\*GitHub Actions\*\*

&#x20;  - Настроен workflow `.github/workflows/python-check.yml`.

&#x20;  - Проверка Python-кода выполняется с помощью `flake8`.



2\. \*\*Git submodule\*\*

&#x20;  - Добавлен submodule через `git submodule add`.

&#x20;  - Используется репозиторий `octocat/Hello-World`.

&#x20;  - Submodule расположен в `libs/hello-world`.



\## Структура проекта



mtp-lab1/

├── .github/

│   └── workflows/

│       └── python-check.yml

├── libs/

│   └── hello-world

├── .gitignore

├── .gitmodules

├── README.md

├── main.py

└── text\_utils.py



\## Основные команды Git



git status

git add

git commit

git switch

git merge

git push

git submodule add

