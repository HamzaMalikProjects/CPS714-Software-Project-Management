Our project has been implemented with HTML, CSS and JavaScript for the frontend and Django for the backend.

In order to run the project, we advise you to do the following

First, unzip the source code, and enter the folder that contains the requirements.txt

Then set up a virtual python environment with the following command:
python -m venv venv
--- Then depending on your environment, you'll need to start the virtual environment with an activation script inside venv/scripts

Then install all the python dependencies with:
pip install -r requirements.txt

To run the server, enter the backend folder and enter the following command:
python manage.py runserver

Now, the server should be running locally, accessible through: http://127.0.0.1:8000/

The rewards front-end is accessible through: http://127.0.0.1:8000/rewards-page/

The backend api is accessible through: http://127.0.0.1:8000/rewards-api/{api endpoint}

A detailed list of the api endpoints can be found in the architecture & system design document, with inputs and outputs required for the functionality


