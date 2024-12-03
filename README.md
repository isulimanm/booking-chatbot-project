Booking Chatbot Project
Welcome to the Booking Chatbot Project! This project aims to transform traditional GUI-based web interfaces into a conversational, chat-based experience using Natural Language Processing Interface (NLPI). Users can book hotels, flights, and events, as well as edit or cancel their bookings, all through a chat interface.


Features

  Conversational Booking:
    Book hotels, flights, and events through chat.
  Manage Bookings:
    Edit or cancel existing bookings via conversation.
  Natural Language Understanding:
    Dialogflow ES handles user intents and entities.
  Real-time Database:
    Firestore is used for storing and retrieving booking data.
  Cloud Functions:
    Firebase Functions execute backend logic for chatbot intents.

    
Technology Stack
  Frontend:
    Angular
  Chatbot:
    Dialogflow ES
  Backend:
    Firebase Functions
    Firestore (Firebase Realtime Database)
  Deployment:
    Firebase Hosting
  Version Control:
    Git & GitHub



    Prerequisites
Node.js (v14 or later)

Angular CLI (v12 or later)
npm install -g @angular/cli

Firebase CLI
npm install -g firebase-tools

Git


Clone the Repository


git clone https://github.com/isulimanm/booking-chatbot-project.git


cd booking-chatbot-project

Install Dependencies



For the Angular Web Application


cd travel-planner


npm install



For Firebase Functions


cd ../chatbot/functions


npm install

Run the Angular Application Locally


cd travel-planner


ng serve



Open your browser at http://localhost:4200/.


Access the web application.


Use the chat interface to interact with the bot.


Example commands:


"I want to book a hotel in Riyadh."


"Cancel my flight booking for tomorrow."


"Show my upcoming event bookings."




Project Structure


booking-chatbot-project/

├── chatbot/


│   └── functions/


│       ├── index.js          # Firebase Functions entry point


│       └── package.json


├── travel-planner/


│   ├── src/


│   │   ├── app/


│   │   └── assets/


│   ├── angular.json


│   └── package.json


├── .gitignore


└── README.md


chatbot/functions/: Contains Firebase Functions code for Dialogflow fulfillment.
travel-planner/: Angular web application source code.
