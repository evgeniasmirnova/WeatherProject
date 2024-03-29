# Weather App Project
Клиент-серверное приложение на основе OpenWeatherMap API для отслеживания погоды.

## Содержание
- [Технологии](https://github.com/evgeniasmirnova/WeatherProject/tree/main?tab=readme-ov-file#содержание)
-  [Начало работы](https://github.com/evgeniasmirnova/WeatherProject/tree/main?tab=readme-ov-file#начало-работы)
-  [Возможности](https://github.com/evgeniasmirnova/WeatherProject/tree/main?tab=readme-ov-file#возможности)

## Технологии
- UIKit
- Alamofire
- SnapKit
- PinLayout
- GCD
- UserDefaults
- Architecture: VIPER

## Начало работы

Клонировать репозиторий в нужную папку с помощью команды:
```
git clone git@github.com:evgeniasmirnova/WeatherProject.git
```

## Возможности


### Главный экран
На данном экране присутствует список избранных городов (по умолчанию их четыре: Канны, Киото, Москва и Ярославль), в которых пользователь хочет отслеживать погоду, их локальное время и основная информация о состоянии погоды. 
Список сохраняется даже после перезапуска, сбрасывается только при удалении приложения. Предусмотрено удаление и добавление новых городов.

<img src="ReadMeAssets/mainScreen.png" width="187" height="406"/>

#### Добавление элемента на главный экран
По нажатию на кнопку плюс можно добавить новый город на главный экран. На экране выбора города можно воспользоваться поиском.

<img src="ReadMeAssets/addCity.gif" width="187" height="406"/>

#### Удаление элемента с главного экрана
В программе предусмотрено удаление города посредством свайпа ячейки.

<img src="ReadMeAssets/deleteCity.gif" width="187" height="406"/>

### Экран детальной информации о погоде 
Здесь отображена информация о погоде на 5 дней, ощущение температуры, скорость ветра, влажность, облачность. 
Для удобства название города и время в его часовом поясе закрепляется при скролле — так вы их не потеряете.

<img src="ReadMeAssets/detailScreen.gif" width="187" height="406"/> <img src="ReadMeAssets/santiagoDetail.png" width="187" height="406" hspace="20"/> <img src="ReadMeAssets/moscowDetail.png" width="187" height="406"/> 
