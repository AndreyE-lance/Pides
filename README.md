# PIDES = Postgresql + IDE + Sql
I made an IDE for Postgresql to make it easier to work with this database. (+ Linux)

1) настройки открываются кнопкой с шестерёнкой в(C:\Users\Public\Documents\Pides\config.txt)
2) избранные таблицы, отмеченные галочкой, а также комментарии сохраняются в файл C:\Users\Public\Documents\Pides\favorite.txt
3) приложение сворачивается в трей (нажатие правой кнопки мыши на иконке в трее 
   вызывает меню с двумя командами Show и Close)
4) создана сплит панель с 2 таблицами: объекты базы данных (слева), содержимое объекта (справа)
5) возможно изменение прозрачности окна приложения
6) добавлена кнопка Refresh для обновления приложения после внесения изменений в файл конфигураций
7) добавлено окно ввода sql-запроса (пока выборка только из одной таблицы). Запуск - клавиша F9.
8) таблица слева:
    - показан список таблиц, вью и матвью
    - по двойному клику на имени объекта открывается содержимое объекта
    - при нажатии на значок суммы в строке отображается количество записей в таблице    
    - возможна сортировка в столбцах
    - при нажатии правой кнопкой мыши на заголовках копируется в clipboard: 
        1) имя конкретного заголовка
        2) все названия заголовков через запятую
        3) данные в конкретном столбце в виде столбца без запятой
    - добавлены checkbox для изменения списка объектов
    - возможность добавления комментариев по объекту
9) таблица справа
    - отображает строки выбранной слева таблицы (лимит строк задаётся в config.txt)
    - возможна сортировка в столбцах
    - контекстное меню по правой кнопке мыши на строке (копировать или удалить строку/строки)
    - двойной клик левой кнопкой мыши выделяет всю строку
    - при нажатии правой кнопкой мыши на заголовках копируется в clipboard: 
        1) имя конкретного заголовка
        2) все названия заголовков через запятую
        3) данные в конкретном столбце в виде строки: data1, data2, data3
        4) данные в конкретном столбце в виде столбца без запятой
        5) данные в конкретном столбце в виде выражения: in ('data1', 'data2', 'data3')
        
![Image alt](https://github.com/mrprogre/Pides/blob/master/gui.png)
