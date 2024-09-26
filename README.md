Pokémon Adventure Bot
This is a Telegram bot game that allows users to experience a Pokémon-style adventure. Users can register, start adventures, catch Pokémon, and access various features like Pokédex, inventory, profile management, and leaderboard.

Features
Registration and Nickname Management: Users can register with a unique nickname and change it later.
Start an Adventure: Begin a Pokémon adventure, catch new Pokémon, and explore the game world.
Pokédex: View different Pokémon based on their rarity or other criteria.
Profile: Check your user profile and progress in the game.
Inventory Management: Manage your items, such as Pokéballs and energy.
Leaderboard: Check the top players in the game.
How to Install
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/pokemon-adventure-bot.git
cd pokemon-adventure-bot
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Set up the environment:
Create a .env file and add your Telegram bot token and database connection details:

makefile
Copy code
BOT_TOKEN=your_telegram_bot_token
DB_CONNECTION=your_database_connection_string
Run the bot:
bash
Copy code
python main.py
Bot Commands
Here are some of the commands that users can interact with:

/start: Start the bot and begin the registration process or continue the adventure if already registered.
/📱Pokedex: View Pokémon in the Pokédex.
/🏃‍♂️Start_Adventure: Start your Pokémon adventure.
/🔚End_Adventure: End the current adventure.
/🎒My_pokemons: View your collected Pokémon.
/📋Profile: View your player profile.
/🔴⚪Get_Pokebolls: Get more Pokéballs for catching Pokémon.
/help: Display help information.
Contribution
Feel free to contribute to this project by creating a pull request. You can also open issues for any bugs or feature requests.

License
This project is licensed under the MIT License.
