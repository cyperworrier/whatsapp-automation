# WhatsApp Messenger & Image Sender

This project provides a convenient way to send WhatsApp messages and images without relying on paid APIs. It leverages the `pywhatkit` library to automate message delivery and offers flexibility by allowing users to either upload an Excel file containing message parameters or directly modify them within the application.

## Features

* **Free WhatsApp Messaging:** Utilizes `pywhatkit` to send text messages and images directly through WhatsApp Web.
* **Batch Messaging via Excel:** Send multiple messages by uploading an Excel file with recipient details and message content.
* **Direct Parameter Input:** Easily send individual messages by manually entering the phone number, message, and image path.
* **User-Friendly Interface:** (Implied for Streamlit app)

## How it Works

The core of this project is `pywhatkit`, a Python library that automates interactions with WhatsApp Web. When you send a message or image, `pywhatkit` opens a WhatsApp Web tab in your default browser, types the message/attaches the image, and sends it.

## Installation

Follow these steps to set up the project on your local machine:

1.  **Clone the Repository (or Download):**

    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    cd YOUR_REPO_NAME
    ```
    (Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.)

2.  **Create a Virtual Environment:**

    It's highly recommended to use a virtual environment to manage project dependencies.

    ```bash
    python -m venv venv
    ```

3.  **Activate the Virtual Environment:**

    * **On Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    * **On macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Install Dependencies:**

    Install the required Python packages using `pip`.

    ```bash
    pip install -r requirements.txt
    ```

## `requirements.txt` Content
