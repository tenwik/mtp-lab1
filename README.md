# Лабораторная работа №1

**Коровников Георгий Александрович**  
Группа: **221141**  
Вариант: **5**

## Выполненные задания

### Средняя сложность

1. **Настройка Git**
   - Git установлен и настроен.
   - Указаны имя пользователя и email.

2. **Создание ветки feature**
   - Создана ветка `feature`.
   - В ветке добавлен новый файл `text_utils.py`.
   - Ветка слита с `main` через `git merge --no-ff`.

3. **Файл .gitignore**
   - Добавлен `.gitignore` для Python-проекта.

### Повышенная сложность

1. **GitHub Actions**
   - Настроен workflow `.github/workflows/python-check.yml`.
   - Проверка Python-кода выполняется с помощью `flake8`.

2. **Git submodule**
   - Добавлен submodule через `git submodule add`.
   - Используется репозиторий `octocat/Hello-World`.
   - Submodule расположен в `libs/hello-world`.

## Структура проекта

```text
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
└── text_utils.py
```

## Основные команды Git

```bash
git status
git add
git commit
git switch
git merge
git push
git submodule add
```