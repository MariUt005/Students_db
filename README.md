# Students_db

Курсовая работа.
**Вариант 51:**
  Разбить группу на 2 части, с поиском среди лиц определенного пола:
  - студентов, поступивших в ВУЗ в одном и том же году;
  - студентов, поступивших в ВУЗ в другие годы, отличные от части 1.


Гарантируется работа на дистрибутиве ubuntu 20.04.
Для сборки необходимо наличие **cmake**.

# Установка
В терминале:
```sh
git clone https://github.com/llollcat/Students_db
cd Students_db/
cmake CMakeLists.txt
make
```
Для запуска, в директории с программой:
```sh
./students_db 
```

# Добавление студентов для примера
Запустить программу с параметром **-generate N**, где N - количество студентов для генерации

# Выполнение варианта 51
- После запуска программы и ввода пароля шифрования создать два листа с разными названиями с помощью команды newL.
- Отфильтровать каждый лист с помощью команды findS и параметра поиска YFE=*/Год поступления\*.
- Вывести каждый лист с помощью команды print.