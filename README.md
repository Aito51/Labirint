# Labirint

> ### Наш главный герой попал в лабиринт полный врагов. Ему нужно дойти до своей принцессы и спасти её. Но если герой коснется стены или врага, он сразу же погибнет. К счастью герой может убивать врагов стреляю по ним.
> ![lab_screen_shot](https://user-images.githubusercontent.com/111111384/184305973-8484db1b-ae1a-4351-80b4-b44ad77c7b51.PNG)

## Начало кода
**Здесь я загрузил библиотеку pygame и создал переменные которые будут использованы в коде.**
![image](https://user-images.githubusercontent.com/111111384/184309272-7a9a5e7e-f7e9-4659-9c89-cd0b50d0bfdb.png)

**Загрузил музыку Eagles of Death Metal - Miss Alissa, добавил шрифт и создал два текста. 1 - текст победы игрока. 2 - текст поражений игрока.**

![Расходный материал](https://user-images.githubusercontent.com/111111384/184553611-68fb0656-7b17-4004-83d1-9a56b9913275.png)


## Создание классов

> **Классы GameSprite и Wall унаследовали свойства класса sprite.Sprite из библиотеки pygame вызвав его конструктор. Остальные классы будут наследовать свойства и методы класса GameSprite. Свойства класса GameSprite это изображение, его место появление по кординатам, ширина, высота и скорость. Так же я добавил метод отображение спрайта - reset. В нём я использовал функцию blit().**

![Расходный материал](https://user-images.githubusercontent.com/111111384/184553954-8a15105d-11a1-43c4-98af-aa337b92cc07.png)

> **Класс Player и класс Bullet унаследовали свойства и метод класса GameSprite. Я добавил метод передвижение update и метод стрельбы fire в классе Player. Игрок может передвигатся вверх нажав клавишу w, вниз клавишу s, влево клавишу a, вправо клавишу d. В методе fire создается пуля по классу Bullet и затем добавляется к группе пуль. А в самом классе Bullet тоже есть метод передвижение update. Но если пуля вылетит за сцену, он исчезнет.**

![Расходный материал](https://user-images.githubusercontent.com/111111384/184554189-bf8c53d4-9841-467a-9693-3872d99501eb.png)

> **Классы Enemy1 и Enemy2 став наследниками класса GameSprite так же имеют метод передвижение update. Но Enemy1 передвигается слева направо, а Enemy2 сверху вниз.**

![Расходный материал](https://user-images.githubusercontent.com/111111384/184554327-8f265928-67b7-4ba7-80e5-e973fe2bb69e.png)

> **Классы Enemy3, Enemy4 и Enemy5 ходят так же как и Enemy1, Enemy6 так же как и Enemy2 но только с другуми цифрами.**

![Расходный материал](https://user-images.githubusercontent.com/111111384/184554480-efe0e8b7-cc58-477f-82aa-23dbb7cb2686.png)
![image](https://user-images.githubusercontent.com/111111384/184554507-41423b7c-ad9b-4155-b6db-6a2ba8a2d43a.png)










**В качестве изоброжение игрока я выбрал фото оранжевого косманавта в игре Among Us. А иконку принцессы я взял из игры Super Mario. Изображение врагов я взял фоту 
приведение из игры Pac-Man.**

![orange_amogus](https://user-images.githubusercontent.com/111111384/184306448-20c3dfb0-8670-4573-ad6d-e0f469a58062.png)
![princess_mario](https://user-images.githubusercontent.com/111111384/184305169-2313b9cd-ec2d-4718-bd5c-e9b7f5147d27.jpg)
![enemy_pacman](https://user-images.githubusercontent.com/111111384/184305149-bc3862ee-b407-4d4d-9e26-1331a19df290.jpg)
