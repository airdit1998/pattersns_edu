Состояние — это поведенческий паттерн, позволяющий динамически изменять поведение объекта при смене его состояния.

Поведения, зависящие от состояния, переезжают в отдельные классы. Первоначальный класс хранит ссылку на один из таких объектов-состояний и делегирует ему работу.

Применимость: Паттерн Состояние часто используют в Python для превращения в объекты громоздких стейт-машин, построенных на операторах switch.

Признаки применения паттерна: Методы класса делегируют работу одному вложенному объекту.