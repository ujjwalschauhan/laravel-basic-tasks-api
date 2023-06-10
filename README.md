# Larvel 10: Create RESTful API with CRUD endpoints
Create a RESTful Tasks API in Laravel v10 with basic C-R-U-D operations:
    
| **METHOD** |	**ACTION** | **REQUEST**  | **Value** |
|----------	|------------- |--------------|------------|
| [![](https://img.shields.io/badge/-GET-brightgreen)](GET)      	| Fetch Tasks      	   | http://127.0.0.1:8000/api/v1/tasks/11    	 | application/json|
| [![](https://img.shields.io/badge/-POST-brightgreen)](POST)      	| Save Tasks      	   | http://localhost:8000/api/v1/tasks    	 | application/json|
| [![](https://img.shields.io/badge/-PUT-brightgreen)](PUT)      	| Update Tasks      	   | http://localhost:8000/api/v1/tasks/11    	 | application/json|
| [![](https://img.shields.io/badge/-PATCH-brightgreen)](PATCH)      	| Mark Tasks Complete      	   | http://localhost:8000/api/v1/tasks/11/complete    	 | application/json|
| [![](https://img.shields.io/badge/-DELETE-brightgreen)](DELETE)      	| Delete Tasks      	   | http://localhost:8000/api/v1/tasks/11/    	 | application/json|

# Testing API

Run the laravel development server

    php artisan serve

The api can now be accessed at

    http://localhost:8000/api/v1/tasks

Request headers

| **Required** 	| **Key**              	| **Value**            	|
|----------	|------------------	|------------------	|
| Yes      	| Accept    	| application/json 	|
