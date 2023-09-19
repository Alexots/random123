# random123
![image](https://github.com/Alexots/random123/assets/115954644/84f5f2f7-856f-42f2-ab85-8b2f5d518483)

## Простой рандомизатор заданий 
### Что делает:
1) Берет все обязательные задания
2) Рандомно берет необязательные
3) Дублирует если необходимо
4) Перемешивает
5) Сохраняет в эксель

### В консоли:
1) pip3 install -r req.txt 
2) jupyter-lab
3) По очереди исполняем ячейки, все интуитивно понятно

### В таблице data/data.xlsx:
1) must: y или n - обязательное задание или нет
2) number: максимальное количество копий заданий
3) from: допустим 6 - выбирается рандомное число от 6 до 10, делится на 10 и умножается на number 👆. Т.е. промежуток рандомного количества копий
4) should_perc: доля случайных заданий. Допустим 5: (5/10)*20  из 20 данных, будут выбраны случайно 10
