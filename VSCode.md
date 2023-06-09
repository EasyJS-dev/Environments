<h1 align="center">Инструкция по настройке Visual Studio Code</h1>

# **Установка VS Code**

## Для устройств на Windows:

- Переходим по ссылке и качаем программу для нашей операционной системы - https://code.visualstudio.com/download
- Запускаем установщик и следуем его инструкциям по установке. Тут процесс установки не отличается от установки любой другой программы - выбираете папку, куда установить программу и устанавливаете.

## Для устройств на MacOS:

- Переходим по ссылке и качаем программу для нашей операционной системы - https://code.visualstudio.com/download
- Разархивируем скачанный файл (просто дважды нажимаем на него)
- Перетаскиваем распакованный файл в папку Applications
- Добавляем файл в Dock (нижнее меню с приложениями) - нажимаем Options и выбираем «Keep in Dock»

## Для устройств на Linux:

- Переходим по ссылке и качаем программу для нашей операционной системы - https://code.visualstudio.com/download
- Рапаковываем скачанный архив в новую папку
- Запускаем VS Code двойным щелчком

<br>

---

# Дополнительные настройки (опционально):

## 1. Установка темной темы

В основном, разработчики стараются использовать темы с темным фоном (dark mode) в программах, которых есть такая возможность. Вы можете использовать темы на свое усмотрение, но ниже я приведу несколько причин в пользу темных тем:

- Темный режим снижает напряжение на глаза. Хоть человеческий глаз и привык и черным чернилам на белом листе, экран компьютера - не бумага и белый фон сильно нагружает ваши зрительные органы. Наше зрение легче воспринимает белый шрифт на темном фоне. Конечно, есть разные дополнительные факторы - внешнее освещение, тип вашего монитора и расстояние до него и т.д.
- Решается проблема мерцания дисплея. У экранов качества пониже или более старых моделей сильно заметно мерцание экрана на светлом фоне. От долгой работы на таком мониторе могут начаться головные боли и ухудшиться зрение. При использовании темной темы даже на максимальной яркости экрана мерцаний не будет видно.
- Увеличивается время работы от аккумулятора у ноутбуков с OLED-экранами. Это связано с тем, что для отображения черного цвета на данных экранах не требуется дополнительных затрат энергии. Таким образом в некоторых приложениях, при использовании темной темы, можно сэкономить от 15% до 63% батареи (это касается так же и мобильных устройств).
- Удобнее работать с несколькими мониторами. Часто разработчики используют 2-3 монитора, а светлый фон может отвлекать боковым зрением от основого экрана

Инструкция для установки Dark Mode в VS Code:

- Выберите настройки темы в программе пройдя по пути: **_File (Файл) > Preferences (Параметры) > Theme (Темы) > Color Theme (Цветовая тема)_**. (Для MacOS - **_Code (Код) > Preferences (Параметры) > Theme (Темы) > Color Theme (Цветовая тема)_**).
- Выберите нужную тему из списка. Я предпочитаю "**_Monokai Dimmed (Monokai с уменьшенной яркостью)_**"

<br>

## 2. Установка русского языка

Изначально программа поставляется на английском языке, но, так как для некоторых это может вызвать дискомфорт - можно перевести его на русский язык, установив языковой пакет по инструкции ниже.

- На боковой панели слева выберите "Extensions" (иконка с четырьмя квадратами)
- В строке поиска введите "Russian Language Pack"
- Выберите первое расширение в списке, нажмите "Install" и после окончания установки перезапустите программу

Если вдруг после перезапуска программа осталась на английском языке, то проделайте следующие действия.

- На левой панели снизу нажмите иконку шестерёнки и выберите "Command Palette"
- В появившейся строке поиска введите "Display" и выберите "Configure Display Language"
- Выберите русский язык в списке и снова перезапустите программу

<br>

---

# Установка расширений

В этом пункте я приведу несколько расширений, которые я использую для работы с VS Code. Изначально я бы рекомендовал все-таки установить их, а уже в будущем, кода вы будете ориентироваться в своих потребностях и понимать, что вам нужно, а что нет - будете подстраивать их под себя.

- Prettier
