# ТРПО

## Лабораторные работы git

Для начала изучить теоретический материал:

[основы работы с git](https://proglib.io/p/git-for-half-an-hour)

Порядок работы:

1. Создать аккаунт на github
2. Сделать fork этого репозитория. Для этого в интерфейсе github есть специальная кнопка справа вверху.
3. Склонировать репозиторий себе на компьютер (git clone https://github.com/[ваш_логин]/10.03.01.git). Если у вас еще не установлен git, то это надо сделать. Также полезен будет визуальный редактор вроде github desktop или tortoise git.
5. Создать свою папку в репозитории в формате имя.фамилия, например k.butin и в ней выполнять задания. Лучше использовать латинские символы.
6. Далее выполняете лабораторные работы в созданной папке с вашим именем.
   
**Обратите внимание, git init уже вызывать не нужно!**

Делайте коммиты как можно чаще. В качесте комментария можно указывать номер выполненного задания. Также не забывайте периодически загружать изменения на сервер командой git push. В случае совместной работы надо одним резпозиторием важно вызывать git pull каждй раз перед началом работы с проектом.

После выполнения всех заданий сделайте pull-реквест в исходный репозиторий.
Все задания выполняются в консоли. В windows лучше использовать git bash или powershell. Они поддерживают историю и дополнительный набор команд.

## Анализ качества кода

### Задания

* Установить инструмент анализа качества кода `pylint`.

* Проверить при помощи `pylint` код, расположенный
  [здесь](./dirty.py). Пояснить обнаруженные проблемы.

* **\*** Исправить код так, чтобы `pylint` ставил за него 10 баллов из
  10, чтобы не было ни одного замечания. Функциональность при этом не
  должна пострадать.

* **\*\*** Настроить `pylint` таким образом, чтобы использование имен
  переменных `x` и `y` не снижало оценку качества кода. Показать, что
  это работает.

### Ссылки

* [Pylint](https://www.pylint.org/)
* [Анализ кода в Python](https://python-scripts.com/code-analysis)

