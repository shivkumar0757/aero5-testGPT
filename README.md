# Django-React App

This is a sample Django-React app that demonstrates how to build a full-stack web application using Django and React.

## Prerequisites

Before you can run this app, you need to install the following software:

- Python 3.6 or higher
- Node.js 14 or higher

## Installation

To install the app, follow these steps:

1. Clone this repository to your local machine:
`git clone https://github.com/yourusername/your-repo.git`



2. Change into the project directory:

`cd your-repo`


3. Install the Python dependencies:

`pip install -r requirements.txt`

(this step will not work now, you have to manually install dipendencies, by checking missing package)

4. Install the Node.js dependencies:

`cd frontend
npm install`


## Usage

To start the app, follow these steps:

1. Start the Django development server:

`python manage.py runserver`


2. In a new terminal window, start the React development server:

`cd frontend
npm start`


3. Open your web browser and go to `http://localhost:3000/` to view the app.


# Using app


3. Open your web browser and go to `http://localhost:3000/` to view the app.

4. Click on the "Fetch Data" button to fetch data from the backend. The button is located in the center of the screen and is styled to match the theme of the app.

5. The app will fetch data from the backend using the URL `http://localhost:8000/api/data`. The backend should be running at that URL for the app to function correctly.
`The url is kept inside  DataFetcher  component inside src directory`

6. If the app is able to connect to the backend, it will display a message in green that says "Connected to backend in green" followed by the message returned by the backend. If the app is unable to connect to the backend, it will display a message in red that says "Unable to connect with backend".

## Contributing

If you'd like to contribute to this project, please fork the repository and make changes as you'd like. Pull requests are welcome!

## License

This project is licensed under the [MIT License](LICENSE).

Make sure to replace the repository URL and your username with the actual values for your project. You can also customize the content of the README file as needed for your specific project.

Note that the installation and usage instructions assume that the user is using a Unix-like shell (e.g., Bash) on either Windows or Ubuntu. If the user is using a different shell or operating system, the commands may need to be modified accordingly.


## Contributing

If you'd like to contribute to this project, please fork the repository and make changes as you'd like. Pull requests are welcome!

## License

This project is licensed under the [MIT License](LICENSE).

Make sure to replace the repository URL and your username with the actual values for your project. You can also customize the content of the README file as needed for your specific project.

Note that the installation and usage instructions assume that the user is using a Unix-like shell (e.g., Bash) on either Windows or Ubuntu. If the user is using a different shell or operating system, the commands may need to be modified accordingly.
