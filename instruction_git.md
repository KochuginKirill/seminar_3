# Git instruction
![picture](picture_git.jpeg)
*System of version control git if for...*

## Creation of local repository

чтобы создать (инициализировать) новый локальный репозиторий нужно в терминале ввсести команду

    git init



- git init (создает репозиторий)
- git status (текущий статус репозитория)
- git add \<file_name> (добавляет или обновляет файл в репозитории)
- git add . (добовляет, обновляет все файлы и изменения репозитория)
- git commit (сохраняет версию с определенным комментарием пользователя)
- git commit -m "message" (сохранение комита с строчным коментарием)
- git commit -am "message" (сохранение с сообзение в одну команду, лучше не злоупотреблять, а то может быть много пустых комитов)
- git log (Журнал версий)
- git log --oneline (тот же git log, но покороче и без чаще всего лишней информации)
- git log --all (полный список всех версий)
- git log --oneline --all (полный список всех версий в сжатом виде)
- git checkout \<hash> (вернуться к версии по ее хэшу)
- git checkout master (возврат к последней актуальной версии)
- git diff (показывает закомиченые изменения)
- git diff \<hash1> \<hash2> (показывает разницу между двумя комитами, можно даже сказать вектор изменений от первого ко второму)


    git branch
(показывает  ветки)

    git branch \<name>

создает ветку

    git merge <branch_name>

помещает изменения в той ветке что указана в команде в текущую ветку 

pls let there be a conflict 

if you create file .gitignore and put file name inside, then this file will not be tracked by git.

result: five branches created and merged with one succsessfull conflict.
first branch deleted

## Удаленные репозитории



