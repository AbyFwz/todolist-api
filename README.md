

**Running a ToDoList Project API**
=============================================

**Table of Contents**
-----------------

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Clone the Repository](#clone-the-repository)
4. [Install Dependencies](#install-dependencies)
5. [Configure Environment Variables](#configure-environment-variables)
6. [Migrate Database](#migrate-database)
7. [Run the Application](#run-the-application)
8. [Test API Endpoints](#test-api-endpoints)

**Introduction**
---------------

This guide provides a step-by-step process for running an existing Laravel project API.

**Prerequisites**
----------------

* Git installed on your system
* Composer installed on your system
* PHP 8.3.6 or higher installed on your system
* A code editor or IDE of your choice

**Clone the Repository**
-------------------------

1. Open your terminal and navigate to the directory where you want to clone the repository.
2. Clone the repository using the following command:
```bash
git clone https://github.com/abyfwz/todolist-api.git
```
3. Navigate to the cloned repository directory:
```bash
cd todolist-api
```

**Install Dependencies**
-------------------------

1. Install the required dependencies using Composer:
```bash
composer install
```
2. Wait for the installation process to complete.

**Configure Environment Variables**
----------------------------------

1. Create a new `.env` file by copying the `.env.example` file:
```bash
cp .env.example .env
```
2. Update the `.env` file with your own environment variables.

**Migrate Database**
---------------------

1. Run the migration command to create the database tables:
```bash
php artisan migrate
```
2. Wait for the migration process to complete.

**Run the Application**
-------------------------

1. Run the application using the following command:
```bash
php artisan serve
```
2. The application will start running on `http://localhost:8000`.

**Test API Endpoints**
----------------------

1. Use a tool like Postman or cURL to test the API endpoints.
2. Verify that the API endpoints are returning the expected responses.

**Conclusion**
--------------

That's it! This guide provides a step-by-step process for running a ToDoList API project. You can now run and test the API endpoints.
