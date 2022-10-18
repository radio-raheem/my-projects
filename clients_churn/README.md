# Отток клиентов

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Мы располагаем историческими данными о поведении клиентов и расторжении договоров с банком. 

Наша задача — построить модель со значеним *F1*-меры не менее 0,59.

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

Основными этапами нашего проекта станут:  
* Подготовка данных
* Исследование задачи. Обучение разных моделей без учета дисбаланса
* Борьба с дисбалансом. Обучение разных моделей с учетом дисбаланса
* Тестирование модели
* Проверка модели на вменяемость
* Исследование метрики AUC-ROC

**Описание данных**  

**Признаки**

*RowNumber* — индекс строки в данных  
*CustomerId* — уникальный идентификатор клиента  
*Surname* — фамилия  
*CreditScore* — кредитный рейтинг  
*Geography* — страна проживания  
*Gender* — пол  
*Age* — возраст  
*Tenure* — сколько лет человек является клиентом банка  
*Balance* — баланс на счёте  
*NumOfProducts* — количество продуктов банка, используемых клиентом  
*HasCrCard* — наличие кредитной карты  
*IsActiveMember* — активность клиента  
*EstimatedSalary* — предполагаемая зарплата

**Целевой признак** 

**Exited** — факт ухода клиента


Проект выполнен в **Jupyter Notebook**, версия сервера блокнотов: 6.1.4. Версия **Python** 3.7.8.  
  
В проекте использованы библиотеки:
* **Pandas**
* **NumPy**
* **MatPlotLib**
* **scikit-learn** 
* **IPython** 



# Apartment sales ads research

Can we determine the market value of objects, having real estate ads for several previous years?  
Great news: yes we can!  
  
We have the data of the service for placing real estate ads — an archive of ads for the sale of apartments in a large Russian city and its suburbs for several years.  
We need to learn how to determine the market value of real estate and set key parameters. This will allow to build an automated system: it will track anomalies and fraudulent activity.  

Two types of data are available for each apartment. The first one is entered by the user, the second one is obtained automatically based on cartographic data. For example, the distance to the center, the airport, the nearest park and reservoir.

The main steps of our project will be:
* Examining the provided data
* Data preprocessing
* Calculations and adding results to the table
* Exploratory data analysis
* General conclusion

The project is made in **Jupyter Notebook**, Notebook server version: 6.1.4. **Python** 3.7.8.
The project uses the **Pandas**, **MatPlotLib** libraries and the **IPython** module.
