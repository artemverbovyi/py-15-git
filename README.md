Тут файл main.py імпортує функції з mymod.py і запускає їх

Команда git status не виявила папку **pycache**, оскільки ми додали її до чорного списку, це файл .gitignore

## AI log:

використовував Gemini для розбору команд git на простих прикладах, тобто що вони означають і нащо вони взагалі

## My history

dcbc478 (HEAD -> main, origin/main) Add README /
a2f957e Add my module and the script that uses it /
10cf10e Add .gitignore

## How to run

python main.py

## Pull request

https://github.com/artemverbovyi/py-15-git/pull/1

## Errors

**Помилка 1:**

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: main.py

no changes added to commit (use "git add" and/or "git commit -a")

**Пояснення:** Git повідомляє, що файл змінено, але його не додано; щоб це виправити, спочатку потрібно виконати команду `git add <ім’я файлу>`.

**Помилка 2:**

fatal: not a git repository (or any of the parent directories): .git

**Пояснення:** Git повідомляє, що поточна папка не є репозиторієм; щоб виправити це, потрібно перейти до потрібної папки за допомогою `cd` або створити новий репозиторій командою `git init`
