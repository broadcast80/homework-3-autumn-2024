# Домашнее задание №3 - Чек-листы

### Команда: beastie boys
Выполнил: Атрошко Никита

В рамках третьего домашнего задания были сделаны чек-листы на проект [VK Реклама](https://ads.vk.com/)

## Содержание 
1. [Центр коммерции](#центр-коммерции)
2. [Сайты](#сайты)
3. [Мобильные приложения](#мобильные-приложения)
4. [Лид-формы и опросы](#лид-формы)
5. [Помощь (задать вопрос/чат-бот)](#помощь)

----
Центр коммерции
---

![image](https://github.com/user-attachments/assets/5835cc15-51b0-4e38-b79a-24bf78553321)
- Если у пользователя нет каталогов товаров то экран содержит:
  - Информационное окно со списком необходимых для создания каталога действий
  - Кнопка [создать каталог](#создание-каталога)
  - Кнопка пройти обучение
 

![image](https://github.com/user-attachments/assets/e4c70c9f-d3cb-4399-9367-98b97c63083a)
- Если у пользователя уже есть каталоги товаров то экран содержит:
  - Кнопка [создать каталог](#создание-каталога)
  - Поле поиска каталогов
  - Список каталогов
    - При нажатии на каталог из списка происходит открытие [страницы каталога](#)
    - При нажатии на троеточие появляется окно с двумя кнопками
    - ![image](https://github.com/user-attachments/assets/0dd018c1-b235-4f4d-88a3-c4b279815d3f)
      - [Настроить каталог](#настройка-каталога)
      - Удалить каталог
        - При нажатии на кнопку удалить каталог появляется модальное окно
        - ![image](https://github.com/user-attachments/assets/9b2da5a7-e950-4f9c-8464-9f99b526e6b8)
        - При нажатии на кнопку удалить каталог пропадает из списка каталогов
        - При нажатии на кнопку отменить модальное окно закроется
## Создание каталога
- При нажатии на кнопку создать каталог появляется форма создания каталога
- При попытке нажать на кнопку "Создать каталог" без введенной информации о каталоге поле выделится красным и появится предупреждение

![image](https://github.com/user-attachments/assets/4ccaa19e-f737-4b24-b8c6-a148f27cb15b)
- После создания, каталог появляется в списке каталогов
![image](https://github.com/user-attachments/assets/68800afc-de51-46bc-8cc3-cee63f7a77cb)
- При создании каталога с именем, которым назван уже другой каталог создатся каталог с таким же именем, однако ID будет другим.

## Настройка каталога
- При нажатии на кнопку настроить каталог откроется окно редактирования каталога
  - Если ввести новое название и нажать на кнопку сохранить, окно закроется и каталог изменит свое имя в списке
  - При нажатии на кнопку "отмена" окно закрывается
  - При нажатии на кнопку "удалить каталог" появляется модальное окно
    - ![image](https://github.com/user-attachments/assets/e78e6d2e-776e-41a1-93e7-9dd4c83c4124)
    - При нажатии на кнопку "отменить" или на крестик модальное окно закрывается
    - При нажатии на кнопку "удалить" модальное окно закрывается и каталог пропадает из списка товаров


## Страница каталога
![image](https://github.com/user-attachments/assets/e653f103-9d09-4b58-9a71-a89e611cfc0e)

Страница каталога содержит:
- Верхний навбар с названием каталога, информацией о кол-ве всех и активных товаров а также кнопку [настроить каталог](#настройка-каталога)
- 5 функционально сгруппированных окон:
  - [Товары](#товары)
  - [Группы](#группы)
  - [Диагностика](#диагностика)
  - [События](#события)
  - [История загрузок](#история-загрузок)
 
### Товары
![image](https://github.com/user-attachments/assets/6d08dfa0-79a1-4f51-a52e-c363a5d85390)
### Добавить товар
- При нажатии на кнопку добавить товар появляется модальное окно с окном для загрузки файла
  - ![image](https://github.com/user-attachments/assets/364ef073-e834-454a-84c7-078118f482bb)
  - При нажатии на кнопку продолжить без выбранного файла появляется предупреждение
    - ![image](https://github.com/user-attachments/assets/0546a84d-f954-4620-84de-32f41684e995)
  - При добавлении csv файла и нажатии на кнопку продолжить открывается пункт "история загрузок" с пунктом о данной загрузке. Добавленный товар появится в списке в пункте "товары"
- При нажатии на кнопку рекламировать открывается страница кампаний
- При нажатии на кнопку с шестеренкой появляется модальное окно с настройками таблицы
  - ![image](https://github.com/user-attachments/assets/ed9e8314-924d-48e9-909b-e06f54db97c4)
  - При снятии чекбокса с одной из метрик она пропадает из информации о товаре
- При нажатии на чекбокс в таблице товаров появляется кнопка архивировать справа от кнопки рекламировать
  - ![image](https://github.com/user-attachments/assets/1ae4230e-ae5c-47a4-8d07-f13e411cd14f)
  - При нажатии на кнопку архивировать появляется модальное окно
  - ![image](https://github.com/user-attachments/assets/cb5bd3eb-299f-49e7-9a20-a5660607b40b)
  - При нажатии на кнопку архивировать кружок слева от картинки товара становится безцветным
  - ![image](https://github.com/user-attachments/assets/2b2e0172-9ac4-4b95-bd17-ffb8b5e45cec)
  - При нажатии на чекбокс данного товара теперь вместо кнопки архивировать появляется кнопка восстановить
  - При нажатии на кнопку восстановить кружок слева от картинки товара снова становится зеленым

- При нажатии на товар из таблицы открывается окно с информацией о товаре

### Группы 
![image](https://github.com/user-attachments/assets/fc99bb75-b8c3-4659-9ca1-7fd3cf411488)
#### Создать группу
- При нажатии на кнопку создать группу появляется выпадающий список с двумя вариантами вариантами:
  - При нажатии на "использовать фильтры" появляется окно создание новой группы товаров с помощью фильтров
    - ![image](https://github.com/user-attachments/assets/1d45acc7-a180-4621-b5db-3840d5c9496c)
    - При нажатии на кнопку добавить фильтр появляется новый фильтр в списке фильтров
    - При применении фильтров меняется список товаров в соответствии с фильтрами
    - При нажатии на товар из таблицы открывается окно с информацией о товаре
    - При нажатии кнопки сохранить новая группа появляется в списке
    - При попытке сохранить группу с уже существующим названием появляется сообщение об ошибке
      - ![image](https://github.com/user-attachments/assets/da2f70cc-1ec4-49e2-ac1b-caea7819f3af)
  - При нажатии на "выбрать товары вручную" появляется окно создание новой группы товаров вручную
    - ![image](https://github.com/user-attachments/assets/cbe89ef5-9b85-4b4f-9a31-5ca17ac306c6)
    - При нажатии на кнопку добавить списком появляется модальное окно
      - ![image](https://github.com/user-attachments/assets/ed1c768f-16ee-4883-99fc-4aacbf26d112)
      - При указании правильных ID ставятся чекбоксы напротив выбранных товаров в таблице
      - При указании несуществующих ID ничего не происходит
      - При нажатии кнопки сохранить новая группа появляется в списке
      - При попытке сохранить группу с уже существующим названием появляется сообщение об ошибке

- При нажатии на кнопку рекламировать открывается страница кампаний
- Кнопка редактировать и троеточие становится активной только при выборе какой либо группы, если выбраны все товары она неактивна
  - ![image](https://github.com/user-attachments/assets/110ef4ef-c81e-4c69-8d44-ba1308d4566b)
- При нажатии на кнопку редактировать открывается окно редактирования группы, ее функционал аналогичен окну [создание группы](#создать-группу)
- При нажатии на троеточие появляется список с тремя вариантами:
  - ![image](https://github.com/user-attachments/assets/15093f7d-a68d-43ae-a512-75910b970d04)
  - При нажатии на кнопку поделиться группой появляется модальное окно "открыть доступ"
    - ![image](https://github.com/user-attachments/assets/88372fff-7555-45b2-92f1-3c747c109f74)
    - При введении несуществующего ID кабинета появляется сообщение об ошибке
    - При выборе варианта "каталог и выбранные группы" появляется форма поиска группы и выпадает список созданных групп
      - ![image](https://github.com/user-attachments/assets/0167b32b-1125-4c12-85e8-047048b664ca)
  - При нажатии на кнопку "создать похожую группу" появляется окно создание группы, ее функционал аналогичен окну [создание группы](#создать-группу)
  - При нажатии на кнопку удалить группу появлятеся модальное окно удаления группы. При удалении группы она пропадает из списка
  - При нажатии на товар из таблицы открывается окно с информацией о товаре
  
### Диагностика
![image](https://github.com/user-attachments/assets/733e7d1a-eab0-4b11-8d2c-814639ec8e73)

- Если нет ошибок то на экране будет надпись все хорошо
- Если есть ошибки, то на экране будут элементы:
  - Кнопка "Скачать полный отчет"
  - Кнопка "Проверить снова"
  - Выпадающий список "Тип ошибки" с типом проблем
- ![image](https://github.com/user-attachments/assets/a5913611-d279-441e-a8b8-98c5ea77af27)
- При нажатии на кнопку "Скачать полный отчет" скачивается отчет
- Кнопка "Проверить снова" будет недоступна, если каталог был на проверке не позже часа назад
  - ![image](https://github.com/user-attachments/assets/17615d42-224e-454e-a77e-8e8f51d4cba0)
- При нажатии на кнопку "Тип ошибки" появляется список с фильтрами
  - При нажатии на любой пункт список ошибок меняется согласно выбранному фильтру


 
### События

### История загрузок 
- При нажатии на кнопку "обновить файл" появляется модальное окно ["настройки каталога"](#добавить-товар)
- В таблице ниже содержиться список со всеми обновлениями каталога

----
Сайты
---

![image](https://github.com/user-attachments/assets/ca7625d7-ba0c-47c5-81d9-bb3c047301ff)
- Если у пользователя нет привязанных пикселей трекинга, то экран будет представлять собой информацию о создание пикселя и кнопка "добавить пиксель"
  - При нажатии на кнопку добавить пиксель появляется модальное окно "добавление пикселя"
  - ![image](https://github.com/user-attachments/assets/a53479b4-7384-4c4c-b2ae-783adf8d153f)
  - При введении валидных данных появится модальное окно с информацией о созданном пикселе
    - Валидны любые данные формата **example.ru**, даже если это несуществующий сайт по типу a.aaa, он все равно добавится в список пикселей
    - ![image](https://github.com/user-attachments/assets/edc6c59c-c663-4600-b43c-af6eda25bd34)
  - ![image](https://github.com/user-attachments/assets/6ac7999f-d7e2-4786-837a-af3966ffe338)

![image](https://github.com/user-attachments/assets/819c1d5f-44e1-4eec-aec7-a66e0dc8eab4)
- Если у пользователя есть привязанные пиксели трекинга, то будет отображаться таблица с пикселями
  - При нажатии на троеточие появляется окно с кнопками "переименовать" и "удалить пиксель"
    - При нажатии на кнопку "переименовать" открывается модальное окно "изменить название пикселя"
    - ![image](https://github.com/user-attachments/assets/0e92cebb-ba1a-401d-8559-0d217be92f75)
    - Если поменять название и нажать на кнопку изменить, название пикселя поменяется в таблице
    - Если не менять название пикселя и нажаить на кнопку изменить, ничего не изменится
    - Если нажать на кнопку отмена, модальное окно закроется

----
Мобильные приложения
---
![image](https://github.com/user-attachments/assets/c494476d-2f35-46d5-93df-e200d4a7d973)
- Если у пользователя нет привязанных мобильных приложений, то экран будет представлять собой информацию о мобильных приложениях и кнопку "добавить приложение"
  - При нажатии на кнопку "добавить приложение" появляется модальное окно "привязка приложения"
    - При нажатии на крестик модальное окно закрывается
    - ![image](https://github.com/user-attachments/assets/a2c38e6d-e935-4241-a2e7-fcbe87dbb427)
    - При введении валидной ссылки на приложение появляется модальное окно с информацией о добавляемом приложении
      - ![image](https://github.com/user-attachments/assets/c662f761-53ea-4daf-8173-03b98e739d82)
      - При нажатии на кнопку "копировать" появляется тост с текстом "Код скопирован"
      - При нажатии на ссылку с именем приложения открывается страница с приложением
      - При нажатии на ссылку "как настроить приложение в трекере" открывается страница [инструкции](https://ads.vk.com/help/articles/integration_tracker)
      - При нажатии на крестик модальное окно закрывается
- После добавления приложения оно появляется в списке приложений
  = ![image](https://github.com/user-attachments/assets/5da6071c-4dc6-42ae-8403-f106ff826024)
- При нажатии на кнопку "фильтр" появляется баннер с чекбоксами, надписью выбрать все и кнопками "применить" и "отмена"
  - ![image](https://github.com/user-attachments/assets/08f91cc4-4b3e-4568-ada7-b7d9abf7912c)
  - При нажатии на кнопку отмена баннер закрывается
  - При нажатии на кнокпку "выбрать все", выбираются все чекбоксы и надпись меняется на "сбросить"
  - При нажатии на чекбокс надпись "выбрать все" также меняется на "сбросить"
  - При нажатии на кнопку "применить" без выбранных чекбоксов баннер закрывается и список приложений остается прежним
  - При нажатии на кнопку "применить" с выбранными чекбоксами баннер закрывается и в списке отображаются приложения, соответствующие выбранным фильтрам

----
Лид-формы и опросы
---

## Лид-формы
- Если у пользователя нет лид форм, то экран представляет собой информацию о лид-формах и кнопку "создать лид-форму"
  - ![image](https://github.com/user-attachments/assets/bf94fbf2-3dfa-42bb-b596-645bf41949cc)
  - При нажатии на кнопку "создать лид-форму" появляется окно создания новой лид-формы
 
### Создание лид-формы
### Оформление 
![image](https://github.com/user-attachments/assets/04a6f0d3-56b6-42e9-8c50-b3045af38662)
- При выборе пункта создать лендинг пропадают пункты "логотип" и "название компании", появляется кнопка редактировать
  - ![image](https://github.com/user-attachments/assets/31e89283-c3a1-461b-bab4-71f79dbbadc9)
  - При нажатии на кнопку редактировать открывается окно "конструктор лендинга"
- При нажатии кнопки продолжить без заполненных полей "логотип", "название компании", "заголовок" и "описание формы" появляется подпись обязательное поле
  - ![image](https://github.com/user-attachments/assets/4d69b6ec-9cff-42d4-9837-dec0bf542165)
- При переключении пункта "первый экран формы" из положения "компактный" в положение "больше текста" меняется пункт "описание формы". Вместимость поля в описании увеличивается с 35 до 350
- При переключении пункта "первый экран формы" в положение "лид-магнит" пункт с описанием меняется на пункты "тип вознаграждения" и "размер скидки". Также меняется оформление шаблона справа
  - ![image](https://github.com/user-attachments/assets/a2203769-5459-4d2a-a434-7a9a7c33d94e)
  - ![image](https://github.com/user-attachments/assets/7da8b07b-0c0d-4241-817d-592c0cc783f2)
  - Если в пункте "тип вознаграждения" выбрать подпункт "скидка" и записать 0 в размер скидки появляется подпись "значение должно быть больше нуля"
    - ![image](https://github.com/user-attachments/assets/b3445c74-30c9-40a4-91d8-b1289cff54b1)
    - При указании скидки больше 100, появится подпись "укажите скидку не больше 100%"
      - ![image](https://github.com/user-attachments/assets/7a065733-4f7d-40a2-8630-493ce8ec4a68)
  - Если в пункте "тип вознаграждения" выбрать подпункт "бонус" и затем нажать кнопку продолжить без заполненного описания бонуса, появится подпись "обязательное поле"
    - ![image](https://github.com/user-attachments/assets/2775d3ac-ddb3-42f9-a5d5-048956ff6700)
- При нажатии на кнопку "продолжить" со всеми корректно заполненными полями откроется раздел "Вопросы"
### Вопросы
![image](https://github.com/user-attachments/assets/130207da-4d59-4cb3-8f50-e49e6dd1a66b)
- При нажатии кнопки "добавить вопрос" появляется форма добавления вопроса и ответов к нему
  - ![image](https://github.com/user-attachments/assets/7696bb69-a1f0-4e35-b197-5a990bd8bf64)
  - Если нажать кнопку продолжить с незаполненным вопросом, то окно вопроса станет красным и появится поп ап при наведении на восклицательный знак
    - ![image](https://github.com/user-attachments/assets/69833f72-3e29-417b-90cd-faeb46046bbc)
  - При выборе какого либо пункта в выпадающем списке "тип вопроса", меняется оформление в шаблоне справа
  - При выборе пункта "ответ в произвольной форме" в выпадающем списке "тип вопроса", форма вопроса меняется
    - ![image](https://github.com/user-attachments/assets/cc132acb-e957-4fd4-825b-7f4e4d510add)
  - При нажатии кнопки добавить ответ появится еще одно поле для добавления ответа
  - При нажатии на кнопку "ответ из шаблона" появится список. При выборе любого пункта из списка он появится как дополнительный ответ на вопрос
    - ![image](https://github.com/user-attachments/assets/c30276d1-3811-4df6-8350-cdd5975903c4)
- При нажатии на кнопку удаления одного из вариантов контактной информации он пропадает из списка и из шаблона справа
- При нажатии на кнопку "добавить контактные данные" появляется модальное окно "контактная информация"
  - ![image](https://github.com/user-attachments/assets/775faa9d-78cf-4063-a1d1-9cfabe801bcd)
  - При выборе каких либо пунктов и нажатии на кнопку добавить эти пункты появляются в списке контактной информации
- При нажатии на кнопку "продолжить" со всеми корректно заполненными полями откроется раздел "Результат"
### Результат
![image](https://github.com/user-attachments/assets/ab4d2f03-c622-4ce2-9900-13c5abe31955)
- При нажатии на кнопку продолжить с незаполненным полем "Заголовок" появится подпись "Обязательное поле"
  - ![image](https://github.com/user-attachments/assets/bc13c4a9-ff26-404e-91dc-a71bbdb1baf5)
- При нажатии на кнопку "добавить сайт" появится поле "ссылка на сайт"
  - При наведении на знак вопроса рядом с подписью поля "ссылка на сайт" появится поп ап с информацией
  - ![image](https://github.com/user-attachments/assets/6fb8d9be-c39d-44ef-b17b-12e2d55f5606)
  - При введение невалидных данных появится подпись с информацией
    - Валидны любые данные формата **https://example.com**. Однако если указать ссылку на несуществующий сайт, то при нажатии на кнопку далее ничего не произойдет.
  - ![image](https://github.com/user-attachments/assets/98a4e545-fba7-4941-93fe-283f59859db9)
- При нажатии на кнопку "добавить телефон" появится поле "телефон для заказа"
  - При введение некорректных данных появится подпись с информацией
  - ![image](https://github.com/user-attachments/assets/33342bb2-bfd5-4cf3-8768-d14cf9492c99)
- При нажатии на кнопку "добавить промокод" появится поле "промокод"
  - При наведении на знак вопроса рядом с подписью поля "ссылка на сайт" появится поп ап с информацией
  - ![image](https://github.com/user-attachments/assets/857de1ff-4575-4c55-95f7-4ef26cce7ab0)
- При нажатии на кнопку "продолжить" со всеми корректно заполненными полями откроется раздел "Настройки"
### Настройки
![image](https://github.com/user-attachments/assets/fff320f5-91a6-4371-aa06-ca3055006fa8)
- При выборе чекбокса "Уведомлять о новых заявках по email" появится поле для ввода email
  - При введение некорректных данных появится подпись о невалидном email
  - ![image](https://github.com/user-attachments/assets/746d1a93-f215-49b0-aed2-715255d2adf2)
- При выборе чекбокса "Обязательные вопросы" появится модальное окно
  - ![image](https://github.com/user-attachments/assets/dff5af0a-9881-4676-8d0d-6d984daee48c)
  - При нажатии на кнопку "Да" чекбокс выберется
- При нажатии на кнопку продолжить с незаполненными полями "Юридическое название" и "Юридический адрес" появится подпись "Обязательное поле"
- При нажатии на кнопку "продолжить" со всеми корректно заполненными полями лид-форма появится в разделе "Лид-формы"
  - ![image](https://github.com/user-attachments/assets/f1510da7-b7b7-47bb-9e0d-d8b2d6596d6c)
## Опросы
- Окно с созданием опроса аналогично окну создания лид-формы

----
Помощь
---
![image](https://github.com/user-attachments/assets/b11f181d-5720-4798-bc74-247bd0892643)
- При нажатии на Заголовок "VK Реклама" открывается страница с мессенджером ВК
- При нажатии на значок ![image](https://github.com/user-attachments/assets/5682b15e-6af2-4e72-8583-041c3558fe80) происходит открытие страницы чата "VK Реклама"
- При нажатии на троеточие появляется окно с кнопками "Go to community" и "Sign out of VK account"
  - ![image](https://github.com/user-attachments/assets/af166afc-54e5-43b5-ac18-4c021e328bb9)
  - При нажатии на кнопку "Go to community" происходит открытие страницы паблика "VK Реклама"
- При нажатии на кнопку с крестиком проихсодит закрытия окна с чат ботом
- При наведении курсора на аватар появляется поп ап с именем пользователя
  - ![image](https://github.com/user-attachments/assets/f0b412b8-24f5-4921-af31-8fd40614a9a2)
- При наведении курсора на значок плюса появляется баннер с выбором формата файла.
- При нажатии на кнопку отправить без введенного текста ничего не происходит
- При нажатии на кнопку отправить с введенным текстом кнопка меняет свой цвет на синий и отправленное сообщение отображается в окне чата
  - ![image](https://github.com/user-attachments/assets/19d99ad2-869c-4028-9186-1e1a836be983)


