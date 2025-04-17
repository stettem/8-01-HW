# Домашнее задание к занятию "`Название занятия`" - `Гильмутдинов Владислав`

### Задание 1
1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).
2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
3. Склонируйте репозиторий, используя https протокол `git clone ...`.
![Название скриншота 1](https://github.com/stettem/8-01-HW/blob/555a915c305fb8213b2bd6b7e1aafd8a5f3a214f/img/1.png)`
4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.
6. Выполните команду git status и запомните результат.
![Название скриншота 2](https://github.com/stettem/8-01-HW/blob/860cc69b5d887a52b4496ef0aff293c9497b33b8/img/3.png)
7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
![Название скриншота 3](https://github.com/stettem/8-01-HW/blob/860cc69b5d887a52b4496ef0aff293c9497b33b8/img/4.png)
8. Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
![Название скриншота 4](https://github.com/stettem/8-01-HW/blob/860cc69b5d887a52b4496ef0aff293c9497b33b8/img/5.png)

Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
Ещё раз выполните команды git diff и git diff --staged.
Теперь можно сделать коммит git commit -m 'First commit'.
Сделайте git push origin master.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
