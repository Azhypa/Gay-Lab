# Gay-Lab

  git init
  git add file.txt
  git commit -m "commit_first"
  git remote add origin https://github.com/Azhypa/Gay-Lab
  git push -u origin master
				Создаем новую ветку develop
  git checkout -b develop
  git push origin develop
				Создаем новую ветку от develop
   git checkout -b child
   git add file.txt
   git commit -m "add first line" -m "test test test 111"
   git push origin child
				Клонируем репозиторий
   git clone https://github.com/sania1801/EMP_task_1
   git branch
   git checkout develop
				Переключаемся на новую ветку от develop и добавляем строку
   git checkout -b child_2
   git add file.txt
   git commit -m "test test test 222"
   git push origin child_second_develop
				Мёржим значится 
   git checkout develop
   git merge child
   git pull origin child_2 // лишний раз засинхронил и перестраховался
   git merge child_2
				Выходим из конфликта
   git add file.txt
   git commit -m "решил проблему при мержинге"
   git push origin develop
   git branch
			
