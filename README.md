# Лабораторная работа №6

## 1. Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 

## 2. Ход работы
### Настройка клиента git
Для начала был настроен клиент git (Имя пользователя и email).

![Скриншот](/screenshots/4.png)

### Клонирование личного репозитория на свой компьютер
В заранее созданную папку клонируем репозиторий.

![Скриншот](/screenshots/5.png)

### Добавление нового файла
При помощи интерфейса GitHub создаем новый файл(add file --> create new file) new_file.

![Скриншот](/screenshots/6.png)

### Подтягивание изменений
Подтягиваем изменения в локальный репозиторий.

![Сркиншот](/screenshots/6_1.png)

### Получение истории операций для веток
Получим историю операций для каждой из веток(master, branch1).

![Скриншот](/screenshots/7.png)

### Просмотр последних изменений
Просмотрим последние изменения для каждой из веток(branch1, master).

![Скриншот](/screenshots/8.png)

### Слияние веток
Выполним слияние в ветку master. Изначально это сделать не получится, так как необходимо разрешить конфликт при слиянии. Разрешим конфликт в текстовом редакторе.

![Скриншот](/screenshots/9.png)

### Удаление побочной ветки
После успешного слияния удалим побочную ветку branch1.

![Скриншот](/screenshots/10.png)

### Изменения в файле
Сделаем неесколько изменений в созданном нами файле. Для каждого изменения сделаем коммит.

![Скриншот](/screenshots/11.png)

### Откат коммита
Сделаем откат последнего коммита.

![Скриншот](/screenshots/12.png)

### Создание новой ветки
При помощи интерфейса GitHub создадим новую ветку(report) для будущего отчёта.

![Скриншот](screenshots/13.png)

## 3. Лог команд
```
git config --global user.name "4319 Хмель Елизавета Алексеевна"
git config --global user.email "liza.xmel@mail.ru"
git config --global --list
git clone https://github.com/lizakhmel/LR6
git pull origin branch_name
git log --oneline
git checkout branch_name
git show
git merge branch_name
git status
git add
git commit -m "text"
git push origin --delete branch_name
git reset --hard 64a8e57
```
## 4. История операций в форматированном виде

![Скриншот](/screenshots/14.png)

## 5. Вывод
Изучила базовые возможности системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 
