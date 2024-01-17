# yandex_practicum

Здесь собраны некоторые реализованные проекты

| № |	Наименование проекта	| Описание	| Навыки и инструменты | Выводы |
| - | --- | --- | --- |
| 1 | [Определение факторов успешности компьютерных игр](https://github.com/yulia-alexeychuk/projects/tree/main/project_games_success) | Изучение закономерностей, определяющих успешность игр на основе исторических данных о продажах игр из открытых источников, где содержатся информация об оценках пользователей и экспертов, жанрах и платформах. Построены графики по годам, платформам, жанрам, составлен ТОП-5 по платформам и жанрам для каждого региона, проанализировано влияние возрастного рейтинга на продажи, проверены две гипотезы. | pandas, matplotlib, scipy, numpy, критерий Стьюдента | Выявлены следующие параметры, определяющие успешность игр: платформы - PS4 и XOne; жанры - Action, Shooter и Role-Playing; возрастной рейтинг - «Для взрослых» и «Для всех»; регионы - Северная Америка и Европа. |
| 2 | [Приоритизация гипотез и анализ A/B-теста](https://github.com/yulia-alexeychuk/projects/tree/main/project_business) | В первой части проведена приоритизация гипотез по фреймворкам ICE и RICE. Во второй части проведен анализ результатов A/B-теста: построены графики кумулятивной выручки, среднего чека, конверсии по группам, посчитана статистическая значимость различий конверсий и средних чеков по сырым и очищенным данным. | pandas, matplotlib, scipy, numpy, критерий Шапиро-Уилка, критерий Манна-Уитни, A/B-тест, RICE, ICE | В первую очередь стоит обратить внимание на гипотезу — `Добавить форму подписки на все основные страницы, чтобы собрать базу клиентов для email-рассылок`. По итогам анализа результаты группы B значительно превосходят группу A. |
