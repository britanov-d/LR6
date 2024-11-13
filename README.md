# LR6
## __Лабораторная работа №6__
### __Система контроля версий__
_Цель лабораторной работы_: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

# Ход выполнения лабораторной работы
> Скриншоты выполнения лабораторной работы находятся в папке screenshots, для каждого пункта создан отдельный скриншот, соответствующий этапу задания. Пример, скриншот для пункта 1 соответственно имеет название _1.png_
## Пункт 1
Нужно создать аккаунт на сайте GitHub (_см. [рис. 1](https://github.com/britanov-d/LR6/blob/Report/screenshots/1.png)_). 
## Пункт 2
Для нажимаем Fork на странице репозитория[репозитория лабораторной работы](https://github.com/Kurtyanik/LR6/), создаётся копия в личное хранилище (_см. [рис. 2](https://github.com/britanov-d/LR6/blob/Report/screenshots/2.png)_).
## Пункт 3
Соглано лабораторной работе, необходимо установить Git, в нашем случае это Git Bash (_см. [рис. 3](https://github.com/britanov-d/LR6/blob/Report/screenshots/3.png)_).
## Пункт 4
Далее с помощью _git config --global user_name_ и _git config --global user_email_ был настроен клиент git (_см. [рис. 4](https://github.com/britanov-d/LR6/blob/Report/screenshots/4.png)_).
## Пункт 5
Далее в корневой папке Git Bash была создана копия своего личного удалённого репозитория (_см. [рис. 5](https://github.com/britanov-d/LR6/blob/Report/screenshots/5.png)_).
## Пункт 6
Теперь нужно добавить файл через интерфейс GitHub и подтянуть изменения в локальный репозиторий. На скриншоте 6 (_см. [рис. 6](https://github.com/britanov-d/LR6/blob/Report/screenshots/6.png)_) представлены файлы, находящиеся в локальном репозитории, до обновленния данных и после. Их поиск осуществляется командой _ls -1_, а обновление информации - _git pull_.
## Пункты 7, 8
Следом необходимо получить историю операций для веток и просмотреть последние изменения. Первое осуществляется с помощью команды _git reflog branch_name_, а второе - с помощью команды _log_ (_см. [рис. 7](https://github.com/britanov-d/LR6/blob/Report/screenshots/7.png)_).
## Пункт 9
Затем нужно выполнить слияние в ветку master. С помощью команды _git merge branch_name_ ветки _master_ и _new_file_ были объединены (содержимое new_file появилось в ветке master, _см. [рис. 9](https://github.com/britanov-d/LR6/blob/Report/screenshots/9.png)_).
## Пункт 10
Следом удаляем побочную ветку. Для этого была использована команда _git branch -d branch_name_ (_см. [рис. 10](https://github.com/britanov-d/LR6/blob/Report/screenshots/10.png)_).
## Пункт 11
Для наглядной работы с репозиторием необходимо сделать изменения и зафиксировать их, оставляя комментарии. Поочередно в репозиторий были добавлены три текстовых файла: first_file, second_file, third_file, созданные командой _echo "text" >> name.txt_. Извенения фиксировались командой _git add_, для создания коммита - _git commit -m "text"_, для обновления информации в репозитории - _git push_ (_см. [рис. 11.1](https://github.com/britanov-d/LR6/blob/Report/screenshots/11.1.png); [рис. 11.2](https://github.com/britanov-d/LR6/blob/Report/screenshots/11.2.png); [рис. 11.3](https://github.com/britanov-d/LR6/blob/Report/screenshots/11.3.png)_).
## Пункт 12
С помощью _git revert HEAD --no-edit_ осуществлен откат коммита (_см. [рис. 12](https://github.com/britanov-d/LR6/blob/Report/screenshots/12.png)_).

# Лог команд
