# Python Amazon Price Tracker
This is a Python Flask App that could track the price of Amazon products! It could work with any Amazon site (.cn, .jp, .com...). Frontend is powered by jQuery and Bootstrap. When there is a price drop, there will be **Desktop Notification** and also **On website notification**.

**Tracking**

![Example Image](https://github.com/donaldzou/Python-Amazon-Price-Tracker/raw/master/templates/example.png)

**Price Dropped Notification**

![Notification Image](https://github.com/donaldzou/Python-Amazon-Price-Tracker/raw/master/templates/notification.png)

# Dependencies
- **Python**
  - TinyDB
  - Flask
  - Beautiful Soup 4
- **Front End**
  - jQuery
  - Bootstrap
  - Push.js
# Install & Run

Follow these steps to set up and run the Python Amazon Price Tracker:

1. Clone this git repository to your local machine.
2. Navigate to the cloned directory.
3. Set up a virtual environment with the command: `python -m venv .venv`
4. To configure your system to run scripts, execute: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser` (Note: This step may require administrator privileges.)
5. Activate the virtual environment with: `.\.venv\Scripts\Activate`
6. Install the required dependencies by running: `python -m pip install -r requirements.txt`
7. Start the application with: `python tracker_server.py`
8. Access the server at `http://127.0.0.1:10086`
9. Happy tracking!

Please note that steps 3 to 7 should be performed within the command prompt or terminal. If you're using a Unix-based system (like Linux or macOS), replace backslashes (`\`) with forward slashes (`/`) in the activation command (step 5).
