1.Need to install django
2.Css and java script files are downloaded from google.
3.Index.html file also i download from google and made some changes.
4.To run this project:
	step 1:
		extract rakesh.rar
	step 2:
		download PostgreSql and connect it with out project:
			1.go to folder rakesh then rakesh_project then again the the rakesh_project folder 
			2.Change in settings.py
			3.change the database part for mine it is:
				DATABASES = {
								'default': {
									'ENGINE': 'django.db.backends.postgresql',
									'NAME': 'rakesh',
									'USER': 'postgres',
									'PASSWORD' : '12345',
									'HOST' : 'localhost'
								}
							}

	step 3:
		go to to the folder rakesh then rakesh_project using cmd:
			1.cd rakesh
			2.cd rakesh_project
	step 4:
		Run a command:
			python manage.py runserver
	step 5:
		you will get a http address(Starting development server), copy that address and paste
		it in browser.

	then you can access my project properly
	

********I made this project when i was learning django basic from youtube channel telusko**********