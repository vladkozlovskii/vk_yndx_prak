# vk_yndx_prak
## Репозиторий учебных проектов, выполненных в ходе прохождения курса Data Scientist в Яндекс практикуме

1. Проект музыка больших городов  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/01_Music_project_DA  
Первый проект реализованный в ходе обучения. Проект базово самый простой - структура была дана изначально, в проекте отрабатывались применение циклов, функций и группировок  

2. Проект Исследование надежности заёмщиков  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/02_Bank_scoring_DA  
Второй проект в ходе курса. Проект тоже достаточно простой, здесь уже велась предобработка данных, выводились простые графики, были применены подходы к работе с текстом (лемматизация), также выполняются группировки и создание сводных таблиц  

3. Проект Исследование объявлений о продаже квартир  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/03_Realty_SPB_DA    
Третий проект, чуть более объемный. Данные похоже на реальные, требовалась предобработка, здесь чуть более развитые графики, используются те же подходы, что и раньше (циклы, функции метод apply) есть исследования корреляций. Также как и впрошлом есть обработка текста, есть работа с datetime  

4. Проект Предварительный анализ тарифов компании Мегалайн на небольшой выборке клиентов  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/04_Tariffs_phone_DA  
Проект посвящен анализу данных сотовых операторов, содержит те же подходы, что и ранее. Особенность в наличии нескольких датасетов между, которыми при помощи группировок циклов и apply устанавливается взаимодействие. Используется категоризация, объединение таблиц. Впервые проводится исследование статистических гипотез  

5. Проект Выявление закономерностей определяющих успешность игр  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/05_Games_DA  
Финальный (сборный) проект блока по аналитике данных (до применения машинного обучения). В проекте ведется анализ данных по продажам игр, применяются подходы изученные в рамках прохождения блока по аналитике. Есть предобработка данных, более активно испольузются графики, срезы, есть проверка статистических гипотез. Во многом по объему сходен с третьим проектом  

6. Проект Рекомендация тарифов  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/06_Tariifs_ML  
Первый проект блока по машинному обучению. Проект посвящен рекомендации тарифов, предобработки данных нет, решается задача классификации (бинарной), метрика качества accuracy. Используются различные модели - проводится исследование какая из них лучше  

7. Проект Отток клиентов  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/07_Bank_project  
Второй проект блока ML, решатеся задача классификации(бинарной), целевая метрика F1. В проекте уже проводится предобработка данных, испольузются методы борьбы с дисбалансом классов (включая upsampling, downsapling). Используются различные модели - проводится исследование какая из них лучше. Дополнительно к F1 исследуется AUC-ROC  

8. Проект Выбор локации для скважины  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/08_Geology_ML  
В проекте основное внимание уделено применению bootstrap и анализу его результатов, предобработка данных не ведется, но ведется их исследование. Машинное обучение присутствует, но является вторичной задачей (задача регрессии, метрика rmse)  

9. Проект Восстановление золота из руды  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/09_Substances_ML  
Сборный проект первой части по ML. Проект содержит элементы и первой части по ML и блока по DA. Решается задача регресии - метрика smape. Основное внимание идет на борьбу с мультиколинеарностью и уменьшение числа признаков. Блок по анализу явялется во многом самостоятельным (в оснвном его результат графики), но также дает информацию для удаления выбросов. По реузльтатам удаления лишних признаков и выбросов проверяются различные модели (как и раньше идет подобор гиперпараметров), начиная с этого проекта ведется использование кросс-валидации  

10. Проект Защита персональных данных клиентов  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/10_Matrix_phones_crypto_ML  
Проект посвящен в основном теоретической задаче - идет после первого блока по линейно алгебре и оснвное содержание это работа с матрицами и то как свойства работы с ними могут использоваться для шифрования данных. Моделирование проводится для проверки результата, в проекте используется Линейная регрессия (ей также во многом посвящен блок) метрика R2  

11. Проект Определение стоимости автомобилей  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/11_Cars_ML  
Первый проект с применением моделей градиентного бустинга (здесь LightGBM). Решается задача регрессии - целевая метрика rmse. В проекте достаточно большую часть занимает предобработка данных, также много внимания уделяется параметрам LightGBM. Ведется кросс-валидация и подобор параметров для различных моделей. Используются разные способы работы с категориальными признаками  

12. Проект Прогнозирование заказов такси  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/12_%D0%A2axi_ML_time_sereis  
Проект посвященный анализу временных рядов. Задача классификации - метрика rmse. Особенности проекта - подготовка различных признаков исходя из datetime и числа заказов. Кросс-валидация в условиях временных рядов. Ведется выбор оптимальной модели, подбор гиперпараметров и тестирование модели  

13. Проект для «Викишоп» с BERT  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/13_Text_toxicity_ML_NLP  
Проект посвященный анализу текстов - ведется предобработка текстов, векторизация - работа с TF-IDF. Решается задача бинарной классификации (токсичность комментария) - ведется выбор оптимальной модели, подбор гипрепараметров, целевая метрика F1. Дополнительно сделана попытка построения модели после подготовки признаков с BERT  

14. Проект Определение возраста покупателей
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/14_Age_by_face_ML_CV  
Проект посвящен знакомству с применением нейронных сетей (ResNet50) в классификации изображений. Целевая метрика MAE. Модель обучалась на GPU-тренажере яндекс практикума. Отдельно сделан анализ для определенного возрастного интервала  

15. Проект Промышленность  
https://github.com/vladkozlovskii/vk_yndx_prak/tree/main/15_Final_project_ML  
Финальный проект, отчасти сходен со собрным проектом про восстановление руды. Решается задача регрессии, метрика MAE. Данные идут из нескольких датасетов. Ведется предобработка данных с заполнением (удалением) порпусков, выцеплением целевого признака. Ведется подготвка новых признаков на основании имеющихся данных (с объединением данных из разных даатфреймов), в данном проекте применяется снижение размерности (не единственный путь решения задачи - но в данном случае был вполне оправданным), идет исследование важности признаков. Ведется подобр гиперпараметров и кросс-валидация на различных моделях, тестирование на лучшей модели  
