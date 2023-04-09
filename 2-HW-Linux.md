1. Узнать полный путь текущего каталога: `pwd`
2. Вывести на экран ПОЛНОЕ содержимое текущего каталога: `ls -la`
3. Создать каталог otusHW: `mkdir otusHW`
4. Прейти в каталог otusHW: `cd otusHW`
5. Вывести в консоль информацию о файловой системе (точки монтирования, занимаемый размер, свободное место): `df -h`
6. Информацию из пункта 5 вывести в файл fsInfo: `df -h > fsInfo`
7. Вывести на экран содержимое файла fsInfo: `cat fsInfo`
8. Вывести на экран строчки файла fsInfo, в которых есть цифра 1, если таких нет, то цифра 2: `grep "1" fsInfo || echo "8"`
9. Сделать копию файла fsInfo - fsInfoCopy: `cp fsInfo fsInfoCopy`
10. Сделать копию файла fsInfo - fsInfoCopy2: `cp fsInfo fsInfoCopy2`
11. Переименовать fsInfoCopy2 в fsInfoCopy3: `mv fsInfoCopy2 fsInfoCopy3`
12. Удалить fsInfoCopy3: `rm fsInfoCopy3`
13. Вывести на экран первые строки fsInfoCopy: `head fsInfoCopy`
14. Вывести на экран последние строки fsInfoCopy: `tail fsInfoCopy`
15. Создать файл runIt: `touch runIt`
16. В vi открыть файл runIt: `vi runIt`
17. В файл runIt добавить команду копирования fsInfo в fsInfoFinal. Для этого нажать клавишу i для перехода в режим вставки, ввести следующую команду `cp fsInfo fsInfoFinal` и сохранить файл нажатием клавиши Esc, введя затем команду `:wq`
18. Сделать runIt исполняемым: `chmod +x runIt`
19. Выполнить runIt и убедится, что он отработал как надо: `./runIt`
   Это должно скопировать файл fsInfo в файл fsInfoFinal. Это можно проверить, что это произошло, выполнив команду: `cat fsInfoFinal`
