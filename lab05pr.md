# Презентация по выполнению лабораторной работы №5
       Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки

***Российский Университет Дружбы Народов***  
***Факультет Физико-Математических и Естественных Наук***  

 ***Дисциплина:*** *Операционные системы*  
 
 ***Студент:*** *Евсельев Дмитрий*    
 
 ***Группа:*** *НПМ-01-20*  
 
 
## Цель работы 
   >Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

## Задание 

1. Определите полное имя вашего домашнего каталога. Далее относительно этого каталога будут выполняться последующие упражнения.
2. Выполните следующие действия:
    1. Перейдите в каталог /tmp.
    2. Выведите на экран содержимое каталога /tmp . Для этого используйте команду ls с различными опциями. Поясните разницу в выводимой на экран информации.
    3. Определите, есть ли в каталоге /var/spool подкаталог с именем cron ?
    4. Перейдите в Ваш домашний каталог и выведите на экран его содержимое. Определите, кто является владельцем файлов и подкаталогов?
3. Выполните следующие действия:
    1. В домашнем каталоге создайте новый каталог с именем newdir .
    2. В каталоге ~/newdir создайте новый каталог с именем morefun .
    3. В домашнем каталоге создайте одной командой три новых каталога с именами letters , memos , misk . Затем удалите эти каталоги одной командой.
    4. Попробуйте удалить ранее созданный каталог ~/newdir командой rm . Проверьте, был ли каталог удалён.
    5. Удалите каталог ~/newdir/morefun из домашнего каталога. Проверьте, был ли каталог удалён.
4. С помощью команды man определите, какую опцию команды ls нужно использовать для просмотра содержимое не только указанного каталога, но и подкаталогов, входящих в него.
5. С помощью команды man определите набор опций команды ls , позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов.
6. Используйте команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm. Поясните основные опции этих команд.
7. Используя информацию, полученную при помощи команды history , выполните модификацию и исполнение нескольких команд из буфера команд   

## Выполнение   

1. Определите полное имя вашего домашнего каталога. Далее относительно этого каталога будут выполняться последующие упражнения.

![pwd](screens/1.png)  

2. Выполните следующие действия:
    1. Перейдите в каталог /tmp.

![cd /tmp](screens/2.png)  

2. Выведите на экран содержимое каталога /tmp . Для этого используйте команду ls с различными опциями. 

![ls](screens/3.png)  

![ls -l](screens/4.png)  

![ls -a](screens/5.png)  

Отличие: ls без ключей показывает содержимое каталога без доп. информации. ls - l выводит содержимое списком и показывает инф. о правах, владельце, дате редактирования и т.д. ls -a показывает содержимое, в том числе скрытые файлы.

3. Определите, есть ли в каталоге /var/spool подкаталог с именем cron ?
4. Перейдите в Ваш домашний каталог и выведите на экран его содержимое. Определите, кто является владельцем файлов и подкаталогов?

![cron](screens/6.png)  

3. Выполните следующие действия:
    1. В домашнем каталоге создайте новый каталог с именем newdir .
    2. В каталоге ~/newdir создайте новый каталог с именем morefun .
    3. В домашнем каталоге создайте одной командой три новых каталога с именами letters , memos , misk . Затем удалите эти каталоги одной командой.
    4. Попробуйте удалить ранее созданный каталог ~/newdir командой rm . Проверьте, был ли каталог удалён.
    5. Удалите каталог ~/newdir/morefun из домашнего каталога. Проверьте, был ли каталог удалён.

![directions](screens/7.png)  

4. С помощью команды man определите, какую опцию команды ls нужно использовать для просмотра содержимое не только указанного каталога, но и подкаталогов, входящих в него.

![man ls](screens/8.png)  

5. С помощью команды man определите набор опций команды ls , позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов.

![man ls](screens/9.png)  

![man ls](screens/10.png)  

6. Используйте команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm. Поясните основные опции этих команд.

![man pwd](screens/11.png)  

![man mkdir](screens/12.png)  

![man rmdir](screens/13.png)  

![man rm](screens/14.png)  

7. Используя информацию, полученную при помощи команды history , выполните модификацию и исполнение нескольких команд из буфера команд   

![Изменение команд из буфера](screens/15.png)  

# Вывод
> Приобрел практические навыкы взаимодействия пользователя с системой посредством командной строки.