## Учебный проект "Когортный анализ бизнес-показателей онлайн-сервиса Афиши"
[Открыть проект в nbviewer](https://nbviewer.org/github/Emiranunuka/Yandex_Practicum_Data_Analyst_Training_Projects_Rus/blob/main/cohorts_metrics_rus/avdonina_cohorts_metrics_rus.ipynb)
### Задачи
Анализ данных маркетинговой аналитики онлайн-сервиса Афиши за 12 месяцев с целью определить как клиенты пользуются сервисом, когда делают первые покупки на сайте, сколько денег 
приносит компании каждый клиент, когда расходы на привлечение клиента окупаются, чтобы помочь маркетологам снизить расходы — отказаться от невыгодных источников трафика и 
перераспределить бюджет.
### Заказчик
Отдел маркетинга.
### Стек
Python, pandas, numpy, matplotlib, seaborn, plotly express, graph_objects.
### Анализ
EDA и предобработка (тип данных, регистр, ошибки). Группировки, срезы, слияния, расчет показателей. Когортный анализ средних и кумулятивных метрик. Визуализация данных: графики, круговые диаграммы, тепловые карты.
- Продуктовые метрики: число уникальных пользователей (DAU, WAU, MAU), cреднее число сеансов одного пользователя в день, средняя продолжительность пользовательской сессии (ASL),
численность когорт по месяцам (число вновь привлеченных уникальных пользователей за период), коэффициент удержания (Retention Rate) по когортам по месяцам и средний коэффициент 
удержания на второй месяц "жизни" когорт. 
- Метрики электронной коммерции: среднее время от первого визита до покупки, валовая прибыль с покупателя, «пожизненная» ценность клиента (LTV) по месяцам "возраста" каждой 
когорты и средний LTV за 6 месяцев, среднее число покупок на покупателя в разные месяцы его "жизни", средний чек по месяцам совершения покупки. 
- Маркетинговые метрики: сумма расходов на маркетинг по источникам трафика, по месяцам; стоимость привлечения клиента (CAC) по каждому источнику трафика в динамике по месяцам и 
средняя CAC по выборке; число покупок с платных источников и средние маркетинговые затраты на один заказ; средняя по месяцам окупаемость инвестиций в маркетинг (ROMI) и ROMI в 
разрезе источников трафика по месяцам "возраста" когорт.
### Результаты
* Выделили перспективные когорты клиентов.
* Рассчитали и оценили продуктовые метрики, метрики электронной коммерции, маркетинговые метрики.
* Оценили результативность продвижения сервиса по источникам трафика и их перспективность, подготовили рекомендации по каждому источнику трафика.
### Статус проекта
+ Завершен.
