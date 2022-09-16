[< к содержанию](./readme.md)

В состав Git входит утилита `git config`, которая позволяет просматривать и настраивать параметры, контролирующие все аспекты работы Git, а также его внешний вид.

`git config --list --show-origin`

**Примеры использования**

*Задание имени пользователя и адреса электронной почты*

`git config --global user.name "Ivan Volosnikov"`

`git config --global user.email volivant@yandex.ru`

*Выбор текстового редактора*

`git config --global core.editor "code --wait"`


