# Indian Food Ordering Chatbot

Welcome to the **Indian Food Ordering Chatbot** project! This chatbot uses **Dialogflow**, **Natural Language Processing (NLP)**, **FastAPI**, and an **SQL database** to handle food orders, track existing orders, and provide information about office hours. 

## Project Overview

This chatbot is designed to take user inputs for ordering food, tracking orders, and checking the restaurant's office hours. The project focuses on **Indian cuisine**, with a variety of delicious dishes that users can choose from, such as:

- Pav Bhaji
- Chole Bhature
- Pizza
- Mango Lassi
- Masala Dosa
- Biryani
- Vada Pav
- Rava Dosa
- Samosa

The chatbot interacts with the user via natural language queries and offers a smooth experience for placing and tracking orders.

## Features

- **Order Placement**: Users can interact with the chatbot to place orders for the listed Indian food items.
- **Order Tracking**: The chatbot allows users to track their orders by providing an order ID.
- **Office Hours**: Users can ask the chatbot for restaurant operating hours. The restaurant is closed on Mondays and open from 9:00 AM to 10:30 PM, Tuesday through Sunday.

## Technologies Used

1. **Dialogflow**: For natural language understanding and building chatbot interactions.
2. **NLP**: To process user queries and map them to intents for order placement, tracking, and retrieving office hours.
3. **FastAPI**: A high-performance web framework for building the backend API that handles requests from the Dialogflow chatbot.
4. **SQL Database**: Stores order data, including order status and details for tracking purposes.

## How It Works

1. **Order Food**: Users can interact with the chatbot to place an order for their favorite Indian dish. For example, the user can say, *"I want to order a Masala Dosa"* or *"Add a Mango Lassi to my order."*
   
2. **Track Order**: Users can track their orders by saying something like, *"Track my order with ID 12345,"* and the chatbot will retrieve the order status from the database.
   
3. **Check Office Hours**: Users can ask about the restaurant's operating hours with queries like *"What are your office hours?"* The chatbot responds with the hours of operation.

## Example Queries

- **Order Placement**:  
   *"I’d like to order Pav Bhaji."*  
   *"Add Biryani to my order."*
   
- **Track Order**:  
   *"Track order number 23456."*  
   *"What’s the status of my order?"*
   
- **Office Hours**:  
   *"When are you open?"*  
   *"What are your working hours?"*

## Video Demo

While the project is not currently live, you can view a demo of the chatbot in action on **LinkedIn**. The video demonstrates how to place orders, track them, and check the office hours through natural language queries.

[Watch the demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7250285268224634880/)

## Future Improvements

- **Deployment**: Setting up the chatbot on a live server for real-time usage.
- **Enhanced NLP**: Improving intent recognition for more complex user queries.
- **User Authentication**: Adding a user login system to personalize order history and preferences.

## How to Run Locally

1. Clone the repository.
2. Set up a virtual environment and install the required dependencies (`FastAPI`, `SQLAlchemy`, `Dialogflow` integration).
3. Set up a local SQL database for storing orders.
4. Run the FastAPI server and connect it to Dialogflow.
5. Test the chatbot locally through Dialogflow’s testing interface.

## License

This project is open-source and licensed under the MIT License.

---

Thank you for checking out this project! Feel free to reach out with feedback or suggestions.