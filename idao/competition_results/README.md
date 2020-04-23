# Некоторые результаты и анализ IDAO 

директории

* data – данные (скачать [тут](https://yadi.sk/d/1YjsfyXdAc6c1g))
   * данные с IDAO
   * данные, где зафиксированны все параметры КО, а коэффециент светового давления (КСД) и радиус перигея (РП) изменяется по сетке
* solutions – несколько лучших решений участников IDAO
* submission – прогнозы полученные с помощью алгоритмов участников  (скачать [тут](https://yadi.sk/d/xTfkF0KaWXx43w))

ноутбуки

* results_on_idao_data.ipynb – анализ результатов на данных IDAO 
    
    \+ сравнение с линейной регрессией 
    
    \+ сравнение с подходом, где предсказания SGP4 в test датасете обновляются на последней известной координате (перезапускается прогноз SGP4 и в качестве референсной точки использовается последняя точка в train датасете)

* results_on_LPC_RP_data.ipynb – анализ результатов на данных, где зафиксированны все параметры КО, а коэффециент светового давления (КСД) и радиус перигея (РП) изменяются по сетке 

    \+ сравнение с линейной регрессией 

    \+ сравнение с подходом, где предсказания SGP4 в test датасете обновляются на последней известной координате (перезапускается прогноз SGP4 и в качестве референсной точки использовается последняя точка в train датасете)