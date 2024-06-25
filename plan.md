## План тестирования приложения
### 1. Планирование (7 часов)
#### Определение границ приложения (2 часа):
- Основные функциональные и нефункциональные требования:
   - Авторизация пользователей.
   - Отображение главного экрана с новостями и цитатами.
   - Навигация по приложению.

#### Анализ реализованного функционала (1 час):
- Проверка соответствия функциональности приложения требованиям:
   - Возможность входа в систему.
   - Отображение главного экрана.
   - Возможность раскрытия списка Новости.
   - Открытие меню.
   - Навигация в пунктах меню ("Главная", "Новости", "О приложении").
   - Возможность сортировки, фильтрации, редактирования и отмены, добавления новостей.
   - Открытие окна тематических цитат, возможность открытия и закрытия списка цитаты.
   - Отображение профиля пользователя.
   - Возможность выхода из приложения.

#### Создание базы для тестов (4 часа):
- Структура тестовых сценариев и чек-листов, охватывающая все аспекты приложения:
   - Авторизация.
   - Главный экран.
   - Новостная сводка.
   - Меню ("Главная", "Новости", "О приложении")
   - Тематические цитаты.
   - Выход.

#### Применимые типы тестирования:
- Исследовательское тестирование: изучение приложения, анализ сценариев и проектирование возможных тестов.
- Функциональное тестирование: проверка соответствия реализованных функций требованиям.
- Интеграционное тестирование: проверка взаимодействия Android-приложения с API.

### 2. Составление чек-листа (11 часов)
#### Регистрация и вход (2 часа):
- Проверка формы авторизации, правильности ввода логина и пароля.
- Проверка сценариев успешного и неуспешного входа в систему.

#### Главный экран (1 час):
- Проверка отображения главного экрана.
- Проверка элементов навигации.

#### Новостная сводка (2 часа):
- Проверка отображения новостей.
- Проверка взаимодействия с новостным контентом (сортировка, фильтрация, редактирование).

#### Тематические цитаты (1 час):
- Проверка отображения цитат.
- Проверка возможности взаимодействия с цитатами.

#### Обработка сетевых сбоев (1 час):
- Проверка поведения приложения при отсутствии сети.
- Проверка обработки ошибок API.

#### Специфичные проверки работы мобильного приложения (4 часа):
- Проверки на прерывания.
- Работа с функциями телефона (ориентация, жесты, светлая и темная темы).
- Соответсиве гайдлайнам Google.

### 3. Составление тест-кейсов (14 часов):
- Создание тест-кейсов для каждого пункта чек-листа.
- Дополнение тест-кейсов при обнаружении новых требований и функционала.
- Определение тест-кейсов для ручного и автоматизированного тестирования.

### 5. Автоматизация (20 часов)
#### Подготовка проекта (4 часа):
- Интеграция библиотек для автоматизации тестирования (например, Appium, Espresso).
- Создание директории для хранения тестовых скриптов.
- Настройка тестового класса для инициализации и завершения тестов.

#### Разработка UI-тестов (16 часов):
- Написание тестов, имитирующих действия пользователя и проверяющих ключевые функции приложения.
- Обеспечение каждой проверки ожидаемым результатом.

#### Инструменты инженера:
- Процессор для среды разработки: MacBook Pro Apple M3 Pro, MacOS Sonoma 14.5.
- IDE: Android Studio Iguana 2023.2.1 Patch 1.
- Физическое устройство: Samsung Galaxy s23 Ultra (One UI 6.1, Android 14).
- Автотесты: Espresso для Android-приложений.
- Перехват трафика: Charles Proxy.
- Отчеты: Allure Framework.

### 6. Составление отчёта (3 часа)
#### Интеграция Allure (1 час):
- Добавление зависимостей для Allure.
- Настройка интеграции с Allure Server.

#### Упаковка отчетов (2 часа):
- Обеспечение полноты и информативности отчетов.
- Упаковка отчетов в архив для удобства хранения и передачи заинтересованным сторонам.

### Общее время: 55 часов