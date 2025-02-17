DocBox - это веб-приложение, которое позволяет запускать различные операционные системы и среды разработки в веб-браузере.

Шаги для открытия Pascal через DocBox:

1. **Откройте DocBox**: Перейдите на сайт DocBox и авторизуйтесь с помощью своей учетной записи.
    
2. **Выберите среду разработки**: В меню DocBox выберите "Среды разработки" и найдите "Free Pascal" или "Pascal" в списке доступных сред.
    
3. **Запустите среду разработки**: Нажмите на кнопку "Запустить" рядом с выбранной средой разработки.
    
4. **Откройте терминал**: В открывшемся окне среды разработки откройте терминал.
    
5. **Запустите компилятор Pascal**: В терминале введите команду `fpc` (Free Pascal Compiler) или `ppc` (Pascal Compiler), в зависимости от версии Pascal, которую вы используете.
    
6. **Создайте файл с расширением .pas**: Создайте файл с расширением `.pas` и введите код Pascal в этом файле. Например, создайте файл `hello.pas` и введите код:
	```python
	program Hello;
	begin 3
	  writeln('Hello, World! '); 
	end.
```

	
7. **Скомпилируйте файл**: Введите команду `fpc hello.pas` или `ppc hello.pas`, в зависимости от версии Pascal, которую вы используете.
    
8. **Запустите программу**: Введите команду `./hello` (имя файла без расширения `.pas`), и программа будет запущена.
	
```python
	$ fpc hello.pas
	$ ./hello
	Hello, World!
```
