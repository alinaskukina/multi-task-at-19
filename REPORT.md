# Первое задание
### из 5 воркеров время работы составляет 36020 ms
![](5_work.png)
### из 10 воркеров время работы составляет 24530 ms
![](10_work.png)
### из 100 воркеров время работы составляет 18600 ms
![](100_work.png)

#### Чтобы увеличить скорость проверки ссылок, надо использовать ThreadPoolExecutor. 
#### Если изменять количество воркеров, то существенно это не влияет на загрузку памяти и процессора. Но, как можно заметить по данным выше, увеличение количества воркеров приводит к уменьшению времени работы программы, а также к увелечению активности отправки и получения в сети.

# Второе задание
#### Генерация одной монеты на одном ядре в среднем занимает от 40000 до 60000ms.
### из 2 воркеров время генерации пяти монет составляет 29743 ms
![](2_work2.png)
### из 4 воркеров время генерации пяти монет составляет 27192 ms
![](4_work2.png)
### из 5 воркеров время генерации пяти монет составляет 24130 ms
![](5_work2.png)
### из 10 воркеров время генерации пяти монет составляет 26391 ms
![](10_work2.png)
### из 100 воркеров время генерации пяти монет составит 22815 ms
![](100_work2.png)

#### Исходя из данных выше видно, что изменение количества воркеров влияет на загрузку памяти и процессора. 