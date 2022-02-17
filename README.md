## GitBash

1. Посмотреть где я.
   * команда `pwd`.
2. Создать папку.
   * команда `mkdir group_27`.
3. Зайти в папку.
   * команда `cd group_27`.
4. Создать 3 папки.
   * команда `mkdir -p {F_1,F_2,F_3}`.
5. Зайти в любоую папку.
   * команда `cd F_1`.
6. Создать 5 файлов (3 txt, 2 json).
   * команда `touch name{1,2,3}.txt name{1,2}.json`.
7. Создать 3 папки.
   * команда `mkdir folder{1,2,3}`.
8. Вывести список содержимого папки.
   * команда `ls -1`.
9. Открыть любой txt файл.
   * команда `vim name3.txt`.
10. Написать туда что-нибудь, любой текст.
    * нажать кнопку `i`.
    * вводим текст `The United Kingdom is an advanced European island country. 
It is surrounded by three bodies of water: the North Sea, in the eastern part, the English Channel in the southern part, and the Atlantic Ocean in the west. 
The country consists of England, Scotland, Wales, and Northern Ireland. The term “United Kingdom” is often confused with the term “Great Britain”, which is the name of the island, but not the state. 
Many smaller islands and adjacent territories form an integral part of this country, as well as the area of Northern Ireland in the northwest. 
The total area of the country is 242,500 sq. km. The population is over 67 million people, according to the 2020 statistical data.
`.
11. Сохранить и выйти.
    * нажать кнопку, чтобы выйти из режима редактирования `esc`.
    * ввести команду `:wq`.
12. Выйти из папки на уровень выше.
    * ввести команду `cd ..`.
13. Переместить любые 2 файла, которые вы создали, в любую другую папку.
    * ввести команду `mv F_1/{name3.txt,name1.json} F_1/folder1`.
14. Скопировать любые 2 файла, которые вы создали, в любую другую папку.
    * ввести команду `cp F_1/{name1.txt,name2.json} F_1/folder2`.
15. Найти файл по имени.
    * ввести команду `find folder1 -name "name1*"`.
16. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
    * ввести команду `find folder1 -name "name1*"`.
17. Вывести несколько первых строк из текстового файла.
    * ввести команду `head -2 name1.txt`.
18. Вывести несколько последних строк из текстового файла.
    * ввести команду `tail -3 name1.txt`.
19. Просмотреть содержимое длинного файла (команда less) изучите как она работает.
    * ввести команду `less name.txt`.
20. Вывести дату и время
    * ввести команду `date`.
