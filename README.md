# payment_changes
Анализ изменения механики оплаты услуг.  

Цель: анализ эксперимента ввода новой механики оплаты услуг.  

Стек: Python (pandas, numpy, seaborn, matplotlib, combinations, requests, scipy.stats)   

Ключевые этапы и результат: 
- EDA.
- Поиск различий в группах и статусах (активен / не активен) клиентов.
- Из представленных сумм чеков выявил базовые компоненты, применил алгоритм нахождения наиболее вероятной комбинаций для каждого значения суммы покупок.
- Нашел различия между группами и статусами клиентов по характеру и количеству приобретенных услуг.
- Проверил гомогенности дисперсий и провел стат. тест по ключевой метрике.
- Визуализировал основные метрики.
- Добавил функцию пересчета метрик при дополнительной загрузке данных.

Результат: новая механика оплат услуг превзашла ожидания (MDE), необходимо распространять на всех клиентов.
