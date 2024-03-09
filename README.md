# OrderBot: A Chatbot for Restaurant Orders

Welcome to OrderBot, a custom chatbot designed to streamline the process of taking food orders for restaurants. This Python-based application utilizes OpenAI's GPT models to interact with customers, collect their orders, and manage order summaries efficiently. OrderBot is versatile and can be customized to fit a variety of use cases beyond restaurants.

## Features

- **Interactive Order Collection**: Engages customers in a conversational manner to collect their food orders.
- **Customizable for Various Use Cases**: Easily adaptable to serve different industries and customer interaction scenarios.
- **Support for Various Menu Items**: Handles orders for pizzas, drinks, sides, and more, including customizations and toppings.
- **Order Summary Generation**: Summarizes the order before finalization, including itemized costs.
- **Delivery or Pickup Options**: Inquires customers about their preferred method of receiving their order.
- **Environmentally Friendly**: Uses a `.env` file to securely manage API keys.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.8 or newer
- pip for installing Python packages

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourgithubusername/orderbot.git
cd orderbot
```

2. **Install the required packages**

```bash
pip install -r requirements.txt
```

3. **Set up your environment variables**

Create a `.env` file in the root directory and add your OpenAI API key:

```
OPENAI_API_KEY=your_openai_api_key_here
```

### Running OrderBot

To start the chatbot, simply run the script:

```bash
python orderbot.py
```

## Usage

Once running, interact with the chatbot through the provided GUI. Enter your order details as prompted. The chatbot will guide you through the ordering process, asking for specifics like pizza size, toppings, drinks, and your preference for pickup or delivery.

## Customization

OrderBot's flexibility allows it to be tailored to a wide range of applications beyond just restaurant orders. Its core logic can be adapted to suit various business needs, such as retail inquiries, booking systems, customer service, and more. With minor modifications, OrderBot can become an essential tool for engaging and understanding your customers across multiple contexts.

## Development

OrderBot is built using Python and leverages the OpenAI API for natural language processing. It uses the Panel library to create a simple and interactive GUI for order collection.

Feel free to contribute or customize OrderBot to suit your restaurant's needs or any other business context. For contributions, please create a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenAI for the GPT models
- Panel library for the interactive web interface
