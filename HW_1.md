# JSON
 #### 4. Создать внешний репозиторий c названием JSON.
	https://github.com/IvanStepanov-QA/JSON.git
 #### 5. Клонировать репозиторий JSON на локальный компьютер.
	$ git clone https://github.com/IvanStepanov-QA/JSON.git
 #### 6. Внутри локального JSON создать файл “new.json”.
	$ cd JSON
	$ touch new.json
 #### 7. Добавить файл под гит.
	 $ git add new.json
 #### 8. Закоммитить файл.
	$ git commit -m "Update 1" 
 #### 9. Отправить файл на внешний GitHub репозиторий.
	$ git push

 #### 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
	$ vim new.json
	{
       	 	"Name": "Ivan",
        	"Age": 33,
        	"Pets": 0,
       	 	"Salary": "^_^"
	}  
 11. Отправить изменения на внешний репозиторий.
	$ git add new.json 
	$ git commit -m "new.json" 
	$ git push      
 12. Создать файл preferences.json
	$ touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
	vim preferences.json  
    {
            "Favorite_movies": "Everything illuminated",
            "Serials": "Samurai Champloo",
            "Favorite_food": "Batat fries",
            "Season": "Summer",
            "Country_to_visit": "Chili"
    }
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 	$ vim touch skills.json
	{
        	"Instruments":  "Terminal, Git, Postman, SQL, Jmeter, CI/CD"
	}
 15. Отправить сразу 2 файла на внешний репозиторий.
	$ git add .  
	$ git commit -m "Update 3"
	$ git push
 16. На веб интерфейсе создать файл bug_report.json.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	JSON-->add file-->create new file-->enter name file-->commit changers
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
	{
	"Num": 1,
  	"Title": "Bug Title",
  	"Severity": "Link"
  	"Steps": "1. Step; 2. Step",
  	"ExpectedResult": "text",
  	"ActualResult": "text",
  	"Enviroment": "win 11, chrome 107",
  	"Comment": "text"
	}
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    --> Commit changes
 20. Синхронизировать внешний и локальный репозиторий JSON
 	$ git pull   

XML
 21. Создать внешний репозиторий c названием XML.
	https://github.com/IvanStepanov-QA/XML.git
 22. Клонировать репозиторий XML на локальный компьютер.
	$ git clone https://github.com/IvanStepanov-QA/XML.git
 23. Внутри локального XML создать файл “new.xml”.
 	$ cd XML
	$ touch new.xml
 24. Добавить файл под гит.
 	$ git add new.xml
 25. Закоммитить файл.
 	$ git commit -m "Update 1"
 26. Отправить файл на внешний GitHub репозиторий.
	$ git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
    <?xml version="1.0" encoding="UTF-8"?>
    <Ivan>
        <field name="Name">Ivan</field>
        <field name="Surname">Stepanov</field>
        <field name="Age">33</field>
        <field name="Pets">0</field>
        <field name="Future salary">^_^</field>
    </Ivan>
 28. Отправить изменения на внешний репозиторий.
	$ git add new.xml
	$ git commit -m "new"
	$ git push
 29. Создать файл preferences.xml
	$ touch preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
	$ vim preferences.xml 
	<?xml version="1.0" encoding="UTF-8"?>
	<Ivan>
        <Favorite_movies> Everything illuminated </Favorite_movies>
        <Serials> Samurai Champloo </Serials>
        <Favorite_food> Batat fries </Favorite_food>
        <Season> Summer </Season>
        <Favorite_coutry> Chili </Favorite_coutry>
	</Ivan>
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 	$ vim skills.xml
	<?xml version="1.0" encoding="UTF-8"?>
	<skills>
	    <skills> Terminal, Git, Postman, SQL, Jmeter, CI/CD </skills>
	</skills>                 
 32. Сделать коммит в одну строку.
	$ git add skills.xml preferences.xml | git commit -m "new3" 
 33. Отправить сразу 2 файла на внешний репозиторий.
 	$ git push   
 34. На веб интерфейсе создать файл bug_report.xml.
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	JSON/add file/create new file/"enter name file/commit changers
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
    <?xml version="1.0" encoding="UTF-8"?>
    <xml>
    <BugReport>
            <ID> 1 <ID>
                <Title> Bug Title </Title>
                <Severity> Major </Severity>
                <Steps> 1. Step; 2. Step </Steps>
                <ExpectedResult> text </ExpectedResult>
                <ActualResult> text </ActualResult>
                <Enviroment> win 11, chrome 107 </Enviroment>
                <Comment> text </Comment>
    </BugReport>
    <xm>     
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	Enter button Commit changes
 38. Синхронизировать внешний и локальный репозиторий XML
 	$ git pull