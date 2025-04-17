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
9. Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
![Название скриншота 5](https://github.com/stettem/8-01-HW/blob/d9b003ac5cb597b5c41f7bd20ced63bf29a1400c/img/6.png)
10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
![Название скриншота 6](https://github.com/stettem/8-01-HW/blob/d9b003ac5cb597b5c41f7bd20ced63bf29a1400c/img/7.png)
12. Ещё раз выполните команды git diff и git diff --staged.
![Название скриншота 7](https://github.com/stettem/8-01-HW/blob/d9b003ac5cb597b5c41f7bd20ced63bf29a1400c/img/8.png)
13. Теперь можно сделать коммит git commit -m 'First commit'.
![Название скриншота 8](https://github.com/stettem/8-01-HW/blob/d9b003ac5cb597b5c41f7bd20ced63bf29a1400c/img/9.png)
14. Сделайте git push origin master.
![Название скриншота 8](https://github.com/stettem/8-01-HW/blob/d9b003ac5cb597b5c41f7bd20ced63bf29a1400c/img/10.png)
![Название скриншота 9](https://github.com/stettem/8-01-HW/blob/d9b003ac5cb597b5c41f7bd20ced63bf29a1400c/img/11.png)
![Название скриншота 10](https://github.com/stettem/8-01-HW/blob/d9b003ac5cb597b5c41f7bd20ced63bf29a1400c/img/12.png)    
15. В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
https://github.com/stettem/8-01-Homework

### Задание 2
Что нужно сделать:

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
![Название скриншота 11](https://github.com/stettem/8-01-HW/blob/9f85f386a5e8a24bef1f39e1eafb5be6ede216a6/img/13.png)
![Название скриншота 12](https://github.com/stettem/8-01-HW/blob/9f85f386a5e8a24bef1f39e1eafb5be6ede216a6/img/14.png) 
2. Добавьте файл .gitignore в следующий коммит git add....
![Название скриншота 13](https://github.com/stettem/8-01-HW/blob/9f85f386a5e8a24bef1f39e1eafb5be6ede216a6/img/15.png)
3.Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
![Название скриншота 14](https://github.com/stettem/8-01-HW/blob/9f85f386a5e8a24bef1f39e1eafb5be6ede216a6/img/18.png)
4. Сделайте коммит и пуш.
![Название скриншота 15](https://github.com/stettem/8-01-HW/blob/9f85f386a5e8a24bef1f39e1eafb5be6ede216a6/img/16.png)
![Название скриншота 16](https://github.com/stettem/8-01-HW/blob/9f85f386a5e8a24bef1f39e1eafb5be6ede216a6/img/17.png)
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
https://github.com/stettem/8-01-Homework/blob/main/.gitignorey
### Задание 3
