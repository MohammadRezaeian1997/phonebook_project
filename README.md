# Django Phonebook

Django Phonebook is a simple web application built with Django that allows users to store and manage contacts in a phonebook.

## Features

- Add, edit, and delete contacts
- View contact details
- Search for contacts by name
- User-friendly Django admin interface for managing contacts

## Requirements

- Python (3.x recommended)
- Django
- Django's default database (SQLite)

## Installation

1. Clone this repository: git clone https://github.com/MohammadRezaeian1997/phonebook_project.git
2. Navigate into the project directory:cd phonebook_project
3. Install the required dependencies: pip install -r requirements.txt
4. Apply migrations to create the database schema: python manage.py makemigrations
python manage.py migrate
5. Create a superuser to access the Django admin interface: python manage.py createsuperuser
6. Run the development server: python manage.py runserver
7. Access the application in your web browser at `http://127.0.0.1:8000/` and log in with the superuser credentials to access the Django admin interface.

## Usage

- Navigate to the Django admin interface (`http://127.0.0.1:8000/admin`) to manage contacts. You can add, edit, and delete contacts from here.
- To view and interact with contacts on the frontend, you can create custom views and templates as per your requirements.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project was created as a demonstration of building a basic Django application.
- Special thanks to the Django community for creating excellent documentation and resources.
