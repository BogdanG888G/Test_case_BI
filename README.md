# 📊 Тестовое задание на Data аналитика  

## 📝 Описание проекта  
Этот проект посвящен анализу взаимосвязи между рекламными ставками, объемами продаж, упущенной выручкой и ценовой политикой продавцов. Исследование основано на данных за 2024 год с прогнозом на 2025 год.

## 🔍 Основные выводы  

### 📈 Взаимосвязь рекламы и продаж  
- **CPM не всегда коррелирует с продажами** – высокая рекламная ставка не гарантирует высокий объем продаж.  
- **Наблюдаются значительные выбросы** – отдельные кампании или товары могут приносить неожиданные результаты.  
- **Тренды изменяются по периодам**, что может указывать на сезонность.  

### 💰 Лидеры по упущенной выручке  
- Некоторые продавцы **теряют миллионы рублей** – лидер списка недополучил более **377 млн руб.**  
- Возможные причины: **нехватка товара, неправильное ценообразование, проблемы с логистикой**.  
- В 2025 году пока **нулевые потери**, что может означать улучшение стратегий или нехватку данных.  

### 🏆 Продажи среди продавцов  
- **Распределение продаж неравномерное** – несколько крупных продавцов доминируют на рынке.  
- **Многие продавцы имеют всего 1-2 продажи**, что может указывать на низкую конкуренцию или узкую нишу.  
- **Продажи меняются по месяцам**, что говорит о сезонных изменениях спроса.  

### 💵 Средняя цена товаров  
- **Большой разброс цен** – у некоторых продавцов средняя цена превышает **5000 рублей**, но большинство товаров продаются дешевле.  
- **Изменения цен по месяцам** – возможно, связано с акциями, скидками или изменением спроса.  

### 🏷️ Цена со скидкой vs. количество продаж  
- **Большинство продаж – товары до 10 000 рублей**.  
- **Дорогие товары (50 000+) продаются редко**, но спрос на них присутствует.  
- **Сезонность влияет на спрос** – в разные периоды разные товары продаются лучше.  

### 🔮 Прогноз продаж на 2025  
- **Ожидается рост продаж** по сравнению с 2024 годом.  
- Причины: **улучшенные маркетинговые стратегии, растущий спрос, изменения в ассортименте**.  

## 📂 Описание файлов  
В проекте используются следующие файлы с данными:  

- **`весь 24 год.csv`** *(1618 КБ)* – содержит полные данные о продажах за весь 2024 год.  
- **`декабрь 24.csv`** *(1193 КБ)* – данные о продажах за декабрь 2024 года.  
- **`ноябрь 24.csv`** *(1151 КБ)* – данные о продажах за ноябрь 2024 года.  
- **`январь 25.csv`** *(1285 КБ)* – данные о продажах за январь 2025 года.  
- **`test_dataset_bi.ipynb`** *(48 КБ)* - скрипт на питоне, объединяющий данные в один общий датасет, а также создание ML-модели для предсказания проджа на 2025 год.

Каждый файл включает в себя информацию о рекламных ставках, объемах продаж, выручке, ценах и скидках, что позволяет анализировать динамику изменений по месяцам и строить прогнозы.  

## 📌 Возможные направления для улучшения  
✅ Оптимизация рекламных стратегий для повышения ROI.  
✅ Анализ причин упущенной выручки и разработка решений для минимизации потерь.  
✅ Поддержка слабых продавцов – обучение, корректировка ценовой политики.  
✅ Исследование влияния сезонности и адаптация стратегий продаж.  

## 🛠 Используемые технологии  
- 📊 **BI-инструменты** (Data Visualization)  
- 📈 **Аналитика данных**  
- 🏷️ **ML-прогнозирование**  
- 🐍 **Python** (pandas, scikit-learn)  

