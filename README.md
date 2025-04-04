# Домашнее задание к занятию «Git»
# Климов Дмитрий

## Задание 1
Что нужно сделать:

1. Зарегистрируйте аккаунт на GitHub.
2. Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
3. Склонируйте репозиторий, используя https протокол git clone ....
4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email 6. johndoe@example.com.
6. Выполните команду git status и запомните результат.
7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
8. Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
9. Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
11. Ещё раз выполните команды git diff и git diff --staged.
12. Теперь можно сделать коммит git commit -m 'First commit'.
13. Сделайте git push origin master.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.


# Ответ:

![Снимок экрана (690)](https://github.com/user-attachments/assets/c7e52cf5-a77c-4750-a363-134a7b58b807)

![Снимок экрана (693)](https://github.com/user-attachments/assets/160451be-1d21-4a24-81ec-9e1bfdb5ca50)

Ссылка на репозиторий:     https://github.com/Dmitriy-py/my-first-git-repo

Ссылка на коммиты:         https://github.com/Dmitriy-py/my-first-git-repo/commits/main/

Ссылка на коммит:          https://github.com/Dmitriy-py/my-first-git-repo/commit/4d9edb93f0e5ccc29d1893338c8d866154f95857




## Задание 2
Что нужно сделать:

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
2. Добавьте файл .gitignore в следующий коммит git add....
3. Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
4. Сделайте коммит и пуш.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.


# Ответ:

![Снимок экрана (700)](https://github.com/user-attachments/assets/5f88d0c4-0c0d-4fea-a0fd-98367b25c39f)

Ссылка на коммит:     https://github.com/Dmitriy-py/my-first-git-repo/commit/21fac11753fedab0236480ecfbe22f17bc151909


# Задание 3

Что нужно сделать:

1. Создайте новую ветку dev и переключитесь на неё.
2. Создайте в ветке dev файл test.sh с произвольным содержимым.
3. Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.
4. Переключитесь на основную ветку.
5. Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
6. Сделайте мердж dev ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
7. Сделайте пуш в основной ветке.
8. Не удаляйте ветку dev.
В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

Ваш граф комитов должен выглядеть аналогично скриншоту:


# Ответ:

![Снимок экрана (702)](https://github.com/user-attachments/assets/7ae051f7-6b48-4916-b2d2-3e3404cdc36b)

![Снимок экрана (701)](https://github.com/user-attachments/assets/e4f5fd53-23f5-49a3-8cbc-6b7134a31a8b)

Ссылка на граф:    https://github.com/Dmitriy-py/my-first-git-repo/network
