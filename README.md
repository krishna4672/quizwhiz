# QwizWhiz

## Overview

QwizWhiz is an interactive quiz management system designed to create, manage, and participate in quizzes seamlessly. It provides an intuitive platform for educators, students, and quiz enthusiasts to engage in knowledge-based activities with real-time results and analytics.

## Features

- **User Authentication**: Secure login and signup for users.
- **Quiz Creation**: Admins and educators can create custom quizzes.
- **Multiple Question Types**: Supports MCQs, True/False, and short answer questions.
- **Real-time Scoring**: Instant feedback and leaderboard system.
- **Data Analytics**: Performance tracking and quiz insights.
- **Responsive Design**: Works across desktop and mobile devices.

## Technologies Used

- **Programming Language**: Python, JavaScript
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django
- **Database**: PostgreSQL/MySQL
- **APIs**: RESTful APIs for quiz and user management
- **Deployment**: Docker, AWS/GCP

## Installation

### Prerequisites

- Python 3.8+
- Node.js & npm (for frontend)
- Virtual environment (optional but recommended)

### Steps to Install

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/qwizwhiz.git
   cd qwizwhiz
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate     # For Windows
   ```
3. Install backend dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Navigate to the frontend folder and install dependencies:
   ```sh
   cd frontend
   npm install
   ```
5. Set up environment variables in a `.env` file:
   ```env
   SECRET_KEY=your_secret_key_here
   DATABASE_URL=your_database_url_here
   ```
6. Run the backend:
   ```sh
   python app.py
   ```
7. Run the frontend:
   ```sh
   cd frontend
   npm start
   ```
8. Access the application at `http://127.0.0.1:3000`

## Usage

1. Register and log in to your account.
2. Create or join a quiz.
3. Answer questions and get instant results.
4. View performance analytics and leaderboards.

## Future Enhancements

- Integration of AI-based question generation.
- Gamification features such as badges and achievements.
- Support for live quiz competitions.
- Mobile app development for better accessibility.

## Contributing

Contributions are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, feel free to reach out:

- **Author**: Krishna Bhardwaj
- **Email**: [krishnabhardwaj4672@gmail.com](mailto\:krishnabhardwaj4672@gmail.com)
- **GitHub**: krishna4672

