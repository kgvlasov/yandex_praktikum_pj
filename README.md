# Учебные проекты Яндекс.Практикум специальности "Аналитик данных"

На текущий момент выполнено 9 проектов. Ниже представлена таблица с описанием проектов - задачи, выполненные работы и используемые технологии.

| Название проекта | Задачи | Выполненные работы | Используемые библиотеки |
| :--- | :--- | :--- | :--- |
| [Исследование надёжности заёмщиков](borrowers_research_project) | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количестводетей клиента на факт возврата кредита в срок | На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца и категоризированны данные. | *Pandas* |
| [Продажа квартир в Санкт-Петербурге](real_estate_market_analysis) | Используя данные Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | *Pandas*, *Matplotlib*|
| [Определение выгодного тарифа для телеком компании](telecom_profitable_tariff_determenation) | На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. | *Pandas*, *Matplotlib*, *NumPy*, *SciPy*|
| [Изучение закономерностей, определяющих успешность игр](game_market_success_analysis) | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок. | *Pandas*, *Matplotlib*, *NumPy*|
| [Исследование данных авиакомпании](airline_data_analysis) | Произвести выгрузки и подготовку данных авиакомпаний с помощью SQL, провести анализ запросов | Проведена выгрузка и подготовка предоставленных данных авиакомпании средствами SQL. Проверена гипотеза о различии среднего спроса на билеты во время проведения различных фестивалей и в обычное время . | *SQL*, *Pandas*, *Matplotlib*|
| [Оптимизация маркетинговых затрат в сервисе по продаже билетов](marketing_costs_optimization) | На основе данных о посещениях сайта Яндекс.Афиша изучить, как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, когда он окупается| Проведен анализ данных от Яндекс.Афиши целью оптимизации маркетинговых затрат. Рассчитаны метрики LTV, CAC, Retention rate, DAU, WAU, MAU, ROMI | *Pandas*, *Matplotlib*, *Seaborn*, *NumPy*,*SciPy*|
| [Проверка гипотез по увеличению выручки в интернет-магазине — оценка результатов A/B теста](internet_market_hypotesis_check)  | Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста. | *Pandas*, *Matplotlib*, *SciPy*|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](catering_market_analysis) | Исследование рынка общественного питания на основе открытых данных, подготовка презентации для инвесторов | Рекомендуется обратить внимание на открытие кафе, с числом посадочных мест около 30-40. Благоприятным расположенем для заведения может стать Пресненский район, т.к. это элитный район, в котором находятся крупные деловые комплексы, жители и гости которого могут быть нашими потенциальными клиентами. | *Pandas*, *Seaborn*, *Plotly* |
| [Анализ пользовательского поведения в мобильном приложении](mobile_app_user_behavior_analysis) | На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования по внедрению нового шрифта | Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовали библиотеки seaborn и plotly. Также мне потребовалось получить район расположения кафе-конкурентов. Эту задачу я решил с помощью данных из открытых источников | *Pandas*, *NumPy*, *SciPy*, *Matplotlyb*, *Seaborn*, *Plotly* |
