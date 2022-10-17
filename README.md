# BMI_calculator_OOP_baised

В рамках данного проекта было реализовано приложение калькулятор индекса массы тела (BMI).
В общем виде структура программы выглядит следующим образом:
* Класс BMI – содержит метод calc – ответственный за расчёт значения BMI и свой конструктор
* Класс Metrics – описывает объект метрики. Метрика содержит в себе лево и правое значение диапазона для данной категории (Дефицит массы тела, Норма, Избыточный вес и.т.д), Номер категории, текстовое представление категории. Класс Metrics содержит в себе метод Within типа Boolean, который возвращает true/false в зависимости от того, входит ли переданное значение BMI в диапазон данной категории, а также конструктор класса
* Класс Diagnosis – содержит в себе 2 метода fillMetrics и ShowDiagnosis,а также массив Metrics заданной длины size. Метод fillMetrics производит заполнение массива метрик значениями, получаемыми из тестового файла. Метод ShowDiagnosis производит сравнение рассчитанного значения BMI с элементами массива метрик, после чего выводит в текстовое поле соответствующий диагноз. 

## Пример GUI программы:

![1 img](images/1.jpg?raw=true "Title")

![2 img](images/2.jpg?raw=true "Title")

![3 img](images/3.jpg?raw=true "Title")