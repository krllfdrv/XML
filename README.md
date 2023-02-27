# XML
1. Создать внешний репозиторий c названием XML. 
2. Клонировать репозиторий XML на локальный компьютер.
`mkdir XML`  
`cd XML`  
`git clone https://github.com/krllfdrv/XML.git` 
3.  Внутри локального XML создать файл “new.xml”. 
 `cd XML`  
`touch new.xml`  
`git status`  
4. Добавить файл под гит. 
 `git add new.xml`  
`git status` 
5. Закоммитить файл.
 `git commit -m "Xml"`
6. Отправить файл на внешний GitHub репозиторий. 
 `git push`
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML. 
 `vim new.xml`  
`cat new.xml` 
8. Отправить изменения на внешний репозиторий. 
 `git status`  
`git commit -am "added main info"` 
`git push`  
9. Создать файл preferences.xml 
 `touch preferences.xml`
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. 
 `vim preferences.xml`  
`cat preferences.xml` 
11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML 
 `touch skills.xml`
 `vim skills.xml`  
`cat skills.xml`
12. Сделать коммит в одну строку. 
 `git status`  
`git add  preferences.xml skills.xml`  
`git status`  
`git commit -m "added skills and preferences"`  
13. Отправить сразу 2 файла на внешний репозиторий. 
 `git push` 
14. На веб интерфейсе создать файл bug_report.xml. 
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. 
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
18. Синхронизировать внешний и локальный репозиторий XML  
`git pull`
