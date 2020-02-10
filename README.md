# Gay-Lab

  git init
  git add file.txt
  git remote add origin https://github.com/Azhypa/Gay-Lab
  git push -u origin master
				Создаем новую ветку develop
  git checkout -b develop
  git push origin develop
			Создаем новую ветку от develop
   git checkout -b child
   git add file.txt
   git commit -m "test test test 111"
   git push origin child
			Клонируем репозиторий
   git clone https://github.com/Azhypa/Gay-Lab
   git branch
   git checkout develop
			Переключаемся на новую ветку от develop и добавляем строку
   git checkout -b child_2
   git add file.txt
   git commit -m "test test test 222"
   git push origin child_2
				Мёржим значится 
   git checkout develop
   git merge child
   git merge child_2
				Выходим из конфликта
   git add file.txt
   git commit -m "решил проблему при мержинге"
   git push origin develop
   git branch
			
