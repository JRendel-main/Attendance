# QR Code Attendance System

This is a Python-based QR code attendance system designed for university use. The system allows instructors to generate QR codes for their classes and for students to scan these codes to mark their attendance.

## Features

- **Instructor Dashboard**: Instructors can log in to the system and create QR codes for their classes.
- **Student Scanner**: Students can scan QR codes using their smartphones to mark their attendance.
- **Attendance Tracking**: The system tracks attendance data and provides reports for instructors.

## Requirements

- Python 3.x
- Flask
- Flask-SQLAlchemy
- Flask-WTF
- qrcode
- Pillow

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/qrcode-attendance-system.git
```

2. Navigate to the project directory:

```bash
cd qrcode-attendance-system
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Set up the database:

```bash
python manage.py create_db
```

## Usage

1. Start the Flask server:

```bash
python manage.py runserver
```

2. Open your web browser and navigate to `http://localhost:5000`.
   
3. Log in as an instructor or student using the provided credentials or sign up if you're a new user.

4. Instructors can create QR codes for their classes, and students can scan these codes to mark their attendance.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to [XYZ University](https://www.xyzuniversity.edu) for the inspiration and support for this project.
