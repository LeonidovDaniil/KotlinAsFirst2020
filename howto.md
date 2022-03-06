1)Сделал форк проекта 2020 года
2)Клонировал задание в папку Задание по гиту
3)Указал в качестве апстрима форк 2021 года командой *git remote add upstream-my URL*
4)Создал ветку backport командой *git branch backport*
5)Переместился в ветку backport командой *git checkout backport*
6)Перенес свои комиты в backport      *git merge remotes/upstream-my/master*
7)Запушил backport
8)Добавил апстрим партнера *git remote add upstream-theirs URL*
9)Обновил его командой *git fetch*
10)Перешел в ветку мастер *git chekout master*
11)Смерджил проект партнера и свой в ветке мастер
12)Получил вывод *git remote -v*
13)Создал файл remotes
14)Поместил в него вывод *vi remotes* и комитнул его *git commit -m " ... "*
15)Создал файл howto.md и описал в нем ход выполнения практики
16)Комитнул howto.md
