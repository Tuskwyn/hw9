# hw9
## Работа с летописью временных лет
**Шаг 1.**  
Использовал регулярное выражение: \[^а-ѵА-Ѵ\d\w\.\,\;\:\]\[\"\«\»\—\<\>\{\}].\s\[^а-ѵА-Ѵ\d\w\.\,\;\:\]\[\"\«\»\—\<\>\{\}]  
Заменил все вхождения на пустоту, иными словами, убрал.  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%201.jpg)  
**Шаг 2.**  
Использовал регулярное выражение: (\[А-Я])(\[а-я]){1,5}слав(\[а-я]){1,3)}  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%202.jpg)  
**Шаг 3.**  
Использовал регулярное выражение: Нов(\[а-я]){1,2}город(\[а-я]){1,2}  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%203.jpg)    
**БОНУСный шаг**  
Использовал регулярное выражение: (\[-!?".,:;])  
Все выделенное заменил на: "$1 "  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Бонус.jpg)  
