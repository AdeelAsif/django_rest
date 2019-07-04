# Create the project directory
    mkdir tutorial
    cd tutorial

# Create a virtual environment to isolate our package dependencies locally
    python3 -m venv env
    source env/bin/activate  # Windows use `env\Scripts\activate`

# Install Django and Django REST framework into the virtual environment
    pip install django
    pip install djangorestframework
    pip install coreapi  # For Documentation generation

# Set up a new project with a single application
    django-admin startproject tutorial .  # Note the trailing '.' character
    cd tutorial
    django-admin startapp quickstart
    cd ..

#Documenting Your API
The coreapi library is required as a dependency for the API docs. Make sure to install the latest version. The Pygments and Markdown libraries are optional but recommended.

    pip install coreapi  # For Documentation generation
    


## Links
0. [Getting Started Django](https://www.djangoproject.com/start/)
1. [Django Rest](https://www.django-rest-framework.org/)
2. [Quick Start](https://www.django-rest-framework.org/tutorial/quickstart/)
3. [Tutorial](https://www.django-rest-framework.org/tutorial/1-serialization/)
4. [Documenting Your API](https://www.django-rest-framework.org/topics/documenting-your-api/)