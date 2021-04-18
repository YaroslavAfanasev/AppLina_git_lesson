# AppLina_git_lesson

Описание практического задания по Git

1. Клонировать на свой локальный компьютер пустой репозиторий;

2. Добавить в свой локальный репозиторий (прямо в master) файл Potter.txt, содержащий список книг (именно в том виде, как оно приведено ниже):

Harry Potter book
One The Philosopher's Stone (1997)
two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
4etyre The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого добавить (push) файл Potter.txt в свой удалённый репозиторий на GitHub.

3. Создать ветку feature, изменить в ней содержание файла Potter.txt на новое:

Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
chetyre The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения в ветку feature.

4. Перейти в master, изменить в ней содержание файла Potter.txt на ещё один вариант:

Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения в ветку master и сделать push в удалённый репозиторий.

5. Снова перейти в ветку feature и вмерджить в неё master.

6. Разрешить мердж-конфликт таким образом, чтобы в результате в ветке feature появился правильный вариант Potter.txt:

Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения ветки feature.

7. После проделанного 6-ого шага изменить файл в ветке feature добавив в него «:» в конце самой 1-ой строки:

Harry Potter book:
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения ветки feature.

8. Перейти в master, изменить в ней содержание файла Potter.txt на ещё один вариант:

Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
4 The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения ветки master.

9. Вмерджить feature в master и обновить Potter.txt, разрешить конфликт в ветке master таким образом, чтобы в результате получился правильный вариант текста:

Harry Potter book:
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

Залить(push) изменения ветки master в удалённый репозиторий