# hw9
## Работа с летописью временных лет
**Шаг 1.**  
Надо было убрать все пустые строки.
Использовал регулярное выражение: \[^а-ѵА-Ѵ\d\w\.\,\;\:\]\[\"\«\»\—\<\>\{\}].\s\[^а-ѵА-Ѵ\d\w\.\,\;\:\]\[\"\«\»\—\<\>\{\}]  
Заменил все вхождения на пустоту, иными словами, убрал.  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%201.jpg)  
**Шаг 2.**  
Надо было найти всех князей и города, имя и название которых оканчивается на "слав".  
Использовал регулярное выражение: (\[А-Я])[а-я]{1,10}слав(\[а-яцуеѣъьѵ]){1,10} 
Всего найдено было 564 вхождений.  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%202.jpg)  
**Шаг 3.**  
надло Найти все упоминания Новгорода. Учтите, что написание может быть разным.  
Использовал регулярное выражение: Нов(.?)город\[цуеѣъьаѵа-я]{1,2}  
Всего найдено было 57 вхождений.  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%203.jpg)    
**БОНУСный шаг**  
Использовал регулярное выражение: (\[-!?".,:;])  
Все выделенное заменил на: "$1 "  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Бонус.jpg)  
