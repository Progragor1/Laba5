# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе №5 выполнил:
- Султанов Егор Альбертович
- РИ-210948

Отметка о выполнении заданий:

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## Цель работы: изучить особенности обучения модели и проанализировать параметры обучения.


## Задание 1 - Изменить параметры файла .yaml-агента и определить какие параметры и как влияют на обучение модели.
## Результат обучения:
### 1) С начальными данными:
![i2yL1EBxHFg](https://user-images.githubusercontent.com/91984484/204602894-8894c9ee-69a9-4c8f-95d8-f3d45141922b.jpg)

![fEtTPDRHPng](https://user-images.githubusercontent.com/91984484/204485460-65461c60-22f9-4da3-bf3d-5ed27fde776c.jpg)
![m_IvMgu6VjQ](https://user-images.githubusercontent.com/91984484/204485526-9f42f6f2-9464-4a06-8580-00e1efe22f0c.jpg)
### 2) При изменении параметра strength:
![wfQ3_IW0Xj8](https://user-images.githubusercontent.com/91984484/204602099-aa5bc3e1-5b45-4f82-acb4-6b6f9461d105.jpg)
![ocNPiS542U4](https://user-images.githubusercontent.com/91984484/204485797-145d14fc-eeac-406d-b391-58fcf49b3e81.jpg)
![v7XNuLIo1tI](https://user-images.githubusercontent.com/91984484/204485855-ce69e974-51c4-4ddc-8785-a99b04be20a4.jpg)
### 3) При изменении начальной скорости обучения - параметра learning_rate:
![NsAo45pzF1g](https://user-images.githubusercontent.com/91984484/204486045-939b4de9-2318-4017-9bfa-068cafea0999.jpg)
![z9-o_Gai-vk](https://user-images.githubusercontent.com/91984484/204486116-c00521d4-0e99-44e7-bbd8-c5096d478f06.jpg)
### 4) После изменения различных параметров
![69Mm4PbVIak](https://user-images.githubusercontent.com/91984484/204486269-747b7f33-e4c7-4e7d-b7bb-3100f7070265.jpg)
![1F18Fhgp9XQ](https://user-images.githubusercontent.com/91984484/204486302-751e41e1-0437-4c69-8614-5d320b36d2c4.jpg)
## Задание 2 - Опишите результаты, введеные в TensorBoard.
 
### -Параметр strength влияет на потери и накопительное вознаграждение и на все скаляры Policy
### -Изменение параметра learning_rate повлекло за собой изменение потерь полиса, но никак не повлияло на скаляры Policy
### -А при изменении различных параметров все скяляры поменялись
### Таким образом, мы поняли, что strangth влияет на RollerBall, а learning-rate на Economic.


## Выводы
### В результате работы:
#### - Научился работать с TenserBoard
#### - Понял, от чего зависит обучение модели
#### - Проанализировал параметры файла configuration.yaml
#### - Описал результаты работы


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
