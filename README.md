# Home_Work5
1. Проверить XML, правильно ли он составлен, не имеет ли он ошибок, если есть какие-либо недочеты, предоставьте правильный вариант в файле 1.xml 
(xml-парсер: https://jsonformatter.org/xml-formatter ):

<user>
<name>"Иван"</name>
<surname>"Иванов"</surname>
<patronymic>"Иванович"</patronymic>
<age>"30"</age>
<phone>"Москва"</phone>
<birthplace>"+7 926 766 48 48"</birthplace>
</user

 

<?xml  version=”1.0” encoding=”UTF-8”?>
<user>
<name>Иван</name> // убраны кавычки между тегами
<surname>Иванов</surname>
<patronymic>Иванович</patronymic>
<age>30</age>
<phone>+7 926 766 48 8</phone> // «+7» заменены на «8»
<birthplace>Москва</birthplace> // поменяны местами в соответствии с тегами данные места рождения и номера тлф
</user> // закрыт тег user

 
2. Проверить JSON, правильно ли он составлен, не имеет ли он ошибок, если есть какие-либо недочеты, предоставьте правильный вариант в файле 2.json 
(json-парсер: https://jsonformatter.org/json-parser):

name: "Иван",
surname: "Иванов",
patronymic: "Иванович",
age: "30",
birthplace: "Москва",
phone: +7 926 766 48 48,
 

\\ если один объект описывать, то используем фигурные скобки, если перечисление - массив – квадратные.
	{
“name“: "Иван", // в кавычки заключаются все аргументы и значения
“surname“: "Иванов",
“patronymic“: "Иванович",
“age“: “30”,
“birthplace“: "Москва",
“phone“: “8 926 766 48 48“ // «+7» заменены на «8»
} 

 
