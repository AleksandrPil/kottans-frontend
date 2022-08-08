# kottans-frontend
## General
---
## 0. Git Basics
### Git та GiHub
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
* раніше вважав, що GitHub Desktop - це і є Git, але ні :), для мене Git зовсім нове.
* здивувало, що за допомогою декілька команд у Git, можна багато чтго зробити.
* Git commands:
   - git init - _створити новий репозиторій_
   - git clone <path-to-repository-to-clone> - _клонувати репозиторій_
   - git status - _визначити статус репозиторію_
   - git log - _відобразити коміти сховища_
   - git log --one line - _однією лінією_
   - git log --stat - _перегляд змінених файлів_
   - git log -p - _перегляд змін у файлі_
   - git log -p - --stat _скільки файлів було змінено і кількість змінених рядків_
   - git log -p -w - _ігнорувати пробіли_ 
   - git add <file1> <file2> ... <fileN> - _переміщення файлів із робочого каталогу до проміжного індексу_
   - gid add . - _додати все_
   - git show -  _показати комміт_
   - git commit -m "My commit" - _додати комміт до репо_
   - git fetch - _витягує дані з віддаленого репозиторію_
   - git pull - _витягує дані з віддаленого репозиторію та робить мердж (merge)_
   - git push - _використовується для надсилання локальних змін на вказаний віддалений репозиторій_
   - git rebase - _бере кілька комітів, "копіює" їх, й кладе їх в інше місце_
   - git cherry-pick <Коміт1> <Коміт2> <...> - _копіює серію комітів до поточного розташування (HEAD)_
   - git diff - _перегляд внесених але ще не зафіксованих змін_
   - git tag -a <tagName> -m "my version 1.4" - _додати таг до комміту_
   - git tag -d <tagName> - _видалити таг_
   - git branch - _список гілок у сховищі_
   - git branch <branchName> <SHA> - _створити гілку_
   - git branch -d <branchName> - _видалити гілку_
   - git checkout <branchName> - _перейти на гілку_
   - git log --oneline --decorate - _відображення гілок_
   - git checkout -b footer master - _створити нову гілку та переключитися на неї_
   - git log --oneline --decorate --graph --all - _переглянути всі гілки одразу_
   - git reset --hard HEAD^ - _скасувати злиття_
   - git merge <name-of-branch-to-merge-in> - _злиття гілок_
   - git commit --amend - _зміна останнього комітту_
   - git revert <SHA-of-commit-to-revert> - _повернення комміту_
   - git reflog - _отримати доступ до стертого вмісту_
   - git reset <reference-to-commit> - _скидання (стертя) комміту_
   - git reset --mixed - _візьме зміни, внесені в комміт і перемістить їх до робочого каталогу_
   - git reset --soft - _візьме зміни, внесені в комміт і перемістить їх до індекcу проміжку_
   - git reset --hard - _візьме зміни, внесені в комміт і зітре їх_
  .gitignore
  fileName
  
  ## 1. Linux CLI, and HTTP
  ### Linux, Command Line, HTTP Tools
  1. [ ] Linux Survival (4 modules)
  2. [ ] HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 1
  3. [ ] HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 2
  
  ---
  ## 2. VCS (hello gitty), GitHub and Collaboration
  ### Git для командної співпраці
  1. [ ] Introduction to Git and GitHub (тижні 3 і 4 курсу)
  2. [ ] Learngitbranching
  
