# TXT
1. Создать внешний репозиторий c названием TXT.  
На вэбе Repositories --> New --> Repos Name:TXT --> Check "Add a README file" --> Press "Create repository"

 2. Клонировать репозиторий TXT на локальный компьютер.  
git clone https://github.com/deleteddeleted/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.  
cd TXT  
touch new.txt   

 4. Добавить файл под гит.  
git add .  
git status

 5. Закоммитить файл.  
git commit -m "Файл добавлен на внешний репозиторий"

 6. Отправить файл на внешний GitHub репозиторий.  
git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  
vim new.txt  
i  
1)name Nastya  
2)surname Vinogradova  
3)Age 25  
4)Pets 1  
5)salary 250000  
esc :wq enter  

 8. Отправить изменения на внешний репозиторий.  
git add .  
git status  
git commit -m "Отредактировано содержание файла"  
git push

 9. Создать файл preferences.txt  
touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.  
 vim preferences.txt  
i  
1)Favorite_movie - The Book Thief  
2)Favorite_TV_series - 13 Reasons Why  
3)Favorite_food - pizza  
4)Favorite_seasons - summer  
5)Country - Norway  
esc :wq enter  

11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT  
vim skills.txt  
i  
1)Terminal  
2)GitBash  
3)API  
4)Postman  
5)Test case  
esc :wq enter

 12. Сделать коммит в одну строку.  
git add . && git commit -m "Коммит в одну строку"

 13. Отправить сразу 2 файла на внешний репозиторий.  
git push

 14. На веб интерфейсе создать файл bug_report.txt.  
Add file --> Create new file --> Name: bug_report.txt

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
Commit New File

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.  
 bug_report.txt --> Edit this file  
  ID:1  
  Summary:Не работает кнопка отправки заказа  
  Steps to Reproduce:  
      1.Пролистать до поля  
      2.Ввести значение в поле  
      3.Ввести значение в поле  
  Actual_Result:кнопка неактивна  
  Expected_Result:кнопка нажимается, можно сделать заказ  
  Attachments:img/video  

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
Commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT  
git pull
