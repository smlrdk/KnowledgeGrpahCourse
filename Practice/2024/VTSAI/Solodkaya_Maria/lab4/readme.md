# Лабораторная работа 4

Выполнили:
* Полежаева Евгения (P4240)
* Солодкая Мария (P4240)

## Графовые нейронные сети (GNNs)
Графовые нейронные сети представляют собой класс нейронных сетей, специально разработанный для работы с графовыми структурами данных. Они могут моделировать зависимости и взаимодействия между сущностями в графе, позволяя учитывать контекст и структуру данных при выполнении задач.

В GNN каждая вершина графа обновляется на основе её соседей, что позволяет модели учить представления вершин, учитывая их окружение. Такие модели широко применяются в задачах, связанных с анализом социальных сетей, биологических сетей, рекомендательных систем и графовых знаний.

## Graph embedding
Эмбеддинги в контексте графовых нейронных сетей представляют собой векторные представления вершин графа. Они извлекаются из GNN и представляют сущности в пространстве низкой размерности. Эти векторы обладают свойством сохранять структурную информацию о графе и могут использоваться для различных задач, таких как предсказание отношений или классификация вершин.

## Тестирование и Валидация
Тестирование и валидация важны для оценки работы графовых нейронных сетей.

Тестирование позволяет оценить обобщающую способность модели на новых данных, которые не участвовали в обучении. Это важно для проверки, насколько хорошо модель обобщает свои знания на новые сценарии.

Валидация используется для подбора оптимальных гиперпараметров модели. Настройка параметров происходит на основе производительности модели на отложенной валидационной выборке.

## Датасет:

[Kinships](https://paperswithcode.com/dataset/kinships)

## Выводы:

1. Освоили применение графовых нейронных сетей (GNNs) для анализа зависимостей в графовых структурах данных. Эмбеддинги, извлеченные с использованием GNN, позволяют представить вершины графа в векторной форме, сохраняя важную структурную информацию.

2. Осуществлено тестирование модели на новых данных и валидация для подбора гиперпараметров с использованием датасета Kinships, что позволило оценить обобщающую способность и оптимальность модели. 

3. Библиотека Pykeen нацелена на упрощение взаимодействия с графовыми данными.

4. Решена задача предсказания отношений в контексте родственных связей с использованием модели TransE и датасета Kinships.

5. Проведена оценка производительности модели с пощью эпох обучения и валидации.
