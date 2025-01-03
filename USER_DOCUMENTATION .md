# Пользовательская документация

## 1. Введение

Программа “Отсечение отрезков и многоугольников” предоставляет возможность визуализации алгоритмов отсечения отрезков (алгоритм Сазерленда-Коэна) и отсечения выпуклого многоугольника. Пользователь может переключаться между двумя частями программы, вводить координаты и наблюдать результаты работы алгоритмов.

## 2. Системные требования

- **Операционная система**: Windows XP и выше, MacOS, Linux
- **Программное обеспечение**: Браузер с поддержкой HTML5 (например, Google Chrome, Firefox, Safari)
- **Аппаратные требования**:
  - Минимум 1 ГБ ОЗУ
  - Процессор с тактовой частотой 1 ГГц или выше

## 3. Установка

### 3.1 Скачивание программы

1. Перейдите на [GitHub-репозиторий проекта](https://github.com/hemrahudayberdi1/LAB5).
2. Скачайте файл `LAB5` или клонируйте репозиторий:
   git clone https://github.com/hemrahudayberdi1/LAB5

### 3.2 Запуск программы

1. Откройте папку с файлом `LAB5`.
2. Дважды щелкните по файлу `LAB5`, чтобы открыть его в браузере.
3. Программа будет загружена и готова к использованию.

## 4. Использование приложения

### 4.1 Основной интерфейс

Программа отображает:
- Заголовок с кратким описанием функционала.
- Кнопки для переключения между частями:
  - **Часть 1**: Отсечение отрезков (алгоритм Сазерленда-Коэна).
  - **Часть 2**: Отсечение выпуклого многоугольника.
- Холст для визуализации алгоритмов.
- Поле для отображения координат курсора.

### 4.2 Часть 1: Отсечение отрезков

1. Нажмите кнопку **"Часть 1: Отсечение отрезков"**.
2. На холсте отобразятся:
   - Прямоугольное окно отсечения.
   - Исходные отрезки (красным цветом).
   - Отсеченные отрезки (зеленым цветом).
3. Наведите курсор на холст, чтобы увидеть текущие координаты.

### 4.3 Часть 2: Отсечение выпуклого многоугольника

1. Нажмите кнопку **"Часть 2: Выпуклый многоугольник"**.
2. На холсте отобразятся:
   - Выпуклый многоугольник (красным цветом).
   - Отсеченные границы (зеленым цветом).
3. Исходные и отсеченные сегменты визуализируются разными цветами.

### 4.4 Работа с координатной системой

- Основные оси координат (X и Y) проходят через центр холста.
- Координаты отображаются динамически внизу страницы при наведении курсора.

## 5. Пример использования

### Пример 1: Часть 1
- Отображение отрезков:
  - Исходные координаты: 
    - (100, 700) → (600, 300)
    - (200, 600) → (700, 200)
  - Отрезки будут отсечены в пределах окна (200, 200) → (600, 600).

### Пример 2: Часть 2
- Отображение выпуклого многоугольника:
  - Исходные вершины: 
    - (300, 500), (400, 700), (600, 650), (550, 400), (350, 300).
  - Отсечение выполняется в пределах окна (200, 200) → (600, 600).

## 6. Обратная связь

Для вопросов и предложений: hemrahudayberdiyev4@gmail.com


# Приложения

## Приложение 1. Список реализованных алгоритмов

1. **Алгоритм Сазерленда-Коэна** (отсечение отрезков).
2. **Алгоритм отсечения выпуклого многоугольника**.

## Лицензия

Программа распространяется на условиях лицензии MIT. Подробнее в репозитории проекта.

## Дополнительные материалы

- Репозиторий проекта: [GitHub](https://github.com/hemrahudayberdi1/LAB5)
- Алгоритмы компьютерной графики: [Wikipedia](https://ru.wikipedia.org/wiki/Компьютерная_графика)

## Обновления документации

Документация обновляется при внесении изменений в программу. Рекомендуется проверять ее актуальность в репозитории проекта.