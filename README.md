V8Unpack: Утилита для распаковки / сборки 1C-файлов *.cf *.epf, *.ert
Это форк проекта [leoniv/v8unpack](https://github.com/leoniv/v8unpack) в основном для дополнения документации. 

## Документация

* [Wiki](https://github.com/AlexKalinin/v8unpack/wiki)

## Скачать / Download
* [V8Unpack v 2.0](https://github.com/AlexKalinin/v8unpack/wiki/builds/V8Unpack20.zip)
* Все загрузки: https://github.com/AlexKalinin/v8unpack/wiki/Home
 


***

###### v8Unpack, GCC edition
Добавлен проект CodeBlocks 13.12.
Для сборки требуется Boost.

###### Fork of v8Unpack project by Denis Demidov (disa_da2@mail.ru)

[Original project HOME](https://www.assembla.com/spaces/V8Unpack/team)

[Original project svn repo](http://svn2.assembla.com/svn/V8Unpack/)

###### Note

V8Unpack - a small console program  for rebuild/build configuration files [1C](http://1c.ru) such as *.cf *.epf *.erf
 
###### Plaform 

Windows, POSIX

###### Environment

Project for [codelite IDE](http://www.codelite.org/)  
Project for [Codeblocks IDE](http://codeblocks.org/)

###### Version 3.0

- Оптимизирована сборка .cf файла ключ -B[UILD]. В версии 2.0 сборка корневого контейнера происходила в оперативной памяти.
При сборке больших конфигураций это могло приводить к ошибке "segmentation fault". В версии 3.0 сборка корневого контейнера происходит 
динамически с сохранением элементов контейнера непосредственно в файл по мере их создания.
