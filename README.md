# Data Science

В этом репозитории собраны мои проекты из курса "Специалист по Data Science".

Название проекта | Задача | Используемые библиотеки
--- | --- | ---
[01_Музыка_Предпочтение_жанров_Москва_Петербург](https://github.com/NistratovR/yap/tree/main/01_%D0%9C%D1%83%D0%B7%D1%8B%D0%BA%D0%B0_%D0%9F%D1%80%D0%B5%D0%B4%D0%BF%D0%BE%D1%87%D1%82%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B6%D0%B0%D0%BD%D1%80%D0%BE%D0%B2_%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D0%B0_%D0%9F%D0%B5%D1%82%D0%B5%D1%80%D0%B1%D1%83%D1%80%D0%B3) | Проверить три гипотезы:
_1._ Активность пользователей зависит от дня недели.
_2._ В понедельник утром в Москве преобладают одни жанры, а в Петербурге — другие.
_3._ Москва и Петербург предпочитают разные жанры музыки. | python, pandas
[02_Исследование_надёжности_заёмщиков](https://github.com/NistratovR/yap/tree/main/02_%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%BD%D0%B0%D0%B4%D1%91%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8_%D0%B7%D0%B0%D1%91%D0%BC%D1%89%D0%B8%D0%BA%D0%BE%D0%B2) | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок. | python, pandas
[03_Определение_стоимости_квартир](https://github.com/NistratovR/yap/tree/main/03_%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8_%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80) | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир. | pandas, seaborn, matplotlib
[04_Какой_тариф_приносит_больше_денег](https://github.com/NistratovR/yap/tree/main/04_%D0%9A%D0%B0%D0%BA%D0%BE%D0%B9_%D1%82%D0%B0%D1%80%D0%B8%D1%84_%D0%BF%D1%80%D0%B8%D0%BD%D0%BE%D1%81%D0%B8%D1%82_%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B5_%D0%B4%D0%B5%D0%BD%D0%B5%D0%B3) | Клиентам предлагают два тарифных плана. 
Чтобы скорректировать рекламный бюджет нужно определить, какой тариф приносит больше денег. | pandas, numpy, scipy, matplotlib, plotly
[05_Закономерности_успешности_игр](https://github.com/NistratovR/yap/tree/main/05_%D0%97%D0%B0%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%BD%D0%BE%D1%81%D1%82%D0%B8_%D1%83%D1%81%D0%BF%D0%B5%D1%88%D0%BD%D0%BE%D1%81%D1%82%D0%B8_%D0%B8%D0%B3%D1%80) | Выявить определяющие успешность игры закономерности. 
Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. | pandas, numpy, scipy, matplotlib, plotly
[06_Подбор_тарифа_для_рекомендации](https://github.com/NistratovR/yap/tree/main/06_%D0%9F%D0%BE%D0%B4%D0%B1%D0%BE%D1%80_%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%B0_%D0%B4%D0%BB%D1%8F_%D1%80%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B8) | На основе данных построить модель, которая выберет подходящий тариф. | pandas, sklearn
[07_Прогноз_ухода_клиентов](https://github.com/NistratovR/yap/tree/main/07_%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7_%D1%83%D1%85%D0%BE%D0%B4%D0%B0_%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2) | На основе данных из банка определить клиента, который может уйти. | pandas, numpy, sklearn, matplotlib
[08_Выбор_локации_для_скважины](https://github.com/NistratovR/yap/tree/main/08_%D0%92%D1%8B%D0%B1%D0%BE%D1%80_%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B8_%D0%B4%D0%BB%D1%8F_%D1%81%D0%BA%D0%B2%D0%B0%D0%B6%D0%B8%D0%BD%D1%8B) | На основе данных геологи разведки выбрать район добычи нефти. | pandas, numpy, sklearn, matplotlib, math
[09_Предсказать_коэффициент_восстановления_золота_из_руды](https://github.com/NistratovR/yap/tree/main/09_%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D1%8C_%D0%BA%D0%BE%D1%8D%D1%84%D1%84%D0%B8%D1%86%D0%B8%D0%B5%D0%BD%D1%82_%D0%B2%D0%BE%D1%81%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%B7%D0%BE%D0%BB%D0%BE%D1%82%D0%B0_%D0%B8%D0%B7_%D1%80%D1%83%D0%B4%D1%8B) | Спрогнозировать концентрацию золота при проведении процесса очистки золота. | pandas, numpy, sklearn, matplotlib, plotly
[10_Защита_персональных_данных_клиентов](https://github.com/NistratovR/yap/tree/main/10_%D0%97%D0%B0%D1%89%D0%B8%D1%82%D0%B0_%D0%BF%D0%B5%D1%80%D1%81%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D1%85_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85_%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2) | Разработать метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. | pandas, numpy, sklearn
[11_Определение_стоимости_автомобилей](https://github.com/NistratovR/yap/tree/main/11_%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8_%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D0%B5%D0%B9) | Разработать систему рекомендации стоимости автомобиля на основе его описания. | pandas, numpy, sklearn, matplotlib, catboost, lightgbm
[12_Прогнозирование_заказов_такси_на_следующий_час](https://github.com/NistratovR/yap/tree/main/12_%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2_%D1%82%D0%B0%D0%BA%D1%81%D0%B8_%D0%BD%D0%B0_%D1%81%D0%BB%D0%B5%D0%B4%D1%83%D1%8E%D1%89%D0%B8%D0%B9_%D1%87%D0%B0%D1%81) | Разработать систему предсказания количество заказов такси на следующий час. | pandas, numpy, sklearn, catboost, matplotlib
[13_Определение_токсичности_комментариев](https://github.com/NistratovR/yap/tree/main/13_%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D1%82%D0%BE%D0%BA%D1%81%D0%B8%D1%87%D0%BD%D0%BE%D1%81%D1%82%D0%B8_%D0%BA%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B5%D0%B2) | Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. | pandas, numpy, matplotlib, sklearn, catboost, lightgbm






