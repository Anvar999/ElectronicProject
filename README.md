
# Автоматическая мусорка. Перерождение
* [Описание проекта](#chapter-0)
* [Папки проекта](#chapter-1)
* [Схемы подключения](#chapter-2)
* [Материалы и компоненты](#chapter-3)
* [Настройка и использование](#chapter-4)
* [FAQ](#chapter-5)
* [Полезная информация](#chapter-6)


<a id="chapter-0"></a>


<a id="chapter-1"></a>
## Папки
- **Low-Power** - библиотека сна, скопировать в  
`C:\Program Files (x86)\Arduino\libraries\` (Windows x64)  
`C:\Program Files\Arduino\libraries\` (Windows x86)
- **auto_trashcan2** - прошивка для Arduino, файлы в папках открыть в Arduino IDE (читай [FAQ](#chapter-5))
- **XODtrashcan** - прошивка для Arduino, упрощённая версия для [XOD](https://goo.gl/teWUBm) из видео

<a id="chapter-2"></a>
## Схема обычной версии
![СХЕМА](https://github.com/AlexGyver/automaticTrashcan_v2/blob/master/scheme1.jpg)

## Схема с мосфетом (максимальное энергосбережение)
![СХЕМА](https://github.com/AlexGyver/automaticTrashcan_v2/blob/master/scheme2.jpg)

<a id="chapter-3"></a>
## Материалы и компоненты
* Arduino NANO http://ali.ski/POpMO
* Датчик расстояния http://ali.ski/BOSn_x
* Серво http://ali.ski/N8P0y
* Батарейный отсек http://ali.ski/D4tPxC
* Корпус http://ali.ski/GpYU7U

РАССЫПУХА
* МОСФЕТ 
  + IRF3704ZPBF
  + IRLB8743PBF
  + IRL2203NPBF
  + IRLB8748PBF
  + IRL8113PBF
  + IRL3803PBF
  + IRLB3813PBF
  + IRL3502PBF
  + IRL2505PBF
  + IRF3711PBF
  + IRL3713PBF
  + IRF3709ZPBF
  + AUIRL3705N
  + IRLB3034PBF
  + IRF3711ZPBF
* Резистор 100 Ом
* Резистор 10 кОм
* ЖЕЛАТЕЛЬНО конденсатор электролитический 10V 470-1000 мкФ


## Вам скорее всего пригодится
* [Всё для пайки (паяльники и примочки)](http://alexgyver.ru/all-for-soldering/)
* [Недорогие инструменты](http://alexgyver.ru/my_instruments/)
* [Все существующие модули и сенсоры Arduino](http://alexgyver.ru/arduino_shop/)
* [Электронные компоненты](http://alexgyver.ru/electronics/)
* [Аккумуляторы и зарядные модули](http://alexgyver.ru/18650/)

<a id="chapter-4"></a>
## Настройка и использование
* [Загрузка прошивки](http://alexgyver.ru/arduino-first/) - ультра подробная статья по началу работы с Ардуино

## Настройки в коде


<a id="chapter-5"></a>

