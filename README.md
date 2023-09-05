
# QuickChat (Live Chat App)

QuicjChat is a real-time chat application built using Django and WebSockets. It allows users to join existing rooms and engage in live conversations. This app is perfect if you are looking to make friends or talk to random people online!

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **User Authentication:** Secure user registration and login system.
- **Join Existing Rooms:** Users can search for and join existing chat rooms.
- **Real-time Messaging:** Instantaneous message delivery and receipt using WebSockets.
- **Message History:** View the 25 most recent messages in each chat room.


## Requirements

Before you begin, ensure you have met the following requirements:

- Python 3.x
- Django 4.2.x
- Channels 3.x

## Installation

Follow these steps to set up the Django Chat Project locally:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/django-chat-project.git
    cd django-chat-project
    ```
2. __Install project dependencies:__
    ```bash
    pip install -r requirements.txt
    ```
3. __Apply database migrations:__
   ```bash
   python manage.py migrate
   ```
4. __Create a superuser account for administration:__
    ```bash
    python manage.py createsuperuser
    ```
5. __Start the development server:__
    ```bash
        python manage.py runserver
    ```
    The Django Chat Project should now be running locally. Access it in your web browser at __http://127.0.0.1:8000/__.

## **Usage**

1. Visit the application in your web browser.
2. Sign up for a new account or log in with an existing one.
3. Join an existing room
4. Start chatting with other users in real-time.

Thank you for choosing QuickChat . We hope you find it useful for your real-time chat needs!
