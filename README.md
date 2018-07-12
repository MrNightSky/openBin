# openBin
Program for decoding .bin file from Aktakom oscilloscope
Данная программа создана для Python3

## Что необходимо для работы с данной программой
Вобщем то не так уж и много. Сама программа предназначена для пакетного преобразования файлов, полученных с осциллографа Актаком, из формата .bin в формата .xlsx. Для работы необходим paths.xlsx файл, в котором в первой ячейке стоит 0, а дальше в этом же столбце идут подряд пути к папкам, в которых находятся .bin файлы. Папок (как и путей к ним) может быть сколько угодно, количество .bin файлов в папке также не ограничено. Программа автоматически обрабатывает все .bin файлы, находящиеся по указанному пути, поэтому будьте внимательны, чтобы в данной папке не оказался посторонний .bin файл. Выходные файлы имеют такое же название, как и исходный .bin файл.

В данном репозитории также представлен пример того, как должен выглядеть файл path.xlsx

### Внимание!
Полученные таблицы формата .xlsx отличаются по формату расположения данных от таблиц .xls, полученных с помощью родной актакомовской программы. Возможно возникновение ошибок в случае последующего использования их в других программах обработки данных.
