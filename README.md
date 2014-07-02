#Running on heroku

####NOTE

This assumes you have installed the heroku toolbit on your system and have configured things properly


1. Clone the project
	
		git clone https://github.com/berinle/uberconf2014-ratpack.git
		
2. Create heroku app
		
		heroku create


3. Deploy to heroku
	
		git push heroku master
		
4. Set the `PUBLIC_ADDRESS` environment variable to the name of your heroku app

		heroku config:set PUBLIC_ADDRESS=http://your-app-name.herokuapp.com
		
5. Open the application

		heroku open
		
	
	
