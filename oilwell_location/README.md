# location_oilwell

## Выбор локации для скважины

**Статус проекта:** закончен.

**Описание проекта:**  даны пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Необходимо с помощью модели машинного обучения определить регион, где добыча принесёт наибольшую прибыль. 

**Задачи проекта:** На основе данных геологической разведки выбрать наиболее прибыльный район добычи нефти.

**Ход исследования:**
 1. Подготовка данных.
 2. Обучение и проверка модели для каждого региона.
 3. Подготовка и расчёт прибыли.
 4. Расчет рисков.
 5. Выводы и рекомендации к выбору района добычи.

**Ключевые навыки:** визуализация данных, бутстреп.


**Используемые инструменты:** Python, Pandas, Scikit-learn.

**Итоги исследования:**
1. Самый перспективный регион №2, на мой взгляд, так как имеет самые лучшие показатели:
  - Средняя прибыль с 200 самых богатых скважин составляет 456.05 млн. рублей. Это хоть и не самый большой показатель, но вероятность его получить достаточно высокая.
  - 95%-й доверительный интервал находится между 33.82 и 852.29 млн. рублей. Получение убытков не прогнозируется.
  - Вероятность убытка в регионе самая низкая - 1.5%
