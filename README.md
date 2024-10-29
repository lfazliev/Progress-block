Блок Progress для мобильных web-приложений

Описание
Этот проект представляет собой прототип блока Progress, предназначенного для использования в мобильных web-приложениях. Блок Progress визуализирует процесс выполнения задач с помощью дуги, отображающей степень завершения.

Функциональность
Блок Progress поддерживает три состояния:

1.  Normal — базовое состояние. Уровень прогресса задается через параметр Value (от 0 до 100). Дуга, соответствующая прогрессу, начинает заполняться с позиции 12 часов и движется по часовой стрелке.
2.  Animated — блок или его элементы вращаются с заданным периодом по часовой стрелке.
3.  Hidden — скрывает блок со страницы.

Технологии
• JavaScript.
• CSS.
• HTML.

Управление
В приложении реализованы элементы управления:
• Поле Value — для ввода числа от 0 до 100, контролирующего размер дуги.
• Переключатели Animate и Hide — для управления состояниями блока.

Запуск проекта

1.  Склонируйте репозиторий:
    git clone
2.  Откройте index.html в браузере.

Приложение доступно по ссылке: GitHub Pages.

Особенности
• Адаптивный дизайн для корректного отображения при смене ориентации экрана.
