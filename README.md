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

![]()

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
```bash
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
Command: git commit -m "modify new.xml"
Command: git push
```
12. Создать файл preferences.xml
```bash 
Command: touch preference.xml
```
13. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```bash
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
14. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML.
```bash 
Command: touch skills.xml
```
```bash
Command: cat >> skills.xml
{
    "skills": ["SDLC", "STLC", "HTTP", "JSON", "XML", "API", "Postman", "Charles", "Fiddler", "DevTools", "VPN", "SQL", "Redis"]
}
```
15. Сделать коммит в одну строку.
```bash

```

16. Отправить сразу 2 файла на внешний репозиторий.
 ```bash 
Command: git add .
```
 ```bash 
Command: git commit -am "add 2 files"
```
 ```bash 
Command: git push
```
16. На веб интерфейсе создать файл bug_report.xml.

![]()

![]()

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

![]()

18. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

![]()

![]()

19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

![]()

20. Синхронизировать внешний и локальный репозиторий XML.
```bash
Command: git pull
```