<h1> Описание проекта </h1>


Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.
Описание данных

<h2> Задача проекта </h2>

На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок

<h2> Сфера деятельности проекта </h2>

- Банковская сфера
- Кредитование

<h3> Направление деятеьлности </h3>

- Data Analyst
- Финансовый аналитик

<h3> Навыки </h3>

- Pandas
- Python
- предобработка данных


**Описание данных**


   - children — количество детей в семье
   - days_employed — общий трудовой стаж в днях
   - dob_years — возраст клиента в годах
   - education — уровень образования клиента
   - education_id — идентификатор уровня образования
   - family_status — семейное положение
   - family_status_id — идентификатор семейного положения
   - gender — пол клиента
   - income_type — тип занятости
   - debt — имел ли задолженность по возврату кредитов
   - total_income — ежемесячный доход
   - purpose — цель получения кредита




**Итоговый вывод**



В итоговом выводе, я скажу, что считаю сравнение возможности погашения кредита по одному признаку не целесообразным - на примерах видно, что отличия в большинстве своем не сильные. Все они будут вырожаться в группе. 

Например если человек замужем, со средним доходом и без детей, берет кредит на квартиру, то у него судя по этой таблице больше вероятность погашения кредита в срок, чем у пары, с 2 детьми, находящимися в гражданском браке, которым нужен кредит на автомобиль. 

По этим примерам можно увидеть куда сколняется вероятность по отдельности, но делать вывод стоит в совокупности всех известных данных. 