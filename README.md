# Исследовательский проект "Создание нейросети с нуля на основе архитектуры ResNet"
Research project to develop a neural network from scratch

Для просмотра необходимо запустить resnet_project.ipynb

## Описание
В рамках этого исследовательского проекта была разработана нейронная сеть, которая определяет возраст человека по фотографии лица. Была использована архитектура, аналогичная ResNet-34, которая была создана и обучена с нуля.

## Цель проекта
Основная цель проекта - на практике разобраться в работе сверточных нейронных сетей и архитектуры ResNet. Изучить возможности и преимущества "глубоких" архитектур и применить эти знания на практике, создав собственную модель.

### Использованные технологии
 - Python
 - PyTorch
 - Matplotlib
 - Numpy

## Набор данных
Для обучения и проверки модели был использован датасет APPA-REAL, который содержит 7591 изображений лиц с метками реального возраста.
Доступен по ссылке: [dataset](https://chalearnlap.cvc.uab.cat/dataset/26/description/)

## Результаты
Разработанная модель достигла средней абсолютной ошибки MAE 11,4 на валидационной выборке, что свидетельствует о том, что модель способна обучаться и имеет потенциал. По сравнению с результатами предобученной модели ResNet-34, обученной на большом наборе данных ImageNet, а потом дообученной на наших данных, было выявлено большое пространство для улучшений 😅.

## Вывод
Лично для меня проект является значительным шагом вперед в понимании и применении сложных архитектур нейросетей, таких как ResNet. Я понял, что могу создать и обучить такую модель с нуля, и эта работа создает основу для дальнейшего улучшения и развития.
