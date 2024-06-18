# Project Name

MenTani

## Set Up

### Check Internet Connection

Ensure that your internet connection is active.

### Steps to Set Up the Project

1. **Create SQL Database**

   Create a new SQL database for your project.

2. **Open Terminal**

   Open the terminal and navigate to the root directory of your project.

3. **Copy Environment File**

   Copy the example environment file to a new `.env` file.

   ```sh
   cp .env.example .env

4. **Configure .env Database Settings**

   Open the .env file and configure the database settings to match your database credentials.

   ```plaintext
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password

5. **Generate Application Key**

   Run the following command to generate a new application key.

   ```sh
   php artisan key:generate

6. **Install NPM Dependencies**

   Run the following command to install the necessary NPM dependencies.

   ```sh
   npm install

7. **Install Composer Dependencies**

   Run the following command to install the necessary Composer dependencies.

   ```sh
   composer install

8. **Seed the Database**

   Run the following command to seed the database with initial data.

   ```sh
   php artisan db:seed --class=UserSeeder

9. **Compile Assets**

   Run the following command to compile the assets.

   ```sh
   npm run dev

10. **Start the Development Server**

   Run the following command to start the Laravel development server.

   ```sh
   php artisan serve

## Default Credentials
- Username: admin
- Password: admin
