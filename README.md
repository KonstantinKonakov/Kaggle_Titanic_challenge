В данном репозитории содержится лог моей работы над проектом Titanic Challenge

Работа выполнена на языке Python

Это был импровизированный конкурс внутри когорты 05 потока студентов Yandex.Praktikum Data Science

Особое внимание я уделил этапу подготовки признаков и заполнения пропусков. 

Например, по имеющимся словам Master и Miss в имени пассажира выделил детей. 
А именно этот класс пассажиров команда пыталась спасти в первую очередь.

В целом мои усилия позволили мне занять второе место в нашей когорте с результатом 0.79425 
Визуализация результататов производилась с помощью библиотек Seaborn и MatplotLib.

Классификация выполнена с помошью модели: SciLearn RandomForestClassifier. Так же тестировал GradientBoosting.
При этом поиск оптимальных гиперпараметров выполнен с помошью GreadSearch 
с оценкой качества кросс-валидацией из этой же библиотеки.

