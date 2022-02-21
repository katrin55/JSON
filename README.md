## JSON

 4. Создать внешний репозиторий c названием JSON.
  - на сайте github.com необходимо нажать `New`
  - в поле `Repository name` ввести `JSON`
  - выбрать следующие параметры: `Public` и  `Add a README file`
  - нажать `Create repository`
  
 5. Клонировать репозиторий JSON на локальный компьютер.
 - во вкладке `Code` необходимо скопировать HTTPS ссылку `https://github.com/katrin55/JSON.git`
 - запустить GitBash, с помощью `pwd` проверить, что находимся в необходимой директории
 - ввести команду `git clone https://github.com/katrin55/JSON.git`

 6. Внутри локального JSON создать файл “new.json”
 - зайти в папку созданного репозитория `cd JSON`
 - ввести `vim new.json`
 - добавить: 
```
{ 
 "name" : "Uglovskaia Ekaterina Evgenevna", 
 "age" : 25, 
 "pets" : 0,  
 "future_salary": 50000
}
```
- для сохранения нажать esc :wq

 7. Добавить файл под гит. \
 `git add new.json`

 8. Закоммитить файл. \
 `git commit -m "add 1 file json"`

 9. Отправить файл на внешний GitHub репозиторий. \
`git push`

 10. Создать файл preferences.json.
 11. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

- ввести `vim preferences.json`
 - добавить: 
```
{
 "favorite_movie" : "1+1",
 "favorite_series": "la_casa_de_papel",
 "favorite_food": "pasta",
 "favorite_time_of_the_year": "summer",
 "country_i_would_like_to_visit": "Switzerland"
}
```
- для сохранения нажать esc :wq

 12. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

- ввести `vim skills.json`
 - добавить: 
```
{
 "skills": [
	 "The theory of software testing",
	 "Client server arhitecture",
	 "Structures of HTTP requests and responses",
	 "Structure of JSON, XML formats",
	 "API testing with Postman (JS, API autotests)",
	 "Removing and reading logs from an external server",
	 "Sniffing http web traffic with Charles and Fiddler",
	 "Dev Tools of web browsers Google Chrome and FireFox",
	 "VPN",
	 "Mobile testing",
	 "Building Android Applications with Android Studio",
	 "ADB",
	 "Setting up proxy and vpn on iOS and Android",
	 "Intercepting mobile traffic with Charles and Fiddler",
	 "Linux terminal",
	 "Access to remote servers",
	 "SQL Basics. Create, Delete, Drop, Insert Into, Select, From, Where, Join",
	 "Postgres database",
	 "Redis non-relational database",
	 "Load Testing with Jmeter",
	 "Scrum Methodology"
 	]
}
```
- для сохранения нажать esc :wq

 13. Отправить сразу 2 файла на внешний репозиторий. 
- `git add . `
- `git commit -m "add 2 files json"`
- `git push`

 14. На веб интерфейсе создать файл bug_report.json.
- в репозитории необходимо нажать на кнопку `Add file`, далее `Create new file`
- в названии ввести `bug_report.json`
- добавить: 
```
{ 
  "Sammary" : "Application crash on clicking the SAVE button while creating a new user",
  "Reported_By" : "Ekaterina U",
  "Build_Number" : "Version Number 5.0.1",
  "Enviroment" : "Windows 7, Chrome 31.0.1650.63 m",
  "Severity" : "HIGH",
  "Priority" : "HIGH",
  "Description" : "Application crashes upon clicking the SAVE button while creating a new the user, hence unable to create a new user",
  "Steps_to_Reproduce" : { "1" : "Login into the Application",
                           "2" : "Navigate to the Users Menu -> New User",
                           "3" : "Filled out all the user information fields",
                           "4" : "Clicked on the ‘Save’ button",
                           "5" : "Seen an error page ORA1090 Exception: Insert values Error",
                           "6" : "See the attached logs for more information",
                           "7" : "Also see the attached screenshot of the error page"
                         },
  "Expected Result" : "On clicking the SAVE button you should be prompted to a successful message New User has been created successfully"
}
``` 

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. \
- нажать на кнопку `Commit new file`

 17. Синхронизировать внешний и локальный репозиторий JSON \
- в терминале GitBash ввести `git pull`

