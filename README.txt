1. Создать внешний репозиторий c названием TXT.
2. Клонировать репозиторий TXT на локальный компьютер.
    git clone https://github.com/atrf87/TXT.git
3. Внутри локального TXT создать файл “new.txt”.
    cd txt
    cat > new.txt
4. Добавить файл под гит.
    git add new.txt
5. Закоммитить файл.
    git commit -m "files TXT"
6. Отправить файл на внешний GitHub репозиторий.
    git push
7. Отредактировать содержание файла “new.txt” - написать информацию о себе. Всё написать в формате TXT.
    vi new.txt
8. Отправить изменения на внешний репозиторий.
    Git add .
    git commit -m "create file new.txt"
    git push
9. Создать файл preferences.txt
    cat > preferences.txt
10. В файл preferences.txt” добавить информацию о своих предпочтениях в формате TXT.
    vi preferences.txt
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
    cat > sklls.txt
    vi sklls.txt
12. Сделать коммит в одну строку.
    Git add .
    git commit -m "preferences and skills"
13. Отправить сразу 2 файла на внешний репозиторий.
    git push
14. На веб интерфейсе создать файл bug_report.txt.
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
18. Синхронизировать внешний и локальный репозиторий TXT
    git pull

