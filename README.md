# Доклад по git для сотрудников DEVEX #

### Темы вступления ###

1. Логи  
 ```git -p --word-diff , --stat```

2. Откат назад 

* Отмена названия последнего коммита 
```git --amend ```

* Отмена индексации файла 
```git --reset HEAD filename```

* Отмена изменений файла
```git checkout file```

* Отмена последнего коммита путем созданием нового коммита
```git revert HEAD``` или ```git revert --soft HEAD^```

* Отмена последнего коммита путем удаления коммита
```git reset --hard HEAD^```

3. Локальные и удаленные ветки

* Просмотр локальных веток ```git brancn```
* Удаленных веток ```git bracn -a```
* Ветки которые незамерженные в которых остались изменения ```git branch --no-merged```
* Удаление веток локальных и удаленных 

    ```git branch -d my_branch``` (удаление пройдет если замержина)
    
    ```git branch -D my_branch``` (удаление пройдетв даже если ветка не замержина)
    
    ```git push origin --delete``` issue_#1

7. Merge (слияние) и rebase (перемещение - чето пока сам не въехал). Основная разница

8. Решение конфликов во время merge. Инструменты

9. Stash

10. Подмодули


### Используемые ресурсы ###

<https://git-scm.com>

