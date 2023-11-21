# CV_2023_lab5
## Сегментация
Команда:  
Байрамова Хумай   
Данишевский Никита  
Калинин Александр  
Лисицина Василиса  

## Датасет
Датасет был разделён в соотношении 20% к 80%:
- Validation set - 300 изображений;
- Training set - 1225 изображений

## Решение
Имплементация модели из [статьи](https://arxiv.org/pdf/2004.01241.pdf)  
![image](https://github.com/DanishevskiyNS/CV_2023_lab5/blob/main/images/model_architecture.png)  
Оптимизатор - Adam, lоss - cross_entropy, batch_size = 16, количество эпох - 50

## Метрики
|Data|IoU|IoU by class|Pixel accuracy|
:---: | :---: | :---: | :---: 
Validation set|0.62| [0.546  0.569  0.7197 0.6567 0.1785 0.576  0.2732 0.2329]| 0.74
Test set| 0.57 | [0.694  0.3389 0.721  0.3696 0.1796 0.3354 0.2334 0.3403] | 0.72
---
