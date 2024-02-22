Café Finder Web Application
Overview
The Café Finder Web Application is a Flask-based web application designed to help users discover cafes in their area. It provides functionalities for users to view existing cafes, add new cafes, and delete closed ones. The application allows users to search for cafes based on specific amenities such as WiFi availability, good coffee, seating options, and more.

Features
View a list of existing cafes with details such as name, location, amenities, and coffee prices.
Add new cafes to the database, specifying amenities and other relevant information.
Delete closed cafes from the database.
Responsive design for optimal viewing on desktop and mobile devices.
Technologies Used
Python
Flask
SQLAlchemy
HTML/CSS
Bootstrap
Setup Instructions
Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Set up a SQLite database by running python and executing the following commands:
css
Copy code
from main import db
db.create_all()
Start the Flask development server by running python main.py.
Access the application in your web browser at http://localhost:5000.
Usage
Navigate to the homepage to view the list of cafes.
Use the "Add Café" button to add a new cafe to the database.
To delete a closed cafe, click on the "Delete" button next to the cafe listing.
Ensure that you have the appropriate API key to perform delete operations.
Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
