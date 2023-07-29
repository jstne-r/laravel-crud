# Laravel CRUD App

This is a simple CRUD (Create, Read, Update, Delete) project built using Laravel. It allows you to manage data records through a web interface. 🤠

## 🗃️ Prerequisites

Before running this application, make sure you have the following installed on your system:

- PHP (>= 7.3)
- Composer
- MySQL

## 👾 Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/jstne-r/laravel-crud.git
cd laravel-crud
```

2. Install the project dependencies:

```bash
composer install
```

3. Create a copy of the `.env.example` file and name it `.env`:

```bash
cp .env.example .env
```

4. Generate an application key:

```bash
php artisan key:generate
```

5. Configure your database in the `.env` file. Update the following lines with your database credentials:

```dotenv
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel-crud
DB_USERNAME=
DB_PASSWORD=
```

6. Run the database migrations:

```bash
php artisan migrate
```

7. (Optional) If you want to populate the database with sample data:

```bash
php artisan db:seed
```

<b>Note</b>: To edit the UI of the project, go to resources\views\products.

## 🏃🏽Running the Application

To start the development server, run the following command:

```bash
php artisan serve
```

You can now access the application by visiting `http://localhost:8000` in your web browser.

## 🤖 Usage

- To view the list of records, navigate to the homepage.
- To create a new record, click on the "Add New" button and fill in the required information.
- To update an existing record, click on the "Edit" button next to the record you want to update.
- To delete a record, click on the "Delete" button next to the record you want to remove.

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms of the license.

---

🎉🎉 <b>Congratulations!</b> You have successfully set up and run the Laravel CRUD project. If you encounter any issues or have questions, feel free to reach out for support. Happy coding!