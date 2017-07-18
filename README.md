# [Splurty](https://splurty-tyna-hhuynh.herokuapp.com/)
A database-powered restaraunt generator with a mobile-first design, using the Ruby on Rails framework, HTML, and CSS. Uses Git and Github for version control, and launched on Heroku.
![alt tag](https://user-images.githubusercontent.com/14388583/28289708-81ef9b74-6af8-11e7-8f1b-7718cac05d93.png)

## Running Locally
Make sure you have Ruby installed.
Clone or download the repository.

Run the following code to install the application's dependencies:
```
bundle install
```
Create initial database:
```
rake db:create
```
Run the migration:
```
rake db:migrate
```

The application should now be running on your localhost.

## Deployment
To deploy on Heroku. Adjust the APP_NAME to your project name.
```
heroku create APP_NAME
```
Now push it up to Heroku with the following command:
```
git push heroku master
```
It should take a few moments to run, and when it finishes it should say "Launching..." along with a URL.

To easily see you heroku url you can type:
```
heroku apps:info
```
The application can now be found at the URL returned.
