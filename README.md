## Специалист по Data Science

Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Специалист по Data Science".

## Содержание

1. [Музыка больших городов](#1-музыка-больших-городов)
2. [Исследование надежности заемщиков](#2-исследование-надежности-заемщиков)
3. [Исследование объявлений о продаже квартир](#3-исследование-объявлений-о-продаже-квартир)
4. [Статистический анализ данных](#4-статистический-анализ-данных)
5. [Анализ факторов успеха видеоигр](#5-анализ-факторов-успеха-видеоигр)
6. [Прогнозная модель «ЭкоФерма» для отбора буренок](#6-прогнозная-модель-экоферма-для-отбора-буренок)
7. [Персонализация предложений постоянным клиентам](#7-персонализация-предложений-постоянным-клиентам)
8. [Предсказание удовлетворенности сотрудников и их увольнения](#8-предсказание-удовлетворенности-сотрудников-и-их-увольнения)

## Обзор проектов

| № | Название проекта | Описание | Используемые библиотеки |
| :-: | :---------------------- | :---------------------- | :---------------------- |
| 1 | [Музыка больших городов](1_big_cities_music) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга по времени суток и дням недели. | `pandas` |
| 2 | [Исследование надежности заемщиков](2_analysis_of_bank_data) | Анализ банковских данных для выявления зависимостей между семейным положением, количеством детей, уровнем дохода и своевременным возвратом кредита. | `pandas`, `matplotlib` |
| 3 | [Исследование объявлений о продаже квартир](3_real_estate_analysis) | Определение рыночной стоимости недвижимости на основе данных Яндекс Недвижимость и построение системы для обнаружения аномалий и мошенничества. | `pandas`, `matplotlib` |
| 4 | [Статистический анализ данных](4_statistical_data_analysis) | Анализ данных о пользователях, их поездках и подписках для выявления ключевых тенденций и закономерностей. | `numpy`, `pandas`, `scipy`, `matplotlib` |
| 5 | [Анализ факторов успеха видеоигр](5_video_game_success_analysis) | Выявление факторов, определяющих успешность видеоигр, для прогнозирования их популярности и планирования рекламных кампаний. | `pandas`, `matplotlib`, `seaborn`, `numpy`, `scipy` |
| 6 | [Прогнозная модель «ЭкоФерма» для отбора буренок](6_eco_farm_model) | Разработка моделей для прогнозирования удоя коров и оценки качества молока для оптимизации закупок буренок. | `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`, `statsmodels` |
| 7 | [Персонализация предложений постоянным клиентам](7_customer_personalization) | Разработка решения для персонализации предложений клиентам интернет-магазина с целью увеличения их активности. | `pandas`, `numpy`, `shap`, `phik`, `sklearn`, `seaborn`, `matplotlib` |
| 8 | [Предсказание удовлетворенности сотрудников и их увольнения](8_employee_satisfaction_prediction) | Построение моделей для предсказания уровня удовлетворённости сотрудников и вероятности их увольнения. | `pandas`, `numpy`, `sklearn`, `seaborn`, `matplotlib`, `phik` |

## Детальное описание проектов

### 1. Музыка больших городов

**Описание проекта:**
Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени суток (утро и вечер) и дня недели (понедельник, среда, пятница).

**Используемые библиотеки:**
- `pandas`

### 2. Исследование надежности заемщиков

**Описание проекта:**
Проведение исследования банковских данных клиентов с целью выявления зависимостей между количеством детей и своевременным возвратом кредита, семейным положением и своевременным возвратом кредита, а также уровнем дохода и своевременным возвратом кредита.

**Используемые библиотеки:**
- `pandas`
- `matplotlib`

### 3. Исследование объявлений о продаже квартир

**Описание проекта:**
Анализ архивных данных Яндекс Недвижимость о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Цель проекта — определить рыночную стоимость объектов недвижимости посредством исследовательского анализа данных и установить параметры, влияющие на цену объектов. Также планируется построение автоматизированной системы для отслеживания аномалий и мошеннической деятельности.

**Описание данных:**
- **airports_nearest:** расстояние до ближайшего аэропорта (м)
- **balcony:** количество балконов
- **ceiling_height:** высота потолков (м)
- **cityCenters_nearest:** расстояние до центра города (м)
- **days_exposition:** количество дней размещения объявления
- **first_day_exposition:** дата публикации
- **floor:** этаж
- **floors_total:** всего этажей в доме
- **is_apartment:** апартаменты (булев тип)
- **kitchen_area:** площадь кухни (м²)
- **last_price:** цена на момент снятия с публикации
- **living_area:** жилая площадь (м²)
- **locality_name:** название населённого пункта
- **open_plan:** свободная планировка (булев тип)
- **parks_around3000:** количество парков в радиусе 3 км
- **parks_nearest:** расстояние до ближайшего парка (м)
- **ponds_around3000:** количество водоёмов в радиусе 3 км
- **ponds_nearest:** расстояние до ближайшего водоёма (м)
- **rooms:** количество комнат
- **studio:** квартира-студия (булев тип)
- **total_area:** общая площадь квартиры (м²)
- **total_images:** количество фотографий в объявлении

**Используемые библиотеки:**
- `pandas`
- `matplotlib`

### 4. Статистический анализ данных

**Описание проекта:**
Анализ данных о пользователях, их поездках и подписках для выявления ключевых тенденций и закономерностей.

**Описание данных:**
- **Пользователи (users_go.csv):**
  - `user_id`: уникальный идентификатор пользователя
  - `name`: имя пользователя
  - `age`: возраст
  - `city`: город
  - `subscription_type`: тип подписки (free, ultra)
- **Поездки (rides_go.csv):**
  - `user_id`: уникальный идентификатор пользователя
  - `distance`: расстояние, проеханное в текущей сессии (м)
  - `duration`: продолжительность сессии (мин)
  - `date`: дата поездки
- **Подписки (subscriptions_go.csv):**
  - `subscription_type`: тип подписки
  - `minute_price`: стоимость одной минуты поездки
  - `start_ride_price`: стоимость начала поездки
  - `subscription_fee`: ежемесячный платеж

**Используемые библиотеки:**
- `numpy`
- `pandas`
- `scipy`
- `matplotlib`

### 5. Анализ факторов успеха видеоигр

**Описание проекта:**
Выявление факторов, определяющих успешность видеоигр, для прогнозирования их популярности и планирования рекламных кампаний на 2017 год.

**Описание данных:**
- **Name:** название игры
- **Platform:** платформа
- **Year_of_Release:** год выпуска
- **Genre:** жанр игры
- **NA_sales:** продажи в Северной Америке (млн копий)
- **EU_sales:** продажи в Европе (млн копий)
- **JP_sales:** продажи в Японии (млн копий)
- **Other_sales:** продажи в других странах (млн копий)
- **Critic_Score:** оценка критиков (макс. 100)
- **User_Score:** оценка пользователей (макс. 10)
- **Rating:** рейтинг ESRB

**Используемые библиотеки:**
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `scipy`

### 6. Прогнозная модель «ЭкоФерма» для отбора буренок

**Описание проекта:**
Разработка двух моделей:
1. Прогнозирование возможного удоя коровы (целевой признак: Удой).
2. Расчет вероятности получения вкусного молока от коровы (целевой признак: Вкус молока).

**Описание данных:**
- **ferma_main.csv:**
  - `id`: уникальный идентификатор коровы
  - `Удой, кг`: масса молока в год
  - `ЭКЕ`: энергетическая кормовая единица
  - `Сырой протеин, г`: содержание протеина в корме
  - `СПО`: соотношение сахара к протеину в корме
  - `Порода`: порода коровы
  - `Тип пастбища`: тип пастбища
  - `порода папы_быка`: порода папы коровы
  - `Жирность,%`: содержание жиров в молоке
  - `Белок,%`: содержание белков в молоке
  - `Вкус молока`: оценка вкуса (бинарный)
  - `Возраст`: возраст коровы (бинарный)
- **ferma_dad.csv:**
  - `id`: уникальный идентификатор коровы
  - `Имя Папы`: имя папы коровы
- **cow_buy.csv:**
  - `Порода`: порода коровы
  - `Тип пастбища`: тип пастбища
  - `порода папы_быка`: порода папы коровы
  - `Имя_папы`: имя папы коровы
  - `Текущая_жирность,%`: содержание жиров в молоке
  - `Текущий_уровень_белок,%`: содержание белков в молоке
  - `Возраст`: возраст коровы (бинарный)

**Используемые библиотеки:**
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`
- `statsmodels`

### 7. Персонализация предложений постоянным клиентам

**Описание проекта:**
Разработка решения для интернет-магазина «В один клик» с целью персонализации предложений постоянным клиентам для повышения их активности.

**Описание данных:**
- **market_file.csv:** данные о поведении покупателя на сайте.
- **market_money.csv:** данные о выручке от каждого покупателя.
- **market_time.csv:** данные о времени, проведенном на сайте.
- **money.csv:** данные о среднемесячной прибыли от покупателя.

**Используемые библиотеки:**
- `pandas`
- `numpy`
- `shap`
- `phik`
- `sklearn`
- `seaborn`
- `matplotlib`

### 8. Предсказание удовлетворенности сотрудников и их увольнения

**Описание проекта:**
Построение двух моделей:
1. Предсказание уровня удовлетворённости сотрудника на основе данных.
2. Предсказание вероятности увольнения сотрудника из компании.

**Описание данных:**
- `id`: уникальный идентификатор сотрудника
- `dept`: отдел
- `level`: уровень должности
- `workload`: уровень загруженности
- `employment_years`: стаж работы в компании
- `last_year_promo`: было ли повышение за последний год
- `last_year_violations`: были ли нарушения трудового договора
- `supervisor_evaluation`: оценка работы сотрудника руководителем
- `salary`: ежемесячная зарплата
- `job_satisfaction_rate`: уровень удовлетворённости (целевой признак)

**Используемые библиотеки:**
- `pandas`
- `numpy`
- `sklearn`
- `seaborn`
- `matplotlib`
- `phik`

## Навыки

- Анализ данных: `pandas`, `numpy`
- Визуализация: `matplotlib`, `seaborn`
- Машинное обучение: `scikit-learn`, `statsmodels`
- Статистический анализ: `scipy`
- Моделирование и прогнозирование
- Работа с большими данными и их предобработка

## Контакты
