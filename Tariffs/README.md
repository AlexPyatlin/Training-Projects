# Comparison of mobile tariffs

## Описание проекта

Компания (федеральный оператор сотовой связи) предлагает клиентам два тарифных плана: "Смарт" и "Ультра". В целях корректировки рекламного бюджета маркетинговый департамент хочет выбрать наиболее прибыльный тариф. В распоряжении есть выборка из 500 клиентов за 2018 год: статистика звонков, интернет трафике, отправленных сообщениях и данные клиентов.

Описание тарифов:

*Тариф «Смарт»*:
1. Ежемесячная плата: 550 рублей
2. Включено 500 минут разговора, 50 сообщений и 15 Гб интернет-трафика
3. Стоимость услуг сверх тарифного пакета:
    - минута разговора: 3 рубля
    - сообщение: 3 рубля
    - 1 Гб интернет-трафика: 200 рублей

*Тариф «Ультра»*:
1. Ежемесячная плата: 1950 рублей
2. Включено 3000 минут разговора, 1000 сообщений и 30 Гб интернет-трафика
3. Стоимость услуг сверх тарифного пакета:
    - минута разговора: 1 рубль
    - сообщение: 1 рубль
    - 1 Гб интернет-трафика: 150 рублей

## Цель исследования
Проанализировать поведение клиентов и выбрать наиболее прибыльный тариф.

## Итоговый вывод 
1. В ходе анализа обнаружены следующие проблемы:
    - 8 абонентов в выборке не совершали звонки;
    - 74 абонента не отправляли СМС;
    - 3 абонента не пользовались интернетом;
    - У 494 пользователей были сессии с нулевым объемом трафика.

2. В среднем в течение года пользователи тарифа "Ультра" больше разговаривают, отправляют смс и пользуются интернетом.

3. Вероятнее всего, средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются. При этом, средняя выручка пользователей из Москвы, скорее всего, не отличается от других регионов. 

4. Несмотря на то, что за рассматриваемый период тариф "Ультра" приносит больше выручки, выручка по тарифу "Смарт" растет более быстрыми темпами. **Маркетинговому департаменту целесообразно сосредоточиться на тарифе "Смарт" в целях дальнейшего стимулирования роста.**

## Используемые библиотеки
*pandas, matplotlib, seaborn, numpy, scipy*
