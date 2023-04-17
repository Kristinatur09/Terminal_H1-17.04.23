# Git_bash_H1, 17.04.23
________________________

* Вывести текущую рабочую директорию - ***$ pwd***

- Создать папку - ***$ mkdir folder***

+ Зайти в папку - ***$ cd folder***

+ Создать 3 папки - ***$ mkdir test1 test2 test3***

+ Зайти в любоую папку - ****$ cd test1***

+ Создать 5 файлов (3 txt, 2 json) - ***$ touch {1..3}.txt {1..5}.json***

+ Создать 3 папки -  ***$ mkdir folder_{1..3}***

+ Вывести список содержимого папки - ***$ ls -la***

+ Открыть любой txt файл - ***$ vim 1.txt***

+ Написать туда что-нибудь, любой текст.- ***i - Hello world***

+ Сохранить и выйти - ***esc***
                     - ***:wq;***

+ Выйти из папки на уровень выше - ***$ cd ..***

+ Переместить любые 2 файла, которые вы создали, в любую другую папку - ***$ mv test1/1.txt test2/1.txt***

+ Скопировать любые 2 файла, которые вы создали, в любую другую папку - ***$ cp test2/qa1.txt  test1/qa1.txt***

+ Найти файл по имени - ***$ find . -name "1*"***

+ Найти папку - ***$ find -type d -name folder_1*** 

+ Просмотреть содержимое в реальном времени (команда grep) изучите как она работает - ***tail -f qa1.txt | grep '.*'***

+ Вывести несколько первых строк из текстового файла - ***$ head -n 5 1.txt***

+ Вывести несколько последних строк из текстового файла - ***$ tail -3 1.txt***

+ Просмотреть содержимое длинного файла (команда less) изучите как она работает -  ***$ less 1.txt***

+ Вывести дату и время - ***$ date***
_______
# Задание *

1) Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request - 

                                                 curl "http://162.55.220.72:5005/terminal-hw-request"

                                                 $ curl "http://162.55.220.72:5005/get_method?"name"="Kris"&"age"=29"
 
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13 - 

   :small_orange_diamond: создаем файл скрипта с командами в расширении sh
   
   :small_orange_diamond: запускаем скрипт sh test.sh
   
