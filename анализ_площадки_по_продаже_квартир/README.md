<h1> Описание проекта </h1>


В вашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — провести исследовательский анализ данных, который поможет установить параметры, влияющие на цену объектов. Это позволит 

построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта и других объектов — эти данные автоматически получены из геосервисов. Количество парков и водоёмов также заполняется без участия пользователя. 

<h2> Задачи проекта </h2>

Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир

<h2> Сферы деятельности проекта </h2>

 - Интернет-сервисы 
 - Площадки объявлений


<h3> Направление деятельности </h3>

- Data Analyst
- Fraud-аналитик
- Маркетинг-аналитик

<h3> Навыки и инстурменты </h3>

- Matplotlib
- Pandas
- Python
- визуализация данных 
- исследовательский анализ данных
- предобработка данных





**Описание данных**


   - airports_nearest — расстояние до ближайшего аэропорта в метрах (м)
   - balcony — число балконов
   - ceiling_height — высота потолков (м)
   - cityCenters_nearest — расстояние до центра города (м)
   - days_exposition — сколько дней было размещено объявление (от публикации до снятия)
   - first_day_exposition — дата публикации
   - floor — этаж
   - floors_total — всего этажей в доме
   - is_apartment — апартаменты (булев тип)
   - kitchen_area — площадь кухни в квадратных метрах (м²)
   - last_price — цена на момент снятия с публикации
   - living_area — жилая площадь в квадратных метрах (м²)
   - locality_name — название населённого пункта
   - open_plan — свободная планировка (булев тип)
   - parks_around3000 — число парков в радиусе 3 км
   - parks_nearest — расстояние до ближайшего парка (м)
   - ponds_around3000 — число водоёмов в радиусе 3 км
   - ponds_nearest — расстояние до ближайшего водоёма (м)
   - rooms — число комнат
   - studio — квартира-студия (булев тип)
   - total_area — общая площадь квартиры в квадратных метрах (м²)
   - total_images — число фотографий квартиры в объявлении

   
**Итоговый вывод**

Изначальные проблемы датасета и способы их исправить:

- При обработке пропусков отдавался приоритет в их заполнение, а не удаление
- Были исправелны типы данных для экономии места и возможности проводить с ними требуемые операции
- Созданы дополнительные столбцы для лучшего понимания данных в таблице и возможнотси предоставить более глубокий анализ

Что касается ответа на главный вопрос задачи

- Основным ориентиром для определения стоимости квартиры - это стоимость квадратного метра.
Понимание особенностей различных факторов поможет определить, какие типы квартир наиболее востребованы. Например, общая площадь, доля жилой площади от общей и доля кухонной площади от общей могут указать на предпочтения покупателей. Также, анализ данных о датах продаж позволит определить оптимальный момент для запуска рекламных компаний, учитывая месяцы или дни недели, когда спрос на недвижимость наиболее активен.

Информация о этаже квартиры также играет важную роль. Например, первые этажи редко пользуются популярностью из-за вопросов безопасности, а последние этажи могут вызвать беспокойство из-за потенциальных проблем с крышей. Следовательно, наибольший интерес чаще всего проявляется к комфортным квартирам, расположенным между первым и последним этажом.

Важным аспектом является также местоположение. Например, пригороды Санкт-Петербурга могут иметь более низкие цены из-за отсутствия статуса и престижности, в то время как недвижимость в центре города, обычно имеет более высокие цены благодаря удобному расположению и качественной планировке квартир.