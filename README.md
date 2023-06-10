# Larvel 10: Create RESTful API with CRUD endpoints
Create a RESTful Tasks API in Laravel v10 using with basic C-R-U-D operations:
    
| **METHOD** |	**ACTION** | **REQUEST**  | **Value** |
|----------	|------------- |--------------|------------|
| [![](https://img.shields.io/badge/-GET-brightgreen)](GET)      	| Fetch Tasks      	   | http://127.0.0.1:8000/api/v1/tasks/11    	 | application/json|
| [![](https://img.shields.io/badge/book-blueviolet?style=for-the-badge)](POST)      	| Save Tasks      	   | http://localhost:8000/api/v1/tasks    	 | application/json|
| [![](https://img.shields.io/badge/API-yellow?style=for-the-badge)](PUT)      	| Update Tasks      	   | http://localhost:8000/api/v1/tasks/11    	 | application/json|
| [![](https://img.shields.io/badge/Crates.io-orange?style=for-the-badge)](PATCH)      	| Mark Tasks Complete      	   | http://localhost:8000/api/v1/tasks/11/complete    	 | application/json|
| [![](https://img.shields.io/badge/Lib.rs-lightgrey?style=for-the-badge)](DELETE)      	| Delete Tasks      	   | http://localhost:8000/api/v1/tasks/11/    	 | application/json|

# Testing API

Run the laravel development server

    php artisan serve

The api can now be accessed at

    http://localhost:8000/api/v1/tasks

Request headers

| **Required** 	| **Key**              	| **Value**            	|
|----------	|------------------	|------------------	|
| Yes      	| Accept    	| application/json 	|