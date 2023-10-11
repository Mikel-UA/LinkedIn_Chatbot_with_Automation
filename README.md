# LinkedIn ChatBot (Disclaimer: Pre-ChatGPT Era)

## Overview

This project is a pre-ChatGPT era solution for automating LinkedIn conversations. It uses web scraping with Selenium, the Transformers library for conversational AI, and translation services to interact with LinkedIn contacts. It was created as a low-resource, automated chatbot for LinkedIn. Please note that LinkedIn's terms of service change, and this script's functionality may be affected by those changes.

**Disclaimer**: The project was created before the existence of ChatGPT and serves as a historical example of early attempts to automate LinkedIn interactions. Please be aware of the LinkedIn User Agreement and use this project responsibly.

## Project Structure

The project consists of a Python script that combines several functionalities:

1. **Web Scraping**: Uses Selenium and BeautifulSoup to automate web scraping of LinkedIn pages. It allows the script to log in, search for contacts, and navigate through LinkedIn pages.

2. **LinkedIn Messaging**: Provides the ability to send connection requests and messages to LinkedIn contacts.

3. **Exclusion List**: Maintains an exclusion list of contacts with whom you don't want to interact.

4. **Translation Services**: Translates messages between English and Spanish, facilitating communication with contacts who speak different languages.

5. **Conversational AI**: Utilizes the Transformers library for creating a conversational AI model pipeline. This allows automated responses to LinkedIn messages.

6. **Bot Status Management**: Monitors messages for specific keywords ("start bot" and "stop bot") to change the bot's status and initiate or stop automated responses.

## How to Use

1. **Installation**:

   - Install the necessary Python libraries using pip:
     ```bash
     pip install selenium beautifulsoup4 webdriver_manager langdetect pandas requests
     ```

   - Make sure you have the Chrome browser installed, as the script is designed to work with Chrome.

2. **Setup**:

   - Edit the `config.py` file with your LinkedIn credentials (username and password).

3. **Running the Script**:

   - Run the Python script `linkedin_bot.py`.

4. **LinkedIn Interaction**:

   - The script will automate the login process and send connection requests and messages to LinkedIn contacts based on your setup.

5. **Managing the Bot**:

   - The script detects messages with "start bot" or "stop bot" to manage the bot's status. This feature is especially important for responsible use of automated interactions.

## Disclaimer

Please be aware of LinkedIn's terms of service and changes that might affect the functionality of this script. Use the project responsibly and avoid actions that could violate LinkedIn's policies.

**Note**: The script was developed in a pre-ChatGPT era and served as an early, low-resource solution for automating LinkedIn interactions.

## Contributions

Contributions to this project are welcome. Please feel free to submit issues, feature requests, or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

