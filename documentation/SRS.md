# Требования к проекту
## Содержание
1. [Введение](#P1)  
1.1. [Назначение](#P1.1)  
1.2. [Бизнес-требования](#P1.2)  
1.3. [Аналоги](#P1.3)  
2. [Требования пользователя](#P2)  
2.1. [Программные интерфейсы](#P2.1)  
2.2. [Характеристики пользователей](#P2.2)  
&nbsp;&nbsp;&nbsp;&nbsp;2.2.1. [Аудитория приложения](#P2.2.1)  
2.3. [Предположения и зависимости](#P2.3)  
3. [Системные требования](#P3)  
3.1. [Функциональные требования](#P3.1)  
&nbsp;&nbsp;&nbsp;&nbsp;3.1.1. [Основные функции](#P3.1.1)  
&nbsp;&nbsp;&nbsp;&nbsp;3.1.2. [Ограничения и исключения](#P3.1.2)  
3.2.3 [Требования к удобству использования](#P3.2.1.1)  
## <a name="P1">1. Введение</a>
### <a name="P1.1">1.1. Назначение </a>
Booking club - это десктопное приложение, представляющее собой удобный пользовательский интерфейс для ведения и учета дел реально существующего "Книжного клуба". Основной его задачей является фиксация участников клуба, учет списка книг, полученных ими от клуба, учет списка книг содержащихся в библеотеке клуба и учет книг внесенных в клуб каждым участником.
### <a name="P1.2">1.2. Бизнес-требования</a>
Приложение представляет собой окно для работы администратора клуба, на главной странице имеются две рабочие кнопки выбора, по которым администратор может перейти в меню работы с участниками клуба или же с ресурсами (книгами) клуба. При переходе в меню работы с участниками клуба, администратор обязан ввести свои данные для получения доступа к регистрации нового участника(нажатием кнопки "Ргистрация"), для этого он должен нажать на кнопку "Авторизация", так же пользователь может просмотреть список участников клуба. 
### <a name="P1.3">1.3. Аналоги</a>
Аналоги приложения отсутствуют, так как приложение заточено под нужды конкретного сообщества.
## <a name="P2">2. Требования пользователя</a>
### <a name="P2.1">2.1. Программные интерфейсы</a>
Приложение использует базу данных MySQL.
### <a name="P2.1">2.1.1 Программные интерфейсы</a>
Основное меню.<br>
![]( https://github.com/TheAntoshkaBy/Boking-Club/blob/master/documentation/diagrams/images/Booking_Club.jpg)<br>
Меню учета участников.
![](https://github.com/TheAntoshkaBy/Boking-Club/blob/master/documentation/diagrams/images/menuUsers.jpg)<br>
Меню регистрации.
![](https://github.com/TheAntoshkaBy/Boking-Club/blob/master/documentation/diagrams/images/registr.jpg)<br>
Меню авторизации.
![](https://github.com/TheAntoshkaBy/Boking-Club/blob/master/documentation/diagrams/images/autorize.jpg)<br>
Список участников.
![](https://github.com/TheAntoshkaBy/Boking-Club/blob/master/documentation/diagrams/images/usersList.jpg)<br>
Меню библиотеки.
![](https://github.com/TheAntoshkaBy/Boking-Club/blob/master/documentation/diagrams/images/menuBib.jpg)<br>
### <a name="P2.2">2.2. Характеристики пользователей</a>
#### <a name="P2.2.1">2.2.1. Аудитория приложения</a>
Пользователями являются администраторы/модераторы выше названного клуба.

| Класс пользователей | Описание |
|:---|:---|
| Главный администратор | Пользователь, являющийся владельцем рабочего пространства. Имеет доступ к полному функционалу. Имеет возможность удаления пользователей из канала, регистрации участников, изменения их данных и получения доступа ко всем данным клуба.

### <a name="P2.3">2.3. Предположения и зависимости</a>
Отсутсвуют.
## <a name="P3">3. Системные требования</a>
Прилоение является кроссплатформенным.
### <a name="P3.1">3.1. Функциональные требования</a>
Админимтратору предоставлены возможности:
  1. Подключение к базе данных
  2. Получение списка участников из базы данных
  3. Добавление новых участников в базу данных
  4. Просмотр книг в библиотеке
  5. Добавление новых книг в библиотеку
#### <a name="P3.1.1">3.1.1. Основные функции</a>
Запоминание, систематизация пользователей - участников клуба, распределение ресурсов клуба (библеотеки).
#### <a name="P3.1.2">3.1.2. Ограничения и исключения</a>
Для работы приложения требуется предустановленная на компьютере библиотека Java.
##### <a name="P3.2.3">3.2.3. Требования к удобству использования</a>
Приложение предоставляет всю нужную информацию сразу после загрузки. 
