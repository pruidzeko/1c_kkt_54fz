[![Release](https://img.shields.io/github/tag/andrei-karpov/1c_kkt_54fz.svg?label=Last%20release&a)](https://github.com/andrei-karpov/1c_kkt_54fz/releases)

# ККТ-ОНЛАЙН 54ФЗ: «Обработка для работы фискальных регистраторов» #

В разделе [issues](https://github.com/andrei-karpov/1c_kkt_54fz/issues), можно добавить свои пожелания или задать вопросы по работе программы.

## Что умеет ##

- Поддерживает [несколько систем налогообложения](mechanism_distribution.md#распределение-по-системам-налогообложения) в одном документе 1С
- Можно использовать один фискальный регистратор с разных рабочих мест.
- Поддерживает последние изменения по 54 ФЗ, форматы обмена: ФФД **1.05** и **1.1**
- Можно использовать в составе отраслевых конфигураций: [**Рарус: Альфа-Авто, Далион**](connecting.md#особенность-подключения-рарус)
- Можно использовать там, где нет функционала по работе [с торговым оборудованием.](instruction.md#форма-отладки)
- Поддерживает собственный [шаблон чека](template_document.md#шаблон-документа-печати) для вывода рекламной или иной информации
- Можно разбить один чек сразу на [несколько ККТ](connecting.md#подключение-дополнительного-оборудования), например, алкоголь по одной кассе, а кухню по другой
- Можно изменить программу по-желанию, для этого есть дополнительно [подключаемая библиотека](for_programmers.md#изменение-функционала-под-себя).
- Можно дополнительно [печатать «копию» чека](instruction.md#печать-копии-чека) на обычном принтере.
- Перед фискальной печатью можно дополнительно сформировать предварительный чек, где будут выведены все нужные реквизиты для проверки
- Можно сформировать [чек коррекции](form_check_and_check_correction.md#чек-коррекции) средствами обработки, либо на основании типового документа
- Использует собственную форму «Рабочего места кассира» ([Форма проверки печати](form_check_and_check_correction.md))
- Поддержка печати чеков с детализацией номенклатуры по кассовым документам(Приходный кассовый ордер, Расходный кассовый ордер, Платежное поручение входящее и т.д)
- Отдельно можно использовать Эмулятор оборудования ККТ
- Позволяет [отправить электронный чек](management_distribution.md) средствами 1С по почте или в виде SMS
- Работает на платформах 1С [8.1](connecting.md#особенность-подключения-81), 8.2 и 8.3
- Работает на операционных системах **Windows** и [**Linux**](connecting.md#особенность-подключения-linux)

## Навигация ##

- [**Подключение обработки, и все с этим связанное**](connecting.md)
  - [Компоненты оборудования](connecting.md#компоненты-оборудования)
  - [Особенность подключения 8.1](connecting.md#особенность-подключения-81)
  - [Особенность подключения LINUX](connecting.md#особенность-подключения-linux)
  - [Особенность подключения Рарус](connecting.md#особенность-подключения-рарус)
  - [Особенность подключения Далион](connecting.md#особенность-подключения-далион)
  - [Особенность подключения УТ 10.2](connecting.md#особенность-подключения-ут-102)
  - [Структура архива с обработкой](connecting.md#структура-архива-с-обработкой)
  - [Подключение эквайринговых терминалов](connecting.md#подключение-эквайринговых-терминалов)
  - [Подключение дополнительного оборудования](connecting.md#подключение-дополнительного-оборудования)
- [**Описание параметров программы**](parameters_description.md)
  - [Основные параметры](parameters_description.md#основные-параметры)
  - [Дополнительные параметры](parameters_description.md#дополнительные-параметры)
  - [ЕНВД, УСН, Нефискальные чеки](parameters_description.md#енвд-усн-нефискальные-чеки)
  - [Параметры драйвера](parameters_description.md#параметры-драйвера)
  - [Параметры документов](parameters_description.md#параметры-документов)
  - [Параметры для ФФД](parameters_description.md#параметры-для-ффд)
  - [Маркировка](parameters_description.md#маркировка)
  - [Служебное](parameters_description.md#служебное)
  - [Ручное управление](parameters_description.md#ручное-управление)
- [**Лицензирование. Особенности покупки**](licensing.md)
  - [Форма лицензирования](licensing.md#форма-лицензирования)
  - [Особенность получения обновлений и технической поддержки](licensing.md#особенность-получения-обновлений-и-технической-поддержки)
  - [Написать разработчику](licensing.md#написать-разработчику)
- [**Маркировка. Продажа лекарств, шин, обуви и т.д.**](marking.md)
  - [Продажа маркировочного товара](marking.md#продажа-маркировочного-товара)
  - [Настройка типов маркировки](marking.md#настройка-типов-маркировки)
  - [Отражение продаж индивидуальных средства защиты](marking.md#отражение-продаж-индивидуальных-средства-защиты)
- [**Дополнительная функциональность**](instruction.md)
  - [Печать копии чека](instruction.md#печать-копии-чека)
  - [Подключение через прокси](instruction.md#подключение-через-прокси)
  - [Редактор произвольного кода](instruction.md#редактор-произвольного-кода)
  - [Форма отладки](instruction.md#форма-отладки)
- [**Рассылка чеков средствами обработки**](management_distribution.md)
  - [Рассылка чеков по SMS](management_distribution.md#рассылка-чеков-по-sms)
  - [Рассылка чеков средствами 1С по Email](management_distribution.md#рассылка-чеков-средствами-1с-по-email)
  - [Форма ввода Email и Номера телефона](management_distribution.md#форма-ввода-email-и-номера-телефона)
- [**Шаблон чека**](template_document.md)
- [**Форма проверки печати и чек коррекции**](form_check_and_check_correction.md)
  - [Настройка открытия формы проверки печати](form_check_and_check_correction.md#настройка-открытия-формы-проверки-печати)
  - [Настройка формы проверки печати](form_check_and_check_correction.md#настройка-формы-проверки-печати)
  - [Чек коррекции](form_check_and_check_correction.md#чек-коррекции)
- [**Механизм распределения. Как задать условия применения параметров программы.**](mechanism_distribution.md)
  - [Условия распределения](mechanism_distribution.md#условия-распределения)
  - [Распределение по системам налогообложения](mechanism_distribution.md#распределение-по-системам-налогообложения)
  - [Распределение по номерам секций](mechanism_distribution.md#распределение-по-номерам-секций)
  - [Распределение по договорам Агента](mechanism_distribution.md#распределение-по-договорам-агента)
  - [Настройка признаков предмета расчета](mechanism_distribution.md#настройка-признаков-предмета-расчета)
  - [Настройка признаков способа расчета](mechanism_distribution.md#настройка-признаков-способа-расчета)
  - [Настройка поставщика агента](mechanism_distribution.md#настройка-поставщика-агента)
  - [Настройка печати реквизитов ГТД и Страна](mechanism_distribution.md#настройка-печати-реквизитов-гтд-и-страна)
  - [Настройка печати получателя и его ИНН](mechanism_distribution.md#настройка-печати-получателя-и-его-инн)
  - [Настройка ограничения времени продажи](mechanism_distribution.md#настройка-ограничения-времени-продажи)
  - [Настройка ставки НДС по умолчанию](mechanism_distribution.md#настройка-ставки-ндс-по-умолчанию)
  - [Подмена номенклатуры](mechanism_distribution.md#подмена-номенклатуры)
- [**Для программистов**](for_programmers.md)
  - [Доработка конфигурации](for_programmers.md#доработка-конфигурации)
  - [Дополнительные параметры](for_programmers.md#дополнительные-параметры)
  - [Изменение функционала "под себя"](for_programmers.md#изменение-функционала-под-себя)
- [**Подключение Рарус**](rarus_connecting.md)
  - [Изменение конфигурации](rarus_connecting.md#изменение-конфигурации)
  - [Подключение оборудования](rarus_connecting.md#подключение-оборудования)
- [**Полезные ссылки**](useful_links.md)
- [**Возможные ошибки**](errors.md)
