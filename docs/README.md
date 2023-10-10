# Ссылки на блоки
- [Общее описание решения](#общее-описание-решения)
- [Описание функций](#описание-функций)
  - [Circle](#circle)
    - [import math](#import-math)
    - [def area(r)](#def-arear)
    - [def perimetre(r)](#def-perimetrer)
  - [Rectangle](#rectangle)
    - [def area(a,b)](#def-areaab)
    - [def perimetre(a,b)](#def-perimetreab)
  - [Sqare](#square)
      - [def area(a)](#def-areaa)
      - [def perimetre(a)](#def-perimetrea)
  - [Triangle](#triangle)
      - [def area(a,h)](#def-areaah)
      - [def perimetre(a,b,c)](#def-perimetreabc)
- [История изменения проекта](#история-изменения-проекта)
  - [1 commit](#1-commit)
  - [2 commit](#2-commit)
  - [3 commit](#3-commit)
  - [4 commit](#4-commit)
  - [5 commit](#5-commit)
  - [6 commit](#6-commit)
  - [7 commit](#7-commit)
  - [8 commit](#8-commit)
  - [9 commit](#9-commit)
  - [10 commit](#10-commit)
  - [11 commit](#11-commit)
  - [12 commit](#12-commit)
  - [13 commit](#13-commit)
  - [14 commit](#14-commit)
  - [15 commit](#15-commit)
# Общее описание решения
1. Создаем директорию на компьютере и клонируем исходный репозиторий с помощью команды **git clone**.
2. Переходим в репозиторий и создаем новую ветку *new_v_413079*
   c помощью команды **git branch**
3. Создаем новый файл **rectangle.py** с кодом для вычисления площади и периметра прямоугольника. Добавляем файл в индекс с помощью команды **git add**.
4. Создаем коммит с помощью команды **git commit -m**, который содержит информацию о добавлении нового файла **rectangle.py**.
5. Создаем новый файл **triangle.py** с кодом для вычисления площади и периметра треугольника. Добавляем файл в индекс с помощью команды **git add**.
6. Исправляем ошибку в вычислении периметра прямоугольника в файле **rectangle.py** и добавляем изменения в индекс с помощью команды **git add**.
7. Создаем коммит с помощью команды **git commit -m**, который содержит информацию о добавлении нового файла **rectangle.py**.
8. Показываем граф всего репозитория с однострочным выводом коммитов с помощью команды **git log --graph --oneline --all**.
9. Показываем граф истории текущей ветки с однострочным выводом коммитов с помощью команды **git log --graph --oneline**.
10. Показываем изменения, внесенные в последние два коммита, используя хеши коммитов, с помощью команды **git show**.
11. Переходим в главную ветку *main* с помощью команды **git checkout main** и сливаем ветку *new_v_413079* в ветку *main* с помощью команды **git merge**.
12. Для создания **Pull Request** я сначала форкнул репозиторий товарища, затем склонировал его на свой компьютер. Создал новую ветку, внес изменения в репозиторий, добавив новый файл **ball.py**.<br> Зафиксировал изменения в индексе, сделал коммит и отправил их на свой репозиторий. Затем на **GitHub** я создал **Pull Request** для товарища, предварительно обсудив его изменения с ним, и дождался принятия.
13. Удалил ветку *new_v_413079* c помощью команды **git branch -d new_v_413079**
# Описание функций
## Circle
### import math
- **Подключаем библеотеку math**
### def area(r)
  - **Описание функции**: Функция получет на вход радиус круга и выводит его площадь.
  - **Параметры, задающиеся пользователем**: *r* типа (**float**) - радиус круга.
  - **Возвращаемое значение**: (*math.pi * r * r*) типа (**float**) - площадь круга.
  - **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 2
    - 2. **Выходные данные**: *output*:  12,56637061435917 
### def perimetre(r)
- **Описание функции**: Функция получет на вход радиус круга и выводит длину окружности.
- **Параметры, задающиеся пользователем**: *r* типа (**float**) - радиус круга.
- **Возвращаемое значение**: (*2 * math.pi * r*) типа (**float**) - длина окружности.
- **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 2
    - 2. **Выходные данные**: *output*:  12,56637061435917
## Rectangle
### def area(a,b)
- **Описание функции**: Функция получет на вход стороны прямоугольника и выводит его площадь.
- **Параметры, задающиеся пользователем**: 
  - 1. *a* типа (**float**) - сторона прямоугольника.
  - 2. *b* типа (**float**) - сторона прямоугольника.
- **Возвращаемое значение**: (*a* * *b*) типа (**float**) - площадь прямоугольника.
- **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 2.7, 3ю9
    - 2. **Выходные данные**: *output*:  10,53
### def perimetre(a,b)
- **Описание функции**: Функция получет на вход стороны прямоугольника и выводит его периметр.
- **Параметры, задающиеся пользователем**: 
  - 1. *a* типа (**float**) - сторона прямоугольника.
  - 2. *b* типа (**float**) - сторона прямоугольника.
- **Возвращаемое значение**: (*2* * (*a* + *b*)) типа (**float**) - периметр прямоугольника.
- **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 2.7, 3.9
    - 2. **Выходные данные**: *output*:  13.2
## Square
### def area(a)
- **Описание функции**: Функция получет на вход сторону квадрата и выводит его площадь.
- **Параметры, задающиеся пользователем**: *a* типа (**float**) - сторона квадрата.
- **Возвращаемое значение**: (*a* * *a*) типа (**float**) - площадь квадрата.
- **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 2.2
    - 2. **Выходные данные**: *output*:  4.84
### def perimetre(a)
- **Описание функции**: Функция получет на вход сторону квадрата и выводит его периметр.
- **Параметры, задающиеся пользователем**: *a* типа (**float**) - сторона квадрата.
- **Возвращаемое значение**: (*4* * *a*) типа (**float**) - периметр квадрата.
- **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 2.2
    - 2. **Выходные данные**: *output*:  8.8
## Triangle
### def area(a,h)
- **Описание функции**: Функция получет на вход сторону треугольника и высоту, проведенную к ней, и выводит его площадь.
- **Параметры, задающиеся пользователем**:
    - 1. *a* типа (**float**) - сторона треугольника.
    - 2. *h* типа (**float**) - высота, проведенная к заданной стороне.
- **Возвращаемое значение**: (*a * h / 2*) типа (**float**) - площадь треугольника.
- **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 3.2, 4.1
    - 2. **Выходные данные**: *output*:  6.56
### def perimetre(a,b,c)
- **Описание функции**: Функция получет на вход стороны треугольника и выводит его периметр.
- **Параметры, задающиеся пользователем**:
    - 1. *a* типа (**float**) - сторона треугольника.
    - 2. *b* типа (**float**) - сторона треугольника.
    - 3. *с* типа (**float**) - сторона треугольника.
- **Возвращаемое значение**: (*a + b + c*) типа (**float**) - периметр треугольника.
- **Примеры работы программы**:
    - 1. **Входные данные**: *input*: 2.7, 3.9, 4.2
    - 2. **Выходные данные**: *output*:  10.8
# История изменения проекта
## 1 commit
commit 8ba9aeb3cea847b63a91ac378a2a6db758682460<br>
Author: smartiqa <info@smartiqa.ru><br>
Date:   Thu Mar 4 14:54:08 2021 +0300<br>

    L-03: Circle and square added
## 2 commit
commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 (new_413079)<br>
Author: smartiqa <info@smartiqa.ru><br>
Date:   Thu Mar 4 14:55:29 2021 +0300<br>

    L-03: Docs added
## 3 commit
commit 15f6f6101c91bb59c49c4fac42948e90f1f70911<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Sat Sep 23 14:12:48 2023 +0300<br>

    new file was added
## 4 commit
commit ce7539dcbcf5908a4941e95540562d2c72fbf4cf (origin/main, origin/HEAD)<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Sat Sep 23 14:22:34 2023 +0300<br>

    error was fixed in rectangle.py
## 5 commit
commit e830c9d8d706c370658879613d8bd90f2dd771b5<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:27:56 2023 +0300<br>

    added a description of the functions in the file circle.py
## 6 commit
commit d13b2653db95b15dd85787d10559255826cd3242<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:32:23 2023 +0300<br>

    a folder has appeared
## 7 commit
commit a6429847fcc737593a2e1f5269402bbd1b498d03<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:38:44 2023 +0300<br>

    added a description of the functions in the file rectangle.py
## 8 commit
commit 0afcaace7b5251b98118c5b98b5e73981175c5d8<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:42:32 2023 +0300<br>

    added a description of the functions in the file square.py
## 9 commit
commit b4dfeee8f97f26a9405649c32c4e1d38b6730efb<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:47:01 2023 +0300<br>

    added a description of the functions in the file triangle.py
## 10 commit
commit cd686593a5b8ffcf4d6827138bc59a3fe14ffa0b (HEAD -> main)<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:48:47 2023 +0300<br>

    commit changes in .idea
## 11 commit
commit d13b2653db95b15dd85787d10559255826cd3242<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:32:23 2023 +0300<br>

    a folder has appeared
## 12 commit
commit a6429847fcc737593a2e1f5269402bbd1b498d03<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:38:44 2023 +0300<br>

    added a description of the functions in the file rectangle.py
## 13 commit
commit 0afcaace7b5251b98118c5b98b5e73981175c5d8<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:42:32 2023 +0300<br>

    added a description of the functions in the file square.py
## 14 commit
commit b4dfeee8f97f26a9405649c32c4e1d38b6730efb<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:47:01 2023 +0300<br>

    added a description of the functions in the file triangle.py
## 15 commit
commit cd686593a5b8ffcf4d6827138bc59a3fe14ffa0b (HEAD -> main)<br>
Author: Akim <akim.susulin@bk.ru><br>
Date:   Tue Oct 10 20:48:47 2023 +0300<br>

    commit changes in .idea