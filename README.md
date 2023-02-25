JSON 
Создать внешний репозиторий c названием JSON.

github.com->repositories->press "New"->giving name to repository "JSON" -> click on "Create repository"

Клонировать репозиторий JSON на локальный компьютер.GitHub
$ cd /d/QA_Training/git/GIT_HUB/JSON

Внутри локального JSON создать файл “new.json”.
$ touch new.json

Добавить файл под гит.
$ git add new.json-

Закоммитить файл.
$ git commit -m "Create new file.json"

Отправить файл на внешний GitHub репозиторий.
$ git push

Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
$ vim new.json
i (insert) Enter

 {  
  "Last name": "Fil",  
  "First name": "Igor",  
  "Middle name": "Vasilievich",  
  "Pets": "One",  
  "Future salary": "120000"  
 }  
Отправить изменения на внешний репозиторий.
$ git add new.json
$ git status
$ git commit -m "Edit new.json"
$ git push

Создать файл preferences.json
$ touch preferences.json

В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
$ vim preferences.json insert

{  
 "Favorite_movie": "Terminator",  
 "Serial": "MosGaz",  
 "Favorite_food": "Duck",  
 "Favorite_time_of_the_year": "Summer",  
 "Country_which_you_like_to_visit": "Uruguay",  
}  
Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
$touch skills.json
Insert

 {  
  "Base_theory": "1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.",  
  "Client-Server": "2. Что такое клиент-серверная архитектура.",  
  "HTTP_methods": "3. HTTP Методы запросов на сервер.",  
  "Codes":"4. Коды ответов HTTP сервера.",  
  "Structures": "5. Структуры HTTP запросов и ответов.",  
  "JSON" : "6. Что такое JSON, XML. Их структура.",  
  "Other_skills" : "и другие навыки"  
  }  
Отправить сразу 2 файла на внешний репозиторий.
$ git add preferences.json skills.json
$ git status (Проверяем проиндексированы ли нужные нам файлы)
$ git commit -m "2 new files, preferences.json and skillls.json"
$ git push

На веб интерфейсе создать файл bug_report.json.
В мастер ветке нажимаем Add file->Create new file , даём имя и расшиерение файлу bug_report.json

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Скроллим вниз нажимаем Commit changes

На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
Кликаем на файл bug_report.json, затем на карандаш и добавляем изменения в файл

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Скроллим вниз нажимаем Commit changes

Синхронизировать внешний и локальный репозиторий JSON
$ git pull

