# File Manager App
### Грибцов Артем ИСП-201
---
### Команды:
- **cd > <путь>** - изменение локальной директории +
- **ls | list** - просмотр файлов 1 уровня локальной директории +
- **f_info > <путь>** - просмотр информации о файле +
- **dir_info > <путь>** - просмотр информации о директории +
- **f_del > <путь>** - удаление файла по пути + 
- **dir_del > <путь>** - удаление директории по пути +
- **f_copy > <путь к файлу> > <директория>** - копирование файла +
- **dir_copy > <директория 1> > <директория 2>** - копирование директории +
- **f_move > <откуда> > <куда>** - перемещение файла
- **dir_move > <откуда> > <куда>** - перемещение директории
- **tree > <путь>** - показать всё дерево файлов и директорий +
### Описание реализованного функционала:
##### FileManagerCommands:
- ***Commands/*** :
    - Реализована логика для изменения локальной директории в **CdCommand.cs**
    - Реализована логика для копирования директории в **DirectoryCopyCommand.cs**
    - Реализована логика для удаления директории в **DirectoryDeleteCommand.cs**
    - Реализована логика для получения информации о директории в **DirectoryInfoCommand.cs**
    - Реализована логика для перемещения директории в **DirectoryMoveCommand.cs**
    - Реализована логика для копирования файла в **FileCopyCommand.cs**
    - Реализована логика для удаления файла в **FileDeleteCommand.cs**
    - Реализована логика для получения информации о файле в **FileInfoCommand.cs**
    - Реализована логика для перемещения файла в **FileMoveCommand.cs**
    - Реализована логика для просмотра файлов 1 уровня локальной директории в **ListCommand.cs**
    - Реализована логика для просмотра всех файлов и вложенных директорий в **TreeCommand.cs**
- Добавлена логика связанная с локальной директорией в **Manager.cs**
##### FileManagerConsoleApi:
- Реализована логика передачи комманд и аргументов в *Manager* в **MainPage.xaml**.
### Скриншоты работы программы:

**cd, list, tree:**
![Скриншот 1](https://sun9-84.userapi.com/impg/JnhvDjSReIFcZAIeoBbURrdijDc_5f7y39hwOQ/KktAAxBO1Pc.jpg?size=981x510&quality=96&sign=0841baab4fa6e9a57e75a7b6317f01f4&type=album)

**f_info, dir_info:**
![Скриншот 2](https://sun9-87.userapi.com/impg/RTG_Yl8plvSaiJnVLSc_QEF_N6vex1iApQzA5g/CQ0joR_XpcE.jpg?size=980x512&quality=96&sign=c109386cdf9cb1040eb63d432c368d6d&type=album)

**dir_del, f_del:**
![Скриншот 3](https://sun9-81.userapi.com/impg/-O_eg3e7C89oW2lXff34NCIAcVdXhwreiMp-PA/puwDjppg2Ks.jpg?size=979x513&quality=96&sign=c0cd5ce76d5540f43acb7384e0a739e1&type=album)

**f_copy, dir_copy:**
![Скриншот 4](https://sun9-79.userapi.com/impg/nISkX6HbbPGLkoeXschirWGPpmG2aiEKDfDrQw/AKR9knd7PLs.jpg?size=979x513&quality=96&sign=86ad0155787e601acc593904b1072df0&type=album)

**f_move, dir_move:**
![Скриншот 5](https://sun9-6.userapi.com/impg/rMgnRjxWaz4iscLlXQIPc2yQj0KkLdcPmi28JA/OwDNS9OAUQM.jpg?size=977x513&quality=96&sign=b432c4999442ae73a1e98218da1f29ff&type=album)