# Real-Time Notification System

Welcome to the Real-Time Notification System! This project transforms static web APIs into a dynamic, real-time notification system using Python, Kafka, ksqlDB, and Telegram.

## Features

- **Real-Time Updates:** Get instant notifications as soon as new data is available.
- **Scalable Architecture:** Built using Kafka for reliable and scalable data streaming.
- **Flexible Integration:** Easily integrates with existing static web APIs.
- **User Notifications:** Sends notifications via Telegram, ensuring you never miss an update.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.7+
- Kafka
- ksqlDB
- Telegram Bot API Token

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/hariprakash619/real-time-notification.git
    cd real-time-notification
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up Kafka and ksqlDB. Refer to their official documentation for installation and configuration.

### Configuration

1. Create a `.env` file in the project root and add your Telegram Bot API Token:
    ```plaintext
    TELEGRAM_API_TOKEN=your_telegram_api_token
    ```

2. Configure Kafka and ksqlDB settings in the `config.py` file.

### Usage

1. Start the Kafka and ksqlDB services.

2. Run the notification service:
    ```bash
    python notification_service.py
    ```

3. Your real-time notification system is now up and running. Notifications will be sent to your Telegram bot as new data arrives.

## Project Structure

- `notification_service.py`: Main script to run the notification service.
- `config.py`: Configuration file for Kafka, ksqlDB, and Telegram settings.
- `requirements.txt`: List of Python dependencies.
- `README.md`: This file.

## Contributing

Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact me at:
- LinkedIn: [Hari Prakash Vel Murugan](https://linkedin.com/in/hariprakashv)
- Email: hvelmuru@asu.edu

Happy coding! 🎉
