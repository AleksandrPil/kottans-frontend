# kottans-frontend
## General
## 0. [Git Basics](tasks/git-intro.md)
---
## Git та GiHub
1. [x] Version Control with Git (Udacity)
<details>
  <summary>Srcreenshots</summary>
  <img src = "./images/Udacity%20Git%20Course%201.jpg">
  <img src = "./images/Udacity%20Git%20Course.jpg">
  <img src = "./images/learngitbranching%201.jpg">
  <img src = "./images/learngitbranching%202.jpg">
</details>

2. [x] Learngitbranching
<details>
  <summary>Srcreenshots</summary>
  <img src = "./images/learngitbranching%201.jpg">
  <img src = "./images/learngitbranching%202.jpg">
</details>

---

раніше вважав, що GitHub Desktop - це і є Git, але ні :), для мене Git зовсім нове.
здивувало, що за допомогою декілька команд у Git, можна багато чтго зробити.
Some Git commands are:

 git init * *створити новий репозиторій* *
 * git clone <path-to-repository-to-clone> * *клонувати репозиторій* *
 * git status * *визначити статус репозиторію* *
 * git log * *відобразити коміти сховища* *
 * git log --one line * *однією лінією* *
 * git log --stat * *перегляд змінених файлів* *
 * git log -p * *перегляд змін у файлі* *
 * git log -p --stat * *скільки файлів було змінено і кількість змінених рядків* *
 * git log -p -w * *ігнорувати пробіли* * 
 * git add <file1> <file2> ... <fileN> * *переміщення файлів із робочого каталогу до проміжного індексу* *
 * gid add . * *додати все* *
 * git show  * *показати комміт* *
 * git commit -m "My commit" * *додати комміт до репо* *
 * git diff * *перегляд внесених але ще не зафіксованих змін* *
 * git tag -a <tagName> -m "my version 1.4" * *додати таг до комміту* *
 * git tag -d <tagName> * *видалити таг* *
 * git branch * *список гілок у сховищі* *
 * git branch <branchName> <SHA> * *створити гілку* *
 * git branch -d <branchName> * *видалити гілку* *
 * git checkout <branchName> * *перейти на гілку* *
 * git log --oneline --decorate * *відображення гілок* *
 * git checkout -b footer master * *створити нову гілку та переключитися на неї* *
 * git log --oneline --decorate --graph --all * *переглянути всі гілки одразу* *
 * git reset --hard HEAD^ * *скасувати злиття* *
 * git merge <name-of-branch-to-merge-in> * *злиття гілок* *
 * git commit --amend * *зміна останнього комітту* *
 * git revert <SHA-of-commit-to-revert> * *повернення комміту* *
 * git reflog * *отримати доступ до стертого вмісту* *
 * git reset <reference-to-commit> * *скидання (стертя) комміту* *
 * git reset --mixed * *візьме зміни, внесені в комміт і перемістить їх до робочого каталогу* *
 * git reset --soft * *візьме зміни, внесені в комміт і перемістить їх до індекcу проміжку* *
 * git reset --hard * *візьме зміни, внесені в комміт і зітре їх* *
  .gitignore
  fileName
  
  [Linux CLI and Networking](tasks/linux-cli-http.md)
