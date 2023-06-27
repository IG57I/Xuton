# HH-Job-Search-Bot 

Welcome to the HH-Job-Search-Bot  repository! This repository is a fork of the original Xuton repository and contains improvements and modifications specific to your needs. HH-Job-Search-Bot is a Telegram bot built in Python that allows users to search for job vacancies on HeadHunter (HH.ru) and view details about each job.

## Usage

To use the HH-Job-Search-Bot, follow these steps:

1. Clone the repository to your local machine.

2. Ensure you have the necessary dependencies installed. You can install them using the following command:

   ```
   pip install -r requirements.txt
   ```

3. Obtain a bot token from the BotFather on Telegram.

4. Open the `config.txt` file in the repository and replace the placeholder `YOUR_BOT_TOKEN_HERE` with your actual bot token.

5. Run the `main.py` file to start the bot:

   ```
   python main.py
   ```

6. Start the bot on Telegram by sending the `/start` command.

7. Use the bot commands and buttons to interact with the bot:

   - Use the `/start` command to initialize the bot and see the welcome message.
   - Click the "Поиск работы" button to start the job search.
   - Use the "Далее" and "Назад" buttons to navigate through the job listings.
   - Enter any other text to see an error message indicating an unknown command.

## Customization

You can customize the bot's behavior by modifying the code in the `Bot` and `Parser` classes.

- In the `Bot` class:
  - Customize the welcome message in the `welcome` function.
  - Modify the keyboard layouts in the `keyboard_start_search_job` and `keyboard_next_and_back` functions.
  - Customize the message sent in response to unknown commands in the `vacancy` function.
- In the `Parser` class:
  - Modify the `__getPage` function to change the search parameters for the job vacancies.
  - Adjust the data extraction and formatting in the `info_to_vac_list` function to match your desired output format.

Make sure to test your changes thoroughly to ensure the bot functions as expected.

## Contributing

Since this is a forked repository, please refer to the original repository for contributing guidelines and information.

## Contact

If you have any questions or need assistance with the HH-Job-Search-Bot  functionality specific to your forked repository, you can reach out to the maintainers of the original repository via the GitHub repository's issue tracker.

Happy job searching with HH-Job-Search-Bot !

Best regards,
Hazardooo
