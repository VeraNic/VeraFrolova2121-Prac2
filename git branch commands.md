# GIT BRANCH COMMANDS

[GIT BRANCH](https://www.atlassian.com/ru/git/tutorials/using-branches)

1. **git branch *branch_name*** - создание новой ветки

2. **git branch** - вывод списка веток

3. **git branch -d *branch_name*** - удаление ветки

4. **git branch -D *branch_name*** - принудительное удаление указанной ветки, даже если в ней есть неслитые изменения: навсегда удаляются все коммиты, связанные с определенным направлением разработки

[GIT CHECKOUT](https://www.atlassian.com/ru/git/tutorials/using-branches/git-checkout)

5. **git checkout -b *branch_name*** - создание ветки, переход в неё

6. **git checkout *branch_name*** - просмотр ветки

[GIT MERGE](https://www.atlassian.com/ru/git/tutorials/using-branches/git-merge)

7. **git merge *branch_name*** - слияние просматриваемой ветки с указанной

8. **git merge --abort** - прерывание слияния, возврат ветки к состоянию, в котором она находилась до начала слияния

9. **git log --merge** - создание журнала со списком конфликтов коммитов между ветками, для которых выполняется слияние

[Конфликты слияния](https://www.atlassian.com/ru/git/tutorials/using-branches/merge-conflicts)

![image](https://miro.medium.com/max/1148/1*Sg8xy936xO0nUdnDZkW3zw.png)
