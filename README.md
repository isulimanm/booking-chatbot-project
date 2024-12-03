# **Booking Chatbot Project**

Welcome to the **Booking Chatbot Project**!  
Transform traditional GUIs into an intuitive **chat-based experience**.  
Easily book and manage **hotels**, **flights**, and **events** through a conversational chatbot powered by **Natural Language Processing Interface (NLPI)**.

---

## **Features**

- **Conversational Booking**  
  Book **hotels**, **flights**, and **events** through a chat interface.  

- **Manage Bookings**  
  Edit or cancel your bookings via natural conversation.  

- **Natural Language Understanding**  
  Powered by **Dialogflow ES** to understand user intents and entities.  

- **Real-time Database**  
  Uses **Firestore** for secure booking data storage and retrieval.  

- **Cloud Functions**  
  Backend logic is executed using **Firebase Functions**.  

---

## **Technology Stack**

- **Frontend**: Angular  
- **Chatbot**: Dialogflow ES  
- **Backend**: Firebase Functions and Firestore  
- **Deployment**: Firebase Hosting  
- **Version Control**: Git & GitHub  

---

## **Prerequisites**

Before you begin, ensure the following are installed:

- **Node.js** (v14 or later)  
- **Angular CLI** (v12 or later):  
  ```bash
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
