# Анализ оттока клиентов

## Данные

Описание данных

- USERID — идентификатор пользователя,
- score — баллы кредитного скоринга,
- city — город,
- gender — пол,
- age — возраст,
- equity — количество баллов собственности,
- balance — баланс на счёте,
- products — количество продуктов, которыми пользуется клиент,
- credit_card — есть ли кредитная карта,
- last_activity — активный клиент,
- EST_SALARY — заработная плата клиента,
- churn — ушёл или нет (1 - ушел, 0 - не ушел).

## Задача

Исследование состоит из нескольких пунктов - задач:

- знакомство с данными и предобработка - выявление и анализ дубликатов, пропусков и аномалий
- исследовательский анализ данных - поиск связи между столбцами-характеристиками клиентов банка и их уходом, анализ коореляции в данных
проверка гипотез
  - гипотеза различия дохода между теми клиентами, которые ушли и теми, которые остались
  - гипотеза, которая будет сформулирована на основе дальнейшего анализа
- на основе исследовательского анализа и проверенных гипотез формируем несколько сегментов наиболее отточных пользователей и приоритезируем сегменты
- формирование вывода и рекомендаций на основе проведенного анализа

## Используемые библиотеки

*pandas*, *matplotlib.pyplot*, *seaborn*, *scipy.stats*, *datetime*, *numpy*, *scipy.stats* (*levene*), *Tableau Public*, *PowerPoint Presentation*