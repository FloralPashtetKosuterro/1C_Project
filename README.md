# 1C_Project

Это мои первые шаги в 1C.

В данной конфигурации в настоящее время присутствуют справочники:
1)ИнструментыДляПисьма;
~~2)Расходники;~~
2)Сотрудники.

Также, я создал подсистему "Склад", с которой связал вышеописанные объекты.

- Установлено свойство "Иерархический" на объект "ИнструментыДляПисьма" для группировки;
- В справочник "Сотрудники" добавлена табличная часть "СоставСемьи";
- Созданы подсистемы: 1)ОказаниеУслуг; 2)РасчётЗарплаты;
- ❗️❗️ Я посчитал, что расходники как отдельный справочник был ошибкой. По итогу создана табличная часть в справочнике "ИнструментыДляПисьма".
Буду записывать подробности про товар в табличной части "ТоварыБренда". ❗️❗️
- Созданы процедуры для подсчёта суммы в документе "ДокументРасчётЗарплаты"
- Создан регистра накопления для документа "ДокументРасчётаЗарплаты"
  
