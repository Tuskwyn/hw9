# hw9
## Работа с повестью временных лет
### Работал в Notepad++
**Шаг 1.**  
Надо было убрать все пустые строки.
Использовал регулярное выражение: ^\s+  
Заменил все вхождения на пустоту, иными словами, убрал.  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%201.jpg)  
**Шаг 2.**  
Надо было найти всех князей и города, имя и название которых оканчивается на "слав".  
Использовал регулярное выражение: \[А-Я]\[а-яѵѣ]+(слав)\[а-яѵѣ]+  
Учел, что могут быть буквы, которые могут не входить в диапазон А-Я\а-я.  
Всего найдено было 564 вхождений.  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%202.jpg)  
**Шаг 3.**  
Надо было найти все упоминания Новгорода. Учел, что написание может быть разным, а также что могут быть буквы, которые могут не входить в диапазон А-Я\а-я.  
Использовал регулярное выражение: (Нов)[а-яѣѵ]+(город)[а-яѣѵ]+  
Всего найдено было 56 вхождений.  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Шаг%203.jpg)    
**БОНУСный шаг**  
Использовал регулярное выражение: \[(-+)!?".,:;]  
Все выделенное заменил на: "$& "  
*Скриншот:* [Тыц](https://github.com/Tuskwyn/hw9/blob/master/Бонус.jpg)  
