# Banana Flourist

Welcome to Banana Flourist, a bouquet shop project developed in Django Python.

## Prerequisites

Before getting started, make sure you have the following installed on your machine:

- Python (version 3.x)
- Django (version 3.x)

## Clone the Repository

To clone the Banana Flourist repository, run the following command in your terminal:

```
git clone https://github.com/Fattybun/SP_BananaFlorist_Django.git

```

## Setting up the Virtual Environment

1. Open the cloned project in Visual Studio Code.
2. Open the integrated terminal in Visual Studio Code by pressing `Ctrl` + `` `.
3. Create a new virtual environment by running the following command:
    
    ```
    python -m venv env
    
    ```
    
4. Activate the virtual environment by running the appropriate command based on your operating system:
    - For Windows:
        
        ```
        .\\env\\Scripts\\activate
        
        ```
        
    - For macOS and Linux:
        
        ```
        source env/bin/activate
        
        ```
        

## Install Dependencies

To install the required dependencies, run the following commands in your terminal while the virtual environment is activated:

```
pip install django
pip install django-ckeditor
pip install pillow

```

## Create Django Superuser

To create a Django superuser, run the following command in your terminal while the virtual environment is activated:

```
python manage.py createsuperuser

```

Follow the prompts to enter your desired username and password.

Now you're all set to start working with Banana Flourist! Happy coding!
