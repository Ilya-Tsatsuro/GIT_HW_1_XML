# GIT_HW_1_XML

# XML

## Задание 
 1. Создайте текстовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash
```bash
Command: cd Desktop/Тестирование/gitrepo/
Перемещаемся в папку, куда будем клонировать репозиторий, который мы только что создали.
```

4. Создать внешний репозиторий c названием XML.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Create%20a%20new%20repository.png?raw=true)
![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Button%20create%20repository.png?raw=true)

5. Клонировать репозиторий XML на локальный компьютер.
```bash
Command: git clone git@github.com:Ilya-Tsatsuro/GIT_HW_1_XML.git    
```

6. Внутри локального XML создать файл “new.xml”.
```bash 
Command: cd GIT_HW_1_XML
Command: touch new.xml
```
7. Добавить файл под гит.
```bash
Command: git add 
```
8. Закоммитить файл.
```bash
Command: git commit -m "add new.xml"
```
9. Отправить файл на внешний GitHub репозиторий.
```bash
Command: git push
```
10. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```xml
Command: cat >> new.xml
<?xml version="1.0" encoding="UTF-8"?>
<root> 
    <about_me>
        <name>Ilia</name>
        <age>29</age>
        <pet>0</pet>
        <desired_salary>5000</desired_salary>
    </about_me>
</root>
```
11. Отправить изменения на внешний репозиторий.
```bash
Command: git commit -am "modify new.xml"
Command: git push
```
12. Создать файл preferences.xml
```bash 
Command: touch preference.xml
```
13. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```xml
Command: cat >> preference.xml
<?xml version="1.0" encoding="UTF-8"?>
<root>
    <preferences>
        <Favorite_movie>The Rock</Favorite_movie>
        <Favorite_TV_series>Lol</Favorite_TV_series>
        <Favorite_food>Sushi</Favorite_food>
        <Favorite_time_of_year>Spring</Favorite_time_of_year>
        <<Country_to_travel>USA</Country_to_travel>
    </preferences>
</root>
```
14. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML.
```xml 
Command: touch skills.xml
Command: cat >> skills.xml
<?xml version="1.0" encoding="UTF-8"?>
<root>
    <skills>
        <skill_1>SDLC</skill_1>
        <skill_2>STLC</skill_2>
        <skill_3>QA_Theory</skill_3>
        <skill_4>HTTP(s)</skill_4>
        <skill_5>XML</skill_5>
        <skill_6>JSON</skill_6>
        <skill_7>DevTools</skill_7>
        <skill_8>API</skill_8>
        <skill_9>Postman</skill_9>
        <skill_10>SQL</skill_10>
    </skills>
</root>
```
15. Сделать коммит в одну строку.
```bash
Command: git add . && git commit -m "add 2 files"
```
16. Отправить сразу 2 файла на внешний репозиторий.
 ```bash 
Command: git push
```
17. На веб интерфейсе создать файл bug_report.xml.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Create%20new%20file.png?raw=true)

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Create%20bug_report.xml.png?raw=true)

18. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Commit%20new%20file.png?raw=true)

19. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Edit%20file.png?raw=true)

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Edit%20file1.png?raw=true)

20. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

![](https://github.com/Ilya-Tsatsuro/Screenshot/blob/main/HW_1_Git/screen_for_xml/Commit%20bagreport.png?raw=true)

21. Синхронизировать внешний и локальный репозиторий XML.
```bash
Command: git pull
```