# SmartQuiz-AI: Intelligent Online Quiz and Performance Analysis System

An AI-powered online quiz platform that enables students to participate in assessments, receive instant results, and gain personalized learning insights through intelligent performance analysis.

---

## Project Overview

SmartQuiz-AI is a web-based assessment platform designed to enhance the learning experience through automated quiz evaluation and performance analytics. The system allows teachers to create and manage quizzes, students to participate in assessments, and administrators to monitor overall system activities.

The platform leverages intelligent analytics to evaluate student performance, identify learning gaps, and provide personalized recommendations for improvement.

---

## Problem Statement

Traditional online quiz systems primarily focus on score generation and provide limited feedback to students. As a result, learners often struggle to understand their strengths and weaknesses.

### Challenges Addressed

* Lack of detailed performance analysis.
* Limited personalized feedback for students.
* Difficulty in monitoring academic progress.
* Manual interpretation of quiz results.
* Inefficient identification of weak subject areas.

SmartQuiz-AI addresses these challenges through automated evaluation, performance tracking, and AI-driven insights.

---

## Objectives

* Develop an interactive online quiz platform.
* Automate quiz evaluation and score calculation.
* Analyze student performance using intelligent analytics.
* Provide personalized feedback and recommendations.
* Enable continuous progress monitoring.
* Improve learning outcomes through data-driven insights.

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* Python
* Flask

### Database

* MySQL

### Tools

* VS Code
* Git & GitHub

---

## Key Features

### Role-Based Access Control

#### Admin

* Register Teachers and Students.
* Manage user accounts.
* Monitor system activities and quiz usage.

#### Teacher

* Create and manage quizzes.
* Add and modify quiz questions.
* View student performance reports.
* Analyze individual and batch-wise results.

#### Student

* Login securely.
* Join quizzes using enrollment or quiz codes.
* Attempt quizzes online.
* View instant scores and feedback.

---

### Quiz Management

* Multiple-choice question support.
* Time-bound quiz execution.
* Automatic answer evaluation.
* Unique quiz access codes.
* Real-time score generation.

---

### AI-Based Performance Analysis

* Subject-wise performance tracking.
* Strength and weakness identification.
* Personalized recommendations.
* Progress monitoring dashboard.
* Performance comparison and analytics.

---

### Responsive User Interface

* Mobile-friendly design.
* Tablet and desktop compatibility.
* User-friendly navigation.

---

### Secure Database Management

* Secure storage of user information.
* Quiz and result management.
* Reliable data retrieval and reporting.

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/Haripriyan-V/SmartQuiz-AI-Intelligent-Online-Quiz-and-Performance-Analysis-System.git
cd SmartQuiz-AI-Intelligent-Online-Quiz-and-Performance-Analysis-System
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure Database

* Create the MySQL database.
* Import the provided SQL schema.
* Update database credentials in `app.py`.

### 4. Run the Application

```bash
python app.py
```

### 5. Access the Application

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## Usage Workflow

```text
[Admin]
    |
    v
[Register Users & Provide Credentials]
    |
    v
[Teacher]
    |
    +--> Create Quiz
    +--> Set Parameters
    +--> Publish Quiz
    |
    v
[Student]
    |
    +--> Login
    +--> Join Quiz
    +--> Submit Answers
    |
    v
[Automatic Evaluation]
    |
    v
[AI Performance Analysis]
    |
    v
[Results & Recommendations]
    |
    v
[Teacher Review]
    |
    v
[Admin Monitoring]
```

---

## Future Enhancements

* AI-powered question generation.
* Adaptive learning recommendations.
* Leaderboard and gamification features.
* Detailed graphical analytics dashboard.
* Email and SMS notifications.
* Online proctoring support.

---

## Conclusion

SmartQuiz-AI combines online assessment with intelligent performance analytics to create a smarter learning environment. By providing automated evaluation, personalized feedback, and progress tracking, the platform helps students improve their learning outcomes while enabling educators to make data-driven decisions.
