# random123
## Простой рандомизатор заданий 

### В консоли:
1) pip3 install -r req.txt 
2) jupyter-lab
3) По очереди исполняем ячейки, все интуитивно понятно

### В таблице data/data.xlsx:
1) must: y или n - обязательное задание или нет
2) number: максимальное количество копий заданий
3) from: допустим 6 - выбирается рандомное число от 6 до 10, делится на 10 и умножается на number 👆. Т.е. промежуток рандомного количества копий
4) should_perc: доля случайных заданий. Допустим 5: (5/10)*20  из 20 данных, будут выбраны случайно 10
