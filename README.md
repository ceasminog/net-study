﻿# Курс .NET

- Система выставления [оценок](course-2017-1/readme.md)
- Посещаемость [студентов](course-2017-1/attendance.md)
- Список [заданий](exercises/exercises.md)
- Гайд по воркфлоу в [git+github](exercises/git-help.md).

---

- 1 [.NET](course/1-net.md#net)
  - [.NET Framework](course/1-net.md#net-framework)
    - [CLR](course/1-net.md#clr)
  - [.NET Core](course/1-net.md#net-core)
  - [.NET Standard](course/1-net.md#net-standard)
  - [.NET Native](course/1-net.md#net-native)
  - [IDE](course/1-net.md#ide)
  - [Nuget](course/1-net.md#nuget)
- 2 [Types](course/2-types.md#overview)
  - [Namespaces](course/2-types.md#namespaces)
  - [Primitive types](course/2-types.md#primitive-types)
    - [Integers](course/2-types.md#integers)
    - [Float numbers](course/2-types.md#float-numbers)
    - [Other common types](course/2-types.md#other-common-types)
  - [Операторы](course/2-types.md#операторы)
    - [Арифметические](course/2-types.md#арифметические)
    - [Поразрядные](course/2-types.md#поразрядные)
    - [Операторы с присваиванием](course/2-types.md#операторы-с-присваиванием)
    - [Логические операторы](course/2-types.md#логические-операторы)
    - [Ternary operator](course/2-types.md#ternary-operator)
    - [Null coalescing operator](course/2-types.md#null-coalescing-operator)
    - [Null conditional operator](course/2-types.md#null-conditional-operator)
  - [Контроль переполнения](course/2-types.md#контроль-переполнения)
  - [Приведение типов](course/2-types.md#приведение-типов)
  - [Ссылочные и значимые типы](course/2-types.md#ссылочные-и-значимые-типы)
    - [Stack & Heap](course/2-types.md#stack--heap)
    - [Referenced VS Value types](course/2-types.md#referenced-vs-value-types)
    - [System.Object](course/2-types.md#systemobject)
- 3 [Value types](course/3-value-types.md#value-types)
  - [Struct](course/3-value-types.md#struct)
  - [Nullable](course/3-value-types.md#nullable)
  - [Guid](course/3-value-types.md#guid)
  - [Dates, times](course/3-value-types.md#dates-times)
    - [DateTime](course/3-value-types.md#datetime)
    - [DateTimeOffset](course/3-value-types.md#datetimeoffset)
  - [Enum](course/3-value-types.md#enum)
    - [Enum Flags](course/3-value-types.md#enum-flags)
- 4 Классы
  - Конструкторы
  - Модификаторы доступа
  - Модификаторы типов: static, abstract, partial, sealed
  - Наследование, полиморфизм, интерфейсы
  - Перегрузка методов, операторов
  - Аттрибуты
  - Generic типы и методы, constraint
  - Анонимные типы, dynamic
  - Extension methods
  - Сборка мусора:
    - Алгоритм, GC
    - Финализаторы
    - Внешние ресурсы, IDisposable pattern
- 5 Строки
  - Символы и строки
  - Создание, преобразование строк. Класс StringBuilder
  - Кодировки, преобразование строк в байт
- 6 Управление программой
  - Циклы, IEnumerable, yield
  - Условные операторы
- 7 Коллекции
  - Типы коллекций и различия между ними
- 8 Делегаты и события
  - Делегаты и обобщенные делегаты, лямбда выражения
  - События
  - Замыкания
- 9 LINQ
  - Отложенные и неотложенные запросы
  - Стандартный и Query Expressions синтакис запросов
- 10 Обработка ошибок
  - Exception
  - throw / try / catch / finally
  - Debug / Trace
- 11 Reflection
- 12 Многопоточность и ассинхронность
  - Проблемы многопоточности
  - Примитивы синхронизации
  - Thread / Threadpool
  - TPL. Класс Task, Continuation, Cancellation
  - async / await, SyncronizationContext
- 13 Сериализация данных
  - JSON
  - XML
- 14 Ввод / вывод
  - Потоки
  - Чтение и запись текстовой информации
  - Работа с файловой системой. System.IO
- 15 Работа с базами данных
  - ADO.Net
  - Entity Framework
  - Simple mapper: dapper, linq2db
- 16 Принципы и паттерны проектирования
  - SOLID
  - Связь классов: наследование, ассоциация, композиция, агрегация
  - Dependency Injection, IOC, управление зависимостями
  - Тестируемость приложения, unit-test, Moq
  - Паттерны: Singleton, Factory, Strategy, Facade, Repository
- 17 Работа в web
  - Http в .Net, класс HttpClient
  - ASP.Net MVC Core
