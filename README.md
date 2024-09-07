# AdopTrack - Django Project

[English](README.md) | [Español](README.es.md)

## English Version (README.md)

# AdopTrack

AdopTrack is a Django-based web application for managing pet adoptions.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Python (3.8 or higher)
- pip (Python package manager)
- virtualenv
- Git

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/adoptrack.git
   cd adoptrack
   ```

2. Create a virtual environment:
   ```
   python3 -m venv venv
   ```

3. Activate the virtual environment:
   - On macOS and Linux:
     ```
     source venv/bin/activate
     ```
   - On Windows:
     ```
     venv\Scripts\activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

5. Run migrations:
   ```
   python manage.py migrate
   ```

6. Start the development server:
   ```
   python manage.py runserver
   ```

Visit `http://127.0.0.1:8000` in your web browser to see the application running.

## Features

- Pet listing and search
- Adoption application process
- User authentication and profiles
- Administrative dashboard for managing pets and applications

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

