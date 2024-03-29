# Проект, в которром я тренеруюсь использовать git и gitHub. Здесь будут размещены мои решения по практикам из курса. 

## Ссылка на материал курса:
[Яндекс.Практикум](https://practicum.yandex.ru/git-basics/?from=catalog) 

## Практическая работа №1. «Делимся проектом с миром»

### Задние:

Пришло время потренироваться!

На этом курсе вы поломаете голову над задачами из реальной практики работы с Git. Такие задачи ещё называют кейсами (от англ. case — «ситуация», «случай»).

Кейсы описывают контекст задачи и результат, который нужно получить, но не дают возможного решения — всё как в жизни.

Решение каждой задачи вам предстоит найти самостоятельно. Для этого опирайтесь на знания и навыки, полученные в предыдущих уроках или темах. Изучать что-то дополнительно не придётся.
Помните: иногда одну и ту же задачу можно решить несколькими способами. Постарайтесь применить изученный материал так, чтобы все его элементы сложились в цельную картину. Если вы что-то забыли, вернитесь к нужному уроку и повторите те места, которые вызвали трудности.

А теперь начнём!

Git — знание, которым хочется поделиться со всем миром! И такая возможность есть.
Представьте, что ваш коллега обратился к вам с просьбой. Он тоже хочет изучить Git, но не уверен, с чего начать. Реализуйте проект-помощник — самую удобную шпаргалку по работе с 

Git:
1. Создайте репозиторий.
2. Добавьте в репозиторий файл ``README.md`` и запишите в него всё, что уже знаете. Это могут быть: список команд и понятий по каждой из пройденных тем; инструкции по инициализации проекта, работе с коммитами и регистрации на GitHub или просто поурочные конспекты в свободной форме.
3. Загрузите получившийся репозиторий на GitHub и убедитесь, что локальная и удалённая версии идентичны.

----

Первым делом хочется рассказать о небольшой шпаргалке из самого курса. Думаю они все будут перечислены здесь: 

#### В первой ссылке описываются базовые команды в консоли для навигации и работы с файлами и папками. 
1. [Шпаргалка по работе с навигацией и работы с файлами и папками](https://practicum.yandex.ru/trainer/git-basics/lesson/fe0bcd71-f592-423b-bb81-27c37a6a115b/)

#### Во второй ссылке рассказывают о файле README.md и описываются возможности по работе с ним. 
2. [Шпаргалка по работе с файлами README.md](https://practicum.yandex.ru/trainer/git-basics/lesson/c6b9607c-e8bc-4446-89f9-c74522c3492f/)





##### Некоторые команды для навигации и работы с файлами и папками. 

* Часто использую `cd ...` для смены директорий. Можно использовать `cd` с продолжениес ввиде: 
1. `..` для перехода на уровень выше, в родительскую папку; 
2. `~` для перехода в домашнюю директорию (/Users/Username);
3. `/` для перехода в корневую директорию.

* `pwd` покажет в какой я папке;

* `ls` покажет файлы и папки в текущей папке;

* `touch ...` создаст файл index.html в текущей папке;

* `rm ...` удалит указанный файл;

##### Некоторые команды для работы с git.

* `git init` создаст репозиторий в текущей директории;

* `git status` покажет текущее состояние репозитория;

* `git add ...` подготовит файл к сохранению;

* `git commit` сделает коммит;

1. Ключ -m позволяет присвоить коммиту сообщение;

* `git log` покажет предыдущие коммиты;

* `git remote add` привяжет удалённый репозиторий к локальному;

* `git remote -v` поможет узнать связаны ли репозитории;

* `git push` отправит изменения на удалённый репозиторий;