<h1>Real Estate Agency Website</h1>
<img src="https://img.shields.io/badge/License-MIT-blue.svg" />

##### Table of Contents  
- [1.Installation](#instalation)  

<a name="instalation"/>
<h3>Installation</h3>

<p>Please check the official laravel installation guide for server requirements before you start. <a href="https://laravel.com/docs/8.x/installation">Official Documentation</a></p>

<p>Laravel 8 requires PHP 7.3+ or above so you need this version or the latest version of PHP installed on your system.</p>

<p>Clone the repository</p>

```
git clone https://github.com/LukaBis/real-estate-site.git
```
<p>Switch to the repo folder</p>

```
cd real-estate-site
```

<p>Install all the dependencies using composer</p>

```
composer install
```

<p>Copy the example env file and make the required configuration changes in the .env file</p>

<p>Linux</p>

```
cp .env.example .env
```
<p>Windows</p>

```
copy .env.example .env
```

<p>Generate a new application key</p>

```
php artisan key:generate
```

<p>Run the database migrations <b>(Set the database connection in .env before migrating)</b></p>

```
php artisan migrate
```

<p>Run the database seeder</p>

```
php artisan db:seed
```

<p>Create the symbolic link</p>

```
php artisan storage:link
```

<p>Check images folder that is inside inside public. Delete images folder if there are no images (image files) in sub-folders of images folder. Then create new, empty images folder. and run:</p>

```
php artisan storage:link
```

<p>Start the local development server</p>

```
php artisan serve
```

<p>You can now access the server at http://localhost:8000</p>
