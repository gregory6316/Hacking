```
Lab: SQL injection UNION attack, finding a column containing text
Задача: Make the database retrieve the string: '2GKU4A'
```
- Выбираем любую категорию
![](1.png)
- Начинаем перехват
![](2.png)
- Отправляем в repeater
![](3.png)
- Находим строчку с category
![](4.png)
- Добавляем строчку "'UNION+SELECT+NULL--", чтобы выяснить количество столбцов
![](5.png)
- Добавляем NULL пока не исчезнет ошибка
![](6.png)
![](7.png)
- Заменяем NULL по очереди на требуюмую строчку пока не достигнем результата
![](8.png)
- Задание выполнено!

