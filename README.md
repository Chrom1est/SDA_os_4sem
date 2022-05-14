<h1>Makefile</h1>
Компиляция - makefile ab <br>
Запуск программы - ./ab.out <br>
(a - номер лекции, 23 или 4, b -0 номер программы)
<h1>Описание программ</h1>
<br>
Lec2-3, Program1<br><br>
(Example 1, normal memory input)<br>
Enter length of array: 1 <br>
Allocated 4 bytes<br><br>
(Example 2, wrong memory input) <br>
Enter length of array: -1<br>
Error: can't allocate memory: Not enough space<br><br>
Пример программы динамического выделения памяти для массива.<br>
В начале происходит выделение памяти для void (malloc), далее указатель переводится на тип int и делается проверка выделения памяти. В конце память освобождается.<br><br><br>
Lec2-3, Program2 <br><br>
(Example 1)<br>
fd = 3 <br>
called read( 3, c, 10). returned that 0 bytes were read. <br> 
closed the fd. <br><br>

Пример программы чтения данных.<br>
В начале происходит выделение памяти для void (malloc), далее указатель переводится на тип char, далее создается дескриптор и выводится его значение. Происходит чтение 10 байт, после чего записывается терминальный ноль в конец строки и закрывается файл.
