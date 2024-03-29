# ** Инстуркция по работе с системой контроля версий Git**

Общая информация про Гит

![Логотип](gitlogo.jpeg)

Git (произносится «гит») — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано.

## Инициализация репозитория

Чтобы инициализировать репозиторий нужно ввести команду:

    git init
## Проверка состояния репозитория

**Чтобы проверить состояние репозитория введи команду:**

    git status

## Добавление версионности

`Чтобы добавить версию введи команду:`

    git add

## Фиксация изменений

* Чтобы зафиксировать изменения репозитория введи команду:

    git commit -m


## Просмотр истории коммитов

*Чтобы просмотреть журнал изменений введи команду:*

    git log

## Переключение между версиями

* Чтобы перейти к предыдущей версии введи команду:

    git checkout

* Чтобы вернуться к актуальной версии введи команду:

    git checkout master
    
## Выход из отображения

>Чтобы выйти  из режима нажми "q"

## Разница между состояниями

~~Чтобы увидеть разницу между состояниями введи команду:~~

    git diff

## Ветвление в git

Ветвление в ГИТ позволяет нам работать параллельно с разными задачами в одном репозитории


## Создание новой ветки

Чтобы создать новую ветку используется команда

    git branch <имя ветки>

## Создание слияния веток

Чтобы слить одну ветку в другую нужно находясь на той ветке **куда** вливаем выполнить команду:

    git merge <имя вливаемой ветки>

## Удаление ветки

Чтобы удалить ненужную ветку необходимо ввести команду:

    git branch -d <имя ветки>

## Переход к другой ветке

Чтобы перейти из одной ветки в другую необходимо ввести команду:

    git checkout <имя ветки>

## Просмотр списка веток

Чтобы просмотреть список веток в репозитории необходимо ввести команду:

    git branch
    
## Просмотр историй коммитов кратко

Чтобы просмотреть краткую историю коммитов необходимо ввести команду:

    git log --graph --oneline --all

## Переход к другой ветке с помощью хэша

Чтобы перейти на другую ветку с помощью хэша введи команду:

    git checkout <символы хэша>

## Автоматическая индексация измнений

Чтобы сохранить файл с автоматической индексацией изменений введи команду:

    git commit -a

## Добавление картинок в ГИТ

Чтобы прикрепить картинку, необходимо добавить ее в репозиторий и проложить к ней путь в гит

    ![наименование картинки](путь)

## Удаленные репозитории

Удаленный репозиторий-это облачное хранилище файлов. Позволяет работать с проектом из любой точки мира
