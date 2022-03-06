#  Домашнее задание по гиту #  
  
## Указание upstream ##  
  
- Сделал форк проекта 2020 года  
- Клонировал задание в папку Задание по гиту  
- Указал в качестве апстрима форк 2021 года командой ***git remote add upstream-my URL***  
  
## Создание backport ##  
  
- Создал ветку backport командой *git branch backport*  
- Переместился в ветку backport командой ***git checkout backport***  
- Перенес свои комиты в backport      ***git merge remotes/upstream-my/master*** 
- Запушил backport  
  
## Указание upstream своего и партнера ##  
  
- Добавил апстрим партнера ***git remote add upstream-theirs URL***  
- Обновил его командой ***git fetch***  
- Перешел в ветку мастер ***git chekout master***  
- Смерджил проект партнера и свой в ветке мастер  
- Получил вывод ***git remote -v***
  
## Создание файла remotes ##  
  
- Создал файл remotes   
- Поместил в него вывод ***vi remotes*** и комитнул его ***git commit -m " ... "***  
  
## Создание файла howto.md ##  
  
- Создал файл howto.md и описал в нем ход выполнения практики  
- Комитнул howto.md  
