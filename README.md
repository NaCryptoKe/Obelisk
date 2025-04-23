# Obelisk

## Explanation of each file/directory:

* `Obelisk/`: The root directory of the project.
* bot/: This directory contains the core logic of the Telegram bot.
    * `__init__.py`: This file is required for Python to treat the directory as a package, allowing you to import modules from it.
    * main.py: This is the main script that will be executed to run the bot. It typically initializes the bot, sets up handlers, and starts the bot's event loop.
    * `handlers.py`: This file contains the functions that handle different types of updates from Telegram, such as receiving messages, commands, and button clicks.
    * `ocr_processor.py`: This file contains the logic for performing OCR (Optical Character Recognition) on images. It might use libraries like pytesseract.
    * `google_sheets_manager.py`: This file handles the interaction with the Google Sheets API, allowing the bot to read from and write to spreadsheets.
* `config/`: This directory contains configuration files for the bot.
    * `__init__.py`: Makes the directory a Python package.
    * `config.py`: This file might contain general configuration settings for the bot, such as API keys, bot settings, and other parameters.
    * `credentials.json`: This file (if used) stores the credentials required to access the Google Sheets API. It's important to handle this file securely.
* `utils/`: This directory contains utility functions used by the bot.
    * `__init__.py`: Makes the directory a Python package.
    * `logger.py`: This file sets up the logging for the bot, allowing you to record events, errors, and debugging information.
* README.md: This file is a Markdown file that provides documentation for the project. It typically includes information about the bot, how to set it up, and how to use it.