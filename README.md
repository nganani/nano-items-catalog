# Item Catalog Web Application
Project for Udacity full stack web developer nanodegree
## Running the application
* Install dependent libraries using `pip3 install -U -r requirements.txt`
  * Flask
  * sqlalchemy
  * requests
  * oauth2client
* Enter your developer credentials for 3rd party authentication in the two files below
* Google:  `client_secrets.json` see [here](https://developers.google.com/maps/documentation/javascript/get-api-key) for more details
* Facebook: `fb_client_secrets.json`, see [here](https://developers.facebook.com/apps) for more details
* Create empty database: `python3 database_setup.py`
* Run `python3 app2.py`
* Go to this [link](http://localhost:5000)
Note: This project was written for Python 3 but should work on Python 2 just as well

## Skills
1. Python
2. HTML/CSS
3. SQLAlchemy
4. OAuth
5. Using frameworks in general, Flask in particular
6. Authentication and Authorization
7. CRUD Operations and using database driven web development
8. RESTfull API endpoints

## License & Contributers
* Project is based on Udacity restaurants project, with elements from [this repo](https://github.com/udacity/ud330/tree/master/Lesson4/step2) and my solution, modified as required
* Project is released under the [MIT License](http://opensource.org/licenses/MIT).
