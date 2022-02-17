# HW_Git_TXT

 1. Создать внешний репозиторий c названием TXT.
 2. Клонировать репозиторий TXT на локальный компьютер.
     
     > git clone https://github.com/dkovalenkoqa/HW_Git_TXT.git
 3. Внутри локального TXT создать файл “new.txt”.
     > touch new.txt
 4. Добавить файл под гит.
     > git add new.txt
 5. Закоммитить файл.
     > git commit -m "add new.txt"
 6. Отправить файл на внешний GitHub репозиторий.
     > git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
       ```
        FNM - Kovalenko Dmytro Mikhailovich
        Age - 22
        Pets - 0
        Salary - 500
       ```
 8. Отправить изменения на внешний репозиторий.
     > git add new.txt

     > git commit -m ""update new.txt"

     > git push 
 9. Создать файл preferences.txt
     > touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
     ```
      Favorite movie - Interstellar 
      Favorite series - Game of Thrones
      Favorite food - Spaghetti
      Favorite season - Summer
      Country - Switzerland
     ```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
     > touch skills.txt

     ```
      Terminal
      Git
      Postman
      SQL
      Jmeter
      Python
      Fiddler
     ```
 12. Сделать коммит в одну строку.
     > git add . && git commit -m "add preferences.txt skills.txt"
 13. Отправить сразу 2 файла на внешний репозиторий.
     > git pull
 14. На веб интерфейсе создать файл bug_report.txt.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий TXT

     > git pull
