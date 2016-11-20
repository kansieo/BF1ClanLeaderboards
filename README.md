# BF1ClanLeaderboards
Quick, Dirty Battlefield 1 Statistics.  In PHP/Bootstrap with a bit of JQuery on the side.

Pulls data from the Battlefieldtracker.com API.  Displays leaderboards in a sortable Google Charts Table format.

# Setup
peeps.txt:
Put your clan roster into 'peeps.txt' names separated by '|'.

index.php:
Modify $system to match your platform (1 = xbox, 2 = PS4, 3 = PC).
Modify $clanname to your clan's name.
Modify $TRNAPIkey to your https://battlefieldtracker.com/site-api API key.

That's it.

# Usage
Visit page in a browser and it'll cache data for each player in the roster, updating every 15 minutes or so, or when a name is clicked in the table.

# Info
Still very much under development, much needed refactoring and simplification.
Contact me at kansieo(at)gmail(dot)com if you need help putting this on your server or if you're a better coder than me and want to help refactor.
