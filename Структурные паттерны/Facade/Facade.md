Фасад — это структурный паттерн, который предоставляет простой (но урезанный) интерфейс к сложной системе объектов, библиотеке или фреймворку.

Кроме того, что Фасад позволяет снизить общую сложность программы, он также помогает вынести код, зависимый от внешней системы в единственное место.

Применимость: Паттерн часто встречается в клиентских приложениях, написанных на Python, которые используют классы-фасады для упрощения работы со сложными библиотеки или API.

Признаки применения паттерна: Фасад угадывается в классе, который имеет простой интерфейс, но делегирует основную часть работы другим классам. Чаще всего, фасады сами следят за жизненным циклом объектов сложной системы.