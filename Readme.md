# Инструкция по работе с git

## Создание репозитория
Для того,чтобы доюавить версионность к созданной папке,и создать в ней локальный репозиторий,для этого нужно открыть окно терминала в этой папке и написать команду "git init". Тогда ваша папка станет репозиторием и в ней появится скрытая папка .git

## Добавление файлов в репозиторий
Добавить версионность к файлу,находящемуся в папке-репозитории,можно с помощью команды "git add".Пишется она следующим образом * git add (название файла)*


## Создание коммитов
Для создания коммита нужно выполнить команду *git commit -m "Текст коммита".* Где *m* от слова *message*.

## Просмотр истории коммитов
Для просмотра истории всех сделанных коммитов используется команда*git log*.Чтобы увидеть всю историю коммитов,в папке репозитория в терминале необходимо набрать *git log*. 

## Переключение между коммитами
Для того,чтобы переключаться между коммитами,необходимо использовать команду *git checkout (номер коммита)*.Номер коммита можно взять посмотрев список всех коммитов.

## Создание ветки
Для того,чтобы создать новую ветку,нужно в терминале набрать команду *git branch (имя ветки)*.

## Переключение между ветками
Чтобы переключаться между ветками,нужно ввести команду *git checkout (название ветки)*.

## Слияние веток
Для того,чтобы совместить ветки между с собой нужно находиться на главной ветке(чистовике) и в терминале ввести команду *git merge (имя той ветки(черновик),которую хотите объединить с главной веткой)*.

## Удаление веток
После слияния веток ненужные ветки удаляются.Для этого в терминале нужно ввести команду *git branch -d (наименование ветки)*.Где *d* от слова *delete*.