## Динамические формы

#### Задание условий для отображения полей
Для того чтобы задать список атрибутов, выводимых на форму, в зависимости от выбранного типа представления, нужно перейти в рабочей панели по кнопке «Представление». Кнопка доступна для сущностей, либо их атрибутов:

![14](docs/ru/system_folder/14.png)

Из списка выбора допустимых значений в поле `«Представление»` выбираем тип формы представления для класса: 

![15](docs/ru/system_folder/15.png) 

в соответствии с таблицей:

|Тип представления	|Назначение|
| ---------------- | ---------- |
|Список объектов	|обеспечивает вывод списка объектов указанного класса|
|Форма создания	|обеспечивает вывод формы создания объекта указанного класса|
|Форма изменения	|обеспечивает вывод формы изменения объекта указанного класса|

Далее отображается список всех атрибутов класса и область для формирования формы представления в соответствии с выбранным типом: 

![16](docs/ru/system_folder/16.png)

Двойным щелчком по наименованию атрибута открываем его форму редактирования, задаем для него свойства, значения которых указаны в [таблице](docs/ru/system_folder/table3.md), сохраняем форму и атрибут перемещается в область формирования формы представления:

![17](docs/ru/system_folder/17.png)

#### Способы группировки атрибутов на форме

##### Создание группы

Для создания группы атрибутов на форме необходимо выбрать действие `«Создать группу»` на рабочей панели, после чего откроется форма создания группы. Для данной формы доступно создание:
* Группа – Позволяет группировать атрибуты в рамках одной формы.
* Вкладка - Задаются в представлении создания и редактирования и используются для разбиения атрибутов класса по отдельным вкладкам на форме.

Заполняем обязательные поля и свойства группы для отображения их на форме представления атрибутов класса. Создаем форму создания группы. Далее на форме редактирования свойств атрибута `«Регион»` и `«Город»` задаем значение для свойства `«Группа»`:

![19](docs/ru/system_folder/19.png)

Теперь, в области формирования списка атрибутов для формы представления, отобразилась группа для атрибутов, присвоенных ей:

![20](docs/ru/system_folder/20.png)

##### Создание вкладки

Для создания вкладки выбираем тип формы представления для необходимого класса и открываем форму создания `«Группы»`, переключаем форму на `«Вкладка»` и заполняем ключевые поля и прочие свойства.

Далее открываем форму редактирования атрибутов текущего класса и для атрибутов, которые необходимо отобразить в созданной вкладке, в свойстве `«Группа»` из списка выбора допустимых значений выбираем необходимую вкладку по наименованию. Сохраняем форму, аналогично соотносим атрибуты класса по вкладкам и в результате видим отображение атрибутов по вкладкам в области формирования форм представления:

![23](docs/ru/system_folder/23.png)

#### Клонирование элементов

При необходимости размножить компоненты или группы приложения доступен функционал клонирования, который позволяет создавать копии необходимого компонента, либо группы компонентов для дальнейшего использования. 

Клонирование доступно для следующих компонентов Подсистемы:
* Сущность
* Бизнес-процесс (а также его состояния и переходы)
* Формы

Действия для клонирования компонентов системы:
1.	Выделяем компонент для клонирования
2.	На рабочей панели выбираем действие `«Клонировать»`:
![37](docs/ru/system_folder/37.png)
3.	После подтверждения действия открывается форма редактирования клонированного элемента, с добавлением префикса `«clone_»` для обязательных полей формы. При необходимости, заполняем остальные поля формы, сохраняем форму.
4.	Клонируемый компонент отобразился в текущей рабочей области, с добавлением префикса `«clone_»` в название:

![26](docs/ru/system_folder/26.png)