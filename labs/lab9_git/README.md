# Оценка 3

![!\[alt text\](01_git_status.png)](../Screenshots/01_git_status.png)

1. Первая строка On branch main показывает текущую ветку.

![!\[alt text\](02_git_log.png)](../Screenshots/02_git_log.png)

2. Видна история коммитов: хэш, автор, дата, сообщение. Если коммитов нет, git пишет, что их нет.

![!\[alt text\](03_sort.png)](../Screenshots/03_sort.png)

3. Создал файл с функцией сортировки

![!\[alt text\](04_git_status.png)](../Screenshots/04_git_status.png)

4. Файл в разделе Untracked files: git его видит, но не отслеживает.

![!\[alt text\](05_add.png) ](../Screenshots/05_add.png)

5. Файл помещён в индекс (stage), то есть подготовлен к коммиту.

![!\[alt text\](06_git_status.png)](../Screenshots/06_git_status.png)

6. Файл в Changes to be committed.

![!\[alt text\](07_commit.png)](../Screenshots/07_commit.png)

7. "Закомитил/закоммитил" файл.

![!\[alt text\](08_git_status.png)](../Screenshots/08_git_status.png)

8. Cтатус.

![ !\[alt text\](09_comm.png)](../Screenshots/09_comm.png)

9. Добавил комментарий в файл.

![!\[alt text\](10_git_status.png)](../Screenshots/10_git_status.png)

10. Файл в Changes not staged for commit как modified.

![!\[alt text\](11_add.png)](../Screenshots/11_add.png)

11. Файл лежит в stage.

![!\[alt text\](12_git_status.png)](../Screenshots/12_git_status.png)

12. Файл в Changes to be committed как modified.

![!\[alt text\](13_comm.png)](../Screenshots/13_comm.png)

13. Добавил ещё один комментарий. 

![!\[alt text\](14_commit.png)](../Screenshots/14_commit.png)

14. Закоммитил файл.

![!\[alt text\](15_git_status.png)](../Screenshots/15_git_status.png)
![!\[alt text\](15_git_log.png)](../Screenshots/15_git_log.png)

15. Статус: modified. В логе 2 коммита про sort.c

![!\[alt text\](16_add_commit.png)](../Screenshots/16_add_commit.png)

16. Добавил в stage и закоммитил.

![!\[alt text\](17_git_push.png)](../Screenshots/17_git_push.png)

17. Всё отправлено успешно!

# Ветки

![alt text](../Screenshots/18_mybranch.png)
![alt text](../Screenshots/18_git_branch.png)

1-2. Создана ветка mybranch. Видны две ветки: main и mybranch. Звёздочка * стоит у main, так как переключения ещё не было.

![alt text](../Screenshots/19_switch_status.png)

3-4. Переключились на новую ветку. Меняется только первая строка: On branch mybranch.

![alt text](../Screenshots/20_git_branch.png)

5. Убедились по *, что находимся на mybranch.

![alt text](../Screenshots/21_file1.png)

6. Создан файл file1.txt с именем. Git пока считает его untracked.

![alt text](../Screenshots/22_add_commit.png)

7. Файл проиндексирован и закоммичен в ветку mybranch.

![alt text](../Screenshots/23_git_log.png)

8. Верхний коммит помечен HEAD -> mybranch.

![alt text](../Screenshots/24_switch_log.png)

9-10. Вернулись на главную ветку. Файл file1.txt из папки исчез: он есть только в коммите mybranch. 

![alt text](../Screenshots/25_add_commit.png)

10-11. В main появился свой новый коммит, независимый от mybranch.

![!\[alt text\](../Screenshots/26_git_log.png)](../Screenshots/26_git_log.png)

12. У main и mybranch теперь разные последние коммиты.

![!\[alt text\](../Screenshots/27_switch.png)](../Screenshots/27_switch.png)

13. Вернулись на ветку mybranch.
14. file2.txt пропал: он закоммичен только в main. При переключении git подставляет содержимое выбранной ветки.

![!\[alt text\](../Screenshots/28_git_diff.png)](../Screenshots/28_git_diff.png)

15. Строки с - есть в mybranch, строки с + есть в main. Видно, что file1.txt есть только в mybranch, а file2.txt только в main.

![!\[alt text\](../Screenshots/29_screenshot.png)](../Screenshots/29_screenshot.png)
![!\[alt text\](../Screenshots/30_add_commit_push.png)](../Screenshots/30_add_commit_push.png)

16. Добавил, закоммитил и отправил под новой веткой.

![!\[alt text\](../Screenshots/31_push.png)](../Screenshots/31_push.png)

17. Вернулся в main и запушил.

![!\[alt text\](../Screenshots/32_branch.png)](../Screenshots/32_branch.png)

Всё на месте! 