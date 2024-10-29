Sudoku Solver App
Ever been stumped by a challenging sudoku puzzle? This app is here to help! With a quick and intuitive interface, you can solve any valid sudoku puzzle in seconds. Just enter your puzzle configuration and hit submit to see it solved.

Live Preview

Project Structure
arduino
Copy code
├── static
│   ├── script.js
│   ├── styles.css
├── templates
│   ├── index.html
├── Main.py
├── server.py
├── .gitignore
├── README.md
Technologies Used
Python (Flask, Gunicorn)
HTML, CSS, JavaScript
Running the App Locally
To get this app running on your local machine, ensure you have Python installed. Then, set up a virtual environment and install the necessary packages.

Requirements
The app relies on the following Python modules, specified in requirements.txt:

click==7.1.2
Flask==1.1.2
gunicorn==20.1.0
itsdangerous==1.1.0
Jinja2==2.11.3
MarkupSafe==1.1.1
Werkzeug==1.0.1
Setup
Clone the repository and navigate to the project directory.

Install the required modules using:

bash
Copy code
pip install -r requirements.txt
Start the app:

On Windows:
bash
Copy code
python server.py
On macOS and Linux:
bash
Copy code
python3 server.py
Open your browser and go to http://localhost:3000 to use the app.
