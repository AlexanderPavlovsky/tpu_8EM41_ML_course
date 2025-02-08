# Методы ИИ

Данный документ направлен на первичную подготовку репозитория средства
индивидуальной разработки к выполнению 1 и 2 лабораторных работ.

## Тема

Методы искусственного интеллекта. EDA. Линейная регрессия. Дерево решений. CatBoost. XGBoost. Нейронные сети (MLP).

## Цель работы

Целю данной работы заключается в получении навыков анализа первичных данных и определение признаков взаимосвязи (EDA), понимания моделей: линейная регрессия, дерево решений, CatBoost, XGBoost, нейронные сети (MLP) и умения разрабатывать программу на языке Python для реализации представленных моделей.

## Ход работы
1) Описать датасета и определить влияние признаков и выбрать признаки, которые наиболее подходят для поставленной задачи предсказания (EDA).
2) Построить пайплйан (DVC) исходя из результатов EDA.
3) Реализовать линейную регрессию, определить весы, метрики и ошибки.
4) Реализовать дерево решений, определить метрики и ошибки. Привести рисунок первых узлов дерева решений.
5) Реализовать CatBoost, определить метрики и ошибки. Выгрузить Feature Importance.
6) Реализовать XGBoost, определить метрики и ошибки. Выгрузить Feature Importance.
7) Реализовать нейронную сети, определить метрики, ошибки, кривые обучения, гимтограммы весов с интерпретацией и график из Tensorboard.
8) Выгрузить конечный вычислительный граф DVC.
9) Построить сводную таблицу с метриками и сделать вывод какая модель отработала лучше и почему.
10) Сделать вывод по работе.

## Анализ данных
После проведенного анализа данных должно быть понятно:
1) Какие признаки будут использованы для предсказания и почему?
2) Как будут преобразованы выбранные признаки и почему?
3) Оценить значимость каждого признака?
В конце EDA должен быть полный и исчерпывающий вывод о том, какие данные и как будет решаться поставленная задача.

Примеры проведенных анализов данных на примере других данных: 
- https://www.kaggle.com/code/ash316/eda-to-prediction-dietanic
- https://www.kaggle.com/code/lucamassaron/eda-target-analysis
- https://www.kaggle.com/code/upadorprofzs/eda-video-game-sales



### Необходимо ПО
Visual Studio Code, Python, Jupyter extension pack, DVC extension pack.

### Дополнительные материалы
Ссылка на документацию и установку DVC: https://dvc.org/

Ссылка на пример построения пайплайна DVC: https://learn.iterative.ai/course/data-scientist-path

Дополнительно по линейной регрессии: https://habr.com/ru/post/514818/
