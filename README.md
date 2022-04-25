# Программа для объединения файлов Excel :capital_abcd:
### Соединение всех Exel таблиц по месяцам :shipit:

Запуск осуществляется через cmd со следующими параметрами:

>- `-d` :inbox_tray: Папка для чтения
>- `-n` :package: Поиск по вложенным папкам
>    - `true` - Ищет только во вложенных папках
>    - `false` - Осуществляет объединение в родительской папке [по умолчанию]
>- `-o` :outbox_tray: Папка вывода объединенного файла\
>- `-c` :floppy_disk: Ищет в директории выхода последний скомпилированный файл
>    - `true` - начинать с последнего найденного файла [по умолчанию]
>    - `false` - начинать сначала
>- `-i` :speech_balloon: Уровень информирования, выбор из 3 доступных:
>    - `None` - Без консольного вывода
>    - `Main` - Только главные процессы [по умолчанию]
>    - `All` - Полный вывод, аж на каждую ячеечку


##### Пути к папкам в PowerShell окружать символом `'`. Пример:
```
.\UseExcel.exe -d 'C:\Users\Username\Downloads\resources' -o 'C:\Users\Username\Downloads\resources out'
```

<details> 
  <summary>Схема скрипта</summary>
  
   ![схема скрипта](https://user-images.githubusercontent.com/58171847/152562046-d859c65e-bd69-4342-b2e7-32a9b36ab702.png)
  
</details>

