# Sprut.Hub

![Hub](https://github.com/sprut/Hub/blob/master/Hub.jpg)
---

С первоначальной концепцией хаба можно ознакомиться в ролике 2017 года [SprutHub](https://www.youtube.com/watch?v=svo1-UbmbRk).
Скоро будет полное и подробное описание. Сейчас проходит второй этап тестирования, чтобы оставить предложение или описать ошибку переходим [сюда](https://github.com/sprut/Hub/issues/new/choose). Так выглядит [хаб в реальности](https://www.instagram.com/p/BzIOoU1CTsV/).

Последние новости о проекте всегда можно узнать в [instagram](https://www.instagram.com/sprut666666/).

Чат для обсуждения продукта в [telegram](https://t.me/SprutAI_SprutHub).

Последние новости о проекте [telegram](https://t.me/SprutHub).

Пример работы от наших партнёров: [Умный дом под ключ с поддержкой Apple HomeKit, Google Home, Яндекс Алиса на SprutHub](https://www.instagram.com/p/ByKxr7aDJfK/)

---
### Поддерживаемые голосовые ассистенты

[Пример одновременной работы с Apple Homekit, Google Home, Yandex Home](https://www.instagram.com/p/ByKxr7aDJfK/)

#### Apple HomeKit
- [HomeKit - что это такое? Умный дом от Apple](https://sprut.ai/client/article/1039)
- [Пример работы](https://www.instagram.com/p/Bq2W1SmjkvP/)
- Для спаривания с HomeKit используйте код:

![Image of paircode](https://github.com/sprut/Hub/blob/master/code.png)

#### Google Home
- [Google Умный дом](https://sprut.ai/client/article/1287)
- [Пример работы](https://www.instagram.com/p/BxxWAbTFeus/)
- Навык в процессе модерации

#### Yandex Home
- [Яндекс Умный дом](https://sprut.ai/client/article/1459)
- [Пример работы](https://www.instagram.com/p/ByDk-7vDC-k/)
- Для использования воспользуйтесь навыком [Sprut.Hub](https://dialogs.yandex.ru/store/skills/7a384ba0-sprut-hub-test)

---

### Приоритет разработки

#### WirenBoard
- [Все модули компании](https://wirenboard.com/ru/catalog/) (Промокод на скидку: "SprutHub" -10%)
- [В 2-х словах о продукте](https://www.instagram.com/p/But_GCjADzl/)

#### RazumDom
- [DDM845R v3](https://razumdom.ru/catalog/modbus_rtu/dimmery_rtu_rs485/507/) (Промокод на скидку: "71" -20%)
- [Пример работы](https://www.instagram.com/p/BvU9JogASqU/)
- При необходимости будет реализовано всё остальное оборудование

#### ZigBee
- [WBE2R-R-ZIGBEE](https://wirenboard.com/ru/product/WBE2R-R-ZIGBEE/) (Промокод на скидку: "SprutHub" -10%)
- [CC2531](https://sprut.ai/client/projects/105)
- [Deconz](https://sprut.ai/client/article/338)
- [Пример работы](https://www.instagram.com/p/BvwBU62hB80/)

#### Z-wave
- [DEFARO UZB7](https://z-wave.ru/shop/category/kontrollery/defaro-uzb7.html) (Промокод на скидку: "SprutHub" -15%)

---

### Применение
- Интеграторами уже начато тестирование на [реальных объектах](https://www.instagram.com/p/Bx7B8K2DMpd/)
- Так же отличный пример самостоятельной [организации системы](https://sprut.ai/client/blog/655) 

---

### Так же в работе

#### Запуск на специфичном железе
- [Пример работы на роутере Asus](https://www.instagram.com/p/BuUCltfABWl/) 

#### Интеграция хабов сторонних производителей
- Fibaro HC2
- Vera
- Homey 1.5
- [Xiaomi Hub](https://www.instagram.com/p/BrxrKb5j5zA/)

#### Z-wave
- Все стики на стандартном SDK

#### Delumo
- [Устройства на новом протоколе на 868](https://sprut.ai/client/news/245)
- [Пример работы](https://www.instagram.com/p/Bsy-HCWnPf2/)

---

### Вводные статьи по настройке Wiren Board
- [Wiren Board и с чем его едят. Краткий обзор.](https://sprut.ai/client/article/821)
- [Wiren Board. Настройка сети WiFi.](https://sprut.ai/client/article/875)
- [Wiren Board. Подключение I2C модулей.](https://sprut.ai/client/article/916)
- [Wiren Board. Подключение Modbus (RS-485) модулей.](https://sprut.ai/client/article/968)

[Первые эмоции от Wiren Board](https://youtu.be/keUKt7OPDWA)

### История изменений:

#### 1.2.1
- Большая оптимизаци работы хаба, теперь потребление CPU минимально
- Первый шаг к сохранению сетей ZigBee и бесшовного перехода между стиками

#### 1.2.0
- Добавлена поддержка 1-ware датчиков
- Исправлена работа switchOffTime
- Оптимизация и улучшение работы ZigBee и Z-wave
- Исправление получение яркости в датчиках ZigBee
- Добавлена поддержка определение заряда батареек в ZigBee
- Добавлены или исправлены устройства: TRADFRI transformer 10w, TRADFRI transformer 30w, TRADFRI Driver 30w, lumi.plug, lumi.remote.b186acn01, lumi.remote.b1acn01, lumi.remote.b286acn01, lumi.sensor_86sw1, lumi.sensor_86sw1lu, lumi.sensor_86sw2, lumi.sensor_86sw2Un, lumi.sensor_86sw2.es1, lumi.sensor_magnet.aq2, lumi.sensor_cube, TRADFRI bulb GU10 W 400lm, TRADFRI_wireless_dimmer, wb-mrm2-mini
- Приведение тимплейтов к единому виду, скоро вы узнаете зачем
- Добавлена поддержка ламп с температурой
- Исправления для диммера ddm845r от razumdom
- Большое обновление в стабильности и скорости работы HomeKit
- Испраление в HomeKit при массовой работе с устройствами
- Обнаружение устройств которые живут в сети, не пугайтесь в логах надписи "Service Found"
- Исправлено сохранение в базу, некоторые параметры могли некорректно восстанавливаться
- Исправлено изменение типа на розетку и обратно
- Оптимизация в работе Google Home
- Автообновление характеристик в веб интерфейсе
- Упрощение процедуры обновления
- Дополнительная оптимизация и увеличение скорости работы

#### 1.1.2
- Увеличена стабильность и скорость zigbee
- Добавлена поддержка zigbee устройств: lumi.vibration.aq1, lumi.sensor_wleak.aq1,lumi.sensor_smoke, lumi.sensor_natgas, lumi.remote.b286acn01, lumi.remote.b186acn01, lumi.remote.b1acn01, lumi.light.aqcn02, lumi.ctrl_86plug, TRADFRI bulb GU10 W 400lm, TRADFRI bulb E27 WS opal 980lm
- Пытались найти максимальный лимит устройств у WBE2R-R-ZIGBEE, после 36 подключенных устройств, устройств больше не осталось... поиски продолжаются
- К типу выключатель или switch, добавлен параметр switchOffTime для возможности реализации примитивной логики для гаражных ворот для имитации работы кнопки.
- Незначительные улучшения и исправления

#### 1.1.1
- Увеличена стабильность при сетевых проблемах, перезагрузках роутера и т.д.
- В "настройках" - "адрес интерфейса", вписываем "localhost", ручное указание интерфейса теперь не требуется.
- У датчиков движения появились настройки таймаутов + начала срабатывания у датчика WB
- Добавлена поддержка снятых с производства устройств Wiren Board 
- Небольшие правки и оптимизация

#### 1.1.0
- При добавлении в HomeKit перед назваванием аксессуара добавляется название комнаты, люди с iOS 13 поймут
- Включена тестовая поддержка deCONZ, для этого в настройках указываем deCONZ - 1, если сс2530 или сс2531 - 0
- Добавлено 10+ тимплейтов на z-wave, теперь 1413 + небольшие фиксы
- Восстановлена полноценная работа штор и окон
- Много внутренних изменений
