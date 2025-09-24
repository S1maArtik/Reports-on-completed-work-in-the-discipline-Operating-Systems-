Словник термінів (українською):

* Git – розподілена система контролю версій, що використовується для відстеження змін у файлах.  
* Репозиторій (repo) – сховище проєкту та його історії.  
* Комміт (commit) – збережений знімок змін у проєкті з метаданими (автор, час, повідомлення).  
* Гілка (branch) – незалежна лінія розробки.  
* Злиття (merge) – об’єднання змін з різних гілок.  
* Область підготовки (staging area) – місце, де файли готуються перед комітом.  
* Клонування (clone) – створення копії репозиторію.  
* Push – відправка локальних змін у віддалений репозиторій.  
* Pull – отримання оновлень із віддаленого репозиторію.  
* Checkout / Switch – перехід між гілками або версіями.  
  Glossary of Terms (in English):  
* Git – a distributed version control system used for tracking changes in files.  
* Repository (repo) – a storage space for the project and its history.  
* Commit – a saved snapshot of changes in the project with metadata (author, time, message).  
* Branch – an independent line of development.  
* Merge – combining changes from different branches.  
* Staging area – the space where files are prepared before committing.  
* Clone – a copy of a repository.  
* Push – sending local changes to a remote repository.  
* Pull – receiving updates from a remote repository.  
* Checkout / Switch – moving between branches or versions.

1\. Для чого використовують Git, основні дії та команди?

Відповідь: Git – це система контролю версій, яка використовується для відстеження змін у коді та спільної роботи над проєктами. Вона дозволяє:

* зберігати історію змін у файлах,  
* повертатися до попередніх версій,  
* працювати в команді без конфліктів,  
  об’єднувати зміни з різних гілок розробки.

Основні дії та команди Git:

* git init – створити новий репозиторій.  
* git clone \<url\> – скопіювати (клонувати) існуючий репозиторій.  
* git status – переглянути поточний стан файлів (змінені, не відстежувані, готові до коміту).  
* git add \<file\> – додати файл(и) у staging area (підготувати до коміту).  
* git commit \-m "message" – створити комміт із повідомленням.  
* git log – перегляд історії коммітів.  
* git branch – робота з гілками (перегляд, створення, видалення).  
* git checkout \<branch\> або git switch \<branch\> – переключення між гілками.  
* git merge \<branch\> – об’єднання гілок.  
* git push – відправка змін у віддалений репозиторій.  
  git pull – отримання змін із віддаленого репозиторію.

2\. Що таке "комміт" і як він відслідковує зміни

Відповідь: Комміт (commit) – це збереження змін у репозиторії.  
 Кожен комміт містить:

* знімок файлів у певний момент часу,  
* унікальний ідентифікатор (hash),  
* автора змін,  
* дату й час,  
* повідомлення з описом змін.

Таким чином, комміти дозволяють відстежувати історію проєкту: які зміни робилися, ким і коли. Це забезпечує можливість відкотитися до попередньої версії, зрозуміти логіку розвитку коду, та працювати над різними версіями паралельно.

Висновки: Git – зручний інструмент для роботи з кодом. Він дозволяє зберігати історію змін і працювати в команді. Комміти допомагають бачити, хто і що змінив, та легко повертатися до попередніх версій.

Conclusions: Git is a useful tool for coding projects. It keeps the history of changes and makes teamwork easier. Commits show who changed what and allow returning to earlier versions if needed.  


Висновки: я молодець.
