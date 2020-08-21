## Version
- PHP: 7.2
- Laravel: 6
## Installation
Please follow the steps below to setup the main site (vola) project
- Clone repository from github: https://github.com/awaisamir123/vola/tree/new-design. When done, please select the branch new-design since that is the base code for your project.
- Composer install. Open the project folder using your command-line program (we recommend Power shell for Windows) and run the command composer install. Wait for it to be done.
- Composer dump-autoload. Open the project folder using your command-line program (we recommend Power shell for Windows) and run the command composer dump-autoload.
- Create a database for the project. Open MySQL and create a database for the project. Write down the name of the database (you will need it next).
- Run command "copy .env.example .env"
- Open you .env file and put the database credential. Please make sure to alter the DB settings according to your local settings.
## Laravel setup. Run the following commands (one at a time):
- php artisan key:generate
- php artisan config:cache
- php artisan migrate --seed
- php artisan server (for run development server)
- http://localhost:8000/ (open in web browser)
