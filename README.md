Портфоліо-проєкт: Аналіз результатів A/B-тестування / Portfolio Project: A/B Testing Results Analysis

🇬🇧 English Version

Portfolio Project: A/B Testing Results Analysis

This project is dedicated to analyzing A/B testing results using statistical methods in Python and creating an interactive visualization in Tableau to demonstrate key conversion metrics and their statistical significance.

Project Goal

    Automate the calculation of statistical significance for A/B test metrics using Python, making the process flexible and scalable.

    Demonstrate proficiency with statistical methods for conversion analysis.

    Create a unique and informative dashboard in Tableau to visualize the test results.

Project Stages

Stage 1. Calculating Statistical Significance in Python

At this stage, a Python script was developed in Google Colab to automate calculations, providing a more flexible solution compared to online calculators.

    Dataset: Data from the "Create Your A/B Testing Tool" assignment was used.

    Key Metrics for Analysis:

        add_payment_info / session

        add_shipping_info / session

        begin_checkout / session

        new_accounts / session

    Dynamic Calculation: The script is built with loops and arrays, which allows for the easy addition of new metrics and analysis across different segments (e.g., by country, device, test number).

    Stage Result: A final .csv file was generated, containing all calculated metrics, confidence intervals, and statistical significance indicators, ready for visualization.

Stage 2. Visualizing Results in Tableau

Based on the data from the first stage, an analytical dashboard was updated and enhanced.

    Dashboard Uniqueness: The existing dashboard was redesigned: the color palette, element layout, and dimensions were changed to create a unique visual style.

    Significance Visualization: New visualizations were added to show the values of the four main metrics for the control and test groups and to clearly indicate whether the difference between them is statistically significant.

    Interactivity: A filter by test number was added to the dashboard, allowing for a detailed analysis of the results of each individual experiment.

    Logic Explanation: The dashboard includes a text block describing the logic of the Python script, explaining how statistical significance is calculated and determined.

Final Result

The final product is a Google Colab notebook that contains:

    A Python script with all the calculations.

    A detailed description of the project stages and final conclusions.

    A direct link to the interactive dashboard on Tableau Public.

    A link to the .csv file with the calculation results.


🇺🇦 Українська версія 

Портфоліо-проєкт: Аналіз результатів A/B-тестування

Цей проєкт присвячений аналізу результатів A/B-тестування за допомогою статистичних методів в Python та створенню інтерактивної візуалізації в Tableau, що демонструє ключові конверсійні метрики та їхню статистичну значущість.

Мета проєкту

    Автоматизувати розрахунок статистичної значущості для метрик A/B-тестів за допомогою Python, зробивши процес гнучким та масштабованим.

    Продемонструвати навички роботи зі статистичними методами для аналізу конверсій.

    Створити унікальний та інформативний дашборд у Tableau для візуалізації результатів тестування.

Етапи проєкту

Етап 1. Розрахунок статистичної значущості в Python

На цьому етапі розроблено Python-скрипт у Google Colab для автоматизації розрахунків, що є більш гнучким рішенням порівняно з онлайн-калькуляторами.

    Набір даних: Використовуються дані з завдання "Create Your A/B Testing Tool".

    Ключові метрики для аналізу:

        add_payment_info / session

        add_shipping_info / session

        begin_checkout / session

        new_accounts / session

    Динамічний розрахунок: Скрипт побудований з використанням циклів та масивів, що дозволяє легко додавати нові метрики та проводити аналіз у різних розрізах (наприклад, за країнами, пристроями, номерами тестів).

    Результат етапу: Сформовано фінальний .csv файл, що містить усі розраховані метрики, довірчі інтервали та показники статистичної значущості, готовий для візуалізації.

Етап 2. Візуалізація результатів у Tableau

На основі даних, отриманих на першому етапі, було оновлено та доповнено аналітичний дашборд.

    Унікалізація дашборду: Існуючий дашборд було перероблено: змінено кольорову палітру, розташування елементів та розміри для створення унікального візуального стилю.

    Візуалізація значущості: Додано нові візуалізації, які показують значення чотирьох основних метрик для контрольної та тестової груп, а також чітко позначають, чи є різниця між ними статистично значущою.

    Інтерактивність: В дашборд додано фільтр за номером тесту, що дозволяє детально аналізувати результати кожного окремого експерименту.

    Пояснення логіки: Дашборд містить текстовий блок з описом логіки Python-скрипту, який пояснює, як саме розраховується і визначається статистична значущість.

Фінальний результат

Кінцевим продуктом є блокнот у Google Collab, який містить:

    Python-скрипт з усіма розрахунками.

    Детальний опис етапів проєкту та фінальні висновки.

    Пряме посилання на інтерактивний дашборд в Tableau Public.

    Посилання на .csv файл з результатами розрахунків.

