# AI Cybersecurity Chatbot

## Overview
The AI Cybersecurity Chatbot is a desktop application built using C# and WPF that educates users about cybersecurity through an interactive chatbot. The application uses machine learning with ML.NET to provide intelligent responses, stores user information, manages reminders, tracks user interests, and includes a cybersecurity quiz game.

## Features

- User registration with username recognition
- AI-powered cybersecurity chatbot
- Machine learning response prediction using ML.NET
- Learns from unknown questions for future improvements
- Stores user interests automatically
- Task reminder management
- Activity log tracking
- Cybersecurity quiz game
- Voice greeting on startup
- User-friendly WPF interface

## Technologies Used

- C#
- WPF (Windows Presentation Foundation)
- .NET Framework
- ML.NET
- SQL Server LocalDB
- XAML
- File Handling
- Git & GitHub

## Project Structure

```
demo
│
├── MainWindow.xaml
├── MainWindow.xaml.cs
├── training.cs
├── respond.cs
├── tasks.cs
├── user_name.cs
├── voice_greeting.cs
├── Question_in_quiz.cs
├── greeting.wav
├── logo.png
└── nlp_model.zip
```

## How It Works

1. The user enters their username.
2. The chatbot checks if the username already exists.
3. A voice greeting welcomes the user.
4. Users can ask cybersecurity-related questions.
5. ML.NET predicts the most relevant response.
6. Unknown questions are saved for future learning.
7. Users can save their interests by saying:
   ```
   I am interested in cybersecurity
   ```
8. Users can manage reminders and tasks.
9. The application records user activity.
10. Users can test their knowledge using the cybersecurity quiz.

## Database

The application automatically creates a SQL Server LocalDB table named:

```
demo_tasks
```

The table stores:

- Task ID
- Task Name
- Description
- Due Date
- Status

## Machine Learning

The chatbot uses ML.NET to:

- Train on predefined cybersecurity responses
- Predict the most suitable response
- Save the trained model
- Load the model when the application starts
- Improve responses over time

## Files Used

| File | Purpose |
|-------|----------|
| user_names.txt | Stores usernames |
| interested_topic.txt | Stores user interests |
| unknown_questions.txt | Stores unanswered questions |
| learned_questions.txt | Stores learned responses |
| nlp_model.zip | Trained ML model |

## Screens

- Home Page
- Username Page
- Chat Page
- Reminder Page
- Activity Log
- Quiz Game

## Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Cybersecurity-Chatbot.git
```

2. Open the solution in Visual Studio.

3. Restore NuGet packages.

4. Build the project.

5. Run the application.

## Future Improvements

- Speech-to-text support
- Text-to-speech chatbot replies
- Better natural language understanding
- User authentication
- Cloud database integration
- More cybersecurity topics
- Dark mode
- Multi-language support

## Author

Rothe Makungo

## License

This project is for educational purposes.
