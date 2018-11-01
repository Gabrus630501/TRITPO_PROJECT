[Glossary](https://github.com/kirillstasiuk/TRITPO_PROJECT/blob/master/documets/Glossary.md) <br>

1. [Use Case Diagram](#1) <br>
	1.1. [Actors](#1.1) <br> 
	1.2. [Use Cases](#1.2) <br>
		1.2.1. [Добавить статью](#1.2.1) <br>
		1.2.2. [Редактировать статью](#1.2.2) <br>
    1.2.3. [Удалить статью](#1.2.3) <br>
    1.2.4. [Поиск](#1.2.4) <br>
    1.2.5. [Изменение цветовой гаммы](#1.2.5) <br>
    1.2.6. [Изменение требуемой валюты](#1.2.6) <br>
 2. [Activity Diagram](#2) <br>
 3. [State Diagram](#3) <br>
 4. [Sequence Diagram](#4) <br>
 5. [Class Diagram](#5) <br>
 6. [Deployment Diagram](#6) <br>

# 1. Use Case Diagram <a name = "1"></a>

Use case diagram is [here](https://github.com/kirillstasiuk/TRITPO_PROJECT/blob/master/documets/diagrams/Use%20case.png).

## 1.1 Actors <a name = "1.1"></a>

Actor | Desription
:-----|:----------
User  | объект использующий приложение


## 1.2 Use Cases <a name = "1.2"></a>

### 1.2.1 Добавить статью <a name = "1.2.1"></a>

**Description**: Пользователь нажимает кнопку "Add", после чего ему становится доступно добавление записи и изображения. 
Flow of events: 

1. Открывается новое активити на котором пользователю становится доступно добаление статьи;
2. При нажатие на кнопку "Add", открывается окно ввода;
3. Сохранение статьи;
4. Конец.

### 1.2.2 Редактировать статью <a name = "1.2.2"></a>

**Description**: Пользователь выбирает существующую запись и редактирует ее содержимое.
Flow of events: 

1. Открывается новое активити на котором пользователю становится доступно изменение статьи;
2. При нажатие на кнопку "Correct", открывается окно ввода с уже имеющимся текстом;
3. Сохранение статьи;
4. Конец.

### 1.2.3 Удалить статью <a name = "1.2.3"></a>

**Description**: Пользователь выбирает существующую запись и удаляет ее.
Flow of events: 

1. Открывается новое активити на котором пользователю становится доступно удаление статьи;
2. При нажатие на кнопку "Delite", выскакивает окно с подтверждением действия;
3. При подтверждении удаления, статья пропадает с активити;
4. Конец.

### 1.2.4 Поиск <a name = "1.2.4"></a>

**Description**: Пользователь ищет запись по дате. 
Flow of events: 

1. Пользователь вводит дату;
2. Система ищет нужную дату и отображает существующую запись;
3. Конец.

### 1.2.5 Изменение цветовой гаммы <a name = "1.2.5"></a>

**Description**: Пользователь заходит в настройки и изменяет оформление. 
Flow of events: 

1. В пункте "Settings", пользователь выбирает нужный пункт;
2. Конец.

### 1.2.6 Изменение требуемой валюты <a name = "1.2.6"></a>

**Description**: Пользователь заходит в настройки и изменяет валюту.
Flow of events: 

1. В пункте "Settings", пользователь выбирает нужный пункт
2. Конец.
 

# 2. Activity Diagram <a name = "2"></a>

Когда пользователь вводит требуемую ему дату, программа проверяет: "Есть ли на эту дату записи". Если есть, то выводит статью, если нет - экран остается пустым

Activity diagram is [here](https://github.com/kirillstasiuk/TRITPO_PROJECT/blob/master/documets/diagrams/Activity.png).


# 3. States Diagram <a name = "3"></a>

State diagram is [here](https://github.com/kirillstasiuk/TRITPO_PROJECT/blob/master/documets/diagrams/StateDiagram.png).


# 4. Sequence Diagram <a name = "4"></a>

Sequence diagram is [here](https://github.com/kirillstasiuk/TRITPO_PROJECT/blob/master/documets/diagrams/Sequence.png).


# 5. Class Diagram <a name = "5"></a>

Sequence diagram is [here](https://github.com/kirillstasiuk/TRITPO_PROJECT/blob/master/documets/diagrams/ClassDiagram.jpg).


# 6. Deployment Diagram <a name = "6"></a>

Sequence diagram is [here](https://github.com/kirillstasiuk/TRITPO_PROJECT/blob/master/documets/diagrams/DeploymentDiagram.png).

