# Lift Tracker App

The Lift Tracker App is a strength training application designed to help users follow a structured workout program, log performance data, and monitor strength progression over time[cite: 1]. The system focuses on making progressive overload efficient by replacing scattered notes and memory with reliable historical data[cite: 1].

## Core Features

* **Calendar Workout View**: A calendar interface where each day displays scheduled exercises.
* **Workout Logging**: Users can enter weight and repetitions completed for each exercise to create a historical record.
* **Previous Performance Display**: Automatically shows the most recent logged weight and reps when a lift reappears.
* **Program Editor**: Allows users to personalize their training structure by editing exercises, sets, and reps.
* **Estimated 1RM Tracking**: Calculates and displays estimated one-rep max (1RM) progression to provide measurable insight into strength growth.

## Technology Stack

* **Frontend**: React (Component-based structure for dashboards and calendar views).
* **Backend**: Python (Handles authentication, data management, and business logic).
* **Database**: SQL (Relational structure for users, exercises, and logs).

## Requirements & User Stories

### Key User Stories
* **Planning**: As a lifter, I want to see my scheduled workout for today.
* **Tracking**: As a user, I want to log weight and reps to track progress.
* **Progression**: As a returning user, I want to see my previous lifts to ensure progressive overload.
* **Customization**: As a user, I want to edit my workout program to adjust my training plan.

### Technical Requirements
* **Persistence**: Data persists securely in a cloud database.
* **Security**: Authentication protects personal workout history, with data transmitted via HTTPS.

## Future Roadmap (Wishes)
* Automatic weight increase recommendations.
* Personal record (PR) notifications.
* Data export functionality (CSV).
* Dark mode support.
