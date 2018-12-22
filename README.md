# DnD-Discord-Bot BETA RELEASE
## About
A Discord Bot for D&amp;D Character Creation, Maintaining, and Progression

Unlike my previous bot this will be closed-source.  This repo is made only for install & usage instructions as well as bug tracking and feature requests.

## Adding D&DBot

Follow this link: https://discordapp.com/oauth2/authorize?client_id=481910793697493011&scope=bot&permissions=379968

You can try the bot / get support for it in this discord: https://discord.gg/XhtCeH9

## Usage
- !createcharacter [name] -- gets you started on the character creation
- !erasecharacter [name] -- deletes a character CANNOT BE UNDONE WITHOUT RECREATING !createcharacter
- !changechar [name] -- changes you to a different character, leave input blank if you want a list of your characters
- !help -- tells you to come here
- !bugreport [bug] -- allows users to report a bug to me
- !featurerequest [feature] -- allows users to request a feature from me
- !r -- explains usage of the rolling command
- !changeprefix [newprefix] -- allows Administrators on servers to change the bot's prefix to whatever they want, (@,#,$,%,etc)
- !changelog -- shows the most recent changes

ex: !r2d20 - rolls 2 d20s

ex: !r5d10 + 1 - rolls 5 d10s then adds 1 to each roll (spacing does not matter)

ex: !r3d4 -5 - rolls 3 d4s then subtracts 5 to each roll (spacing does not matter)

- !coinflip - flips a coin
- !stats [stat] -- use !stat to sell all of your sheet, !stat ch[aracter], !stat sp[ell], !stat sk[ills], !stat eq[uipment] to see specific pages **NOTE:** b[lah] 'lah' is optional in command, meaning !stat ch shows the same as !stat character.

**BELOW COMMANDS ARE CASE SENSITIVE FOR CHARACTER SHEET MODIFYING** 

- !kset [dict] [item] [what to set it to] -- The clunkiness of this will be fixed later for easier management

- !kadd [dict] [item] [what you're adding to it] -- clunkiness will be fixed later

- !kdel [dict] [item] [what you're subtracting from it] -- clunkiness will be fixed later

**NOTE:** These are the ONLY 3 commands to modify Skills, CharacterDescription, Modifiers, Stats, Coins and SavingThrowStats currently.

ex: !kset Coins Electrum 500

ex: !kadd Coins Gold 5

ex: !kset Skills AnimalHandling 6

ex: !kadd Skills SleightOfHand 1

ex: !kset CharacterDescription Age 500

ex: !kdel CharacterDescription Age 1

ex: !kset Modifiers Str 5

ex: !kdel Modifiers Str 1

ex: !kset Stats Con 10

ex: !kset SavingThrowStats Wis 500000 -- This is the Saving Throws Modifiers mini-page.

- !set [attribute] [whatever] -- Case sensitive for now, used to change items on the character sheet

**NOTE:** This only works with items on CHARACTER SHEET and SPELLS & CANTRIPS which can be viewed using !stat ch or !stat sp

ex: !set XP 500

ex: !set Alignment Neutral Evil

- !add [attribute] [whatever] -- Case sensitive as well

ex: !add CurrentHP 5

ex: !add Treasure Gold Chain

ex: !add Equipment Bone Club

- !del [attribute] [whatever] -- Case sensitive

ex: !del CurrentHP 2

ex: !del Personality Bad Guy

ex: !del Treasure Gold Chain

- !appearance [Age] [Height] [Weight] [Eyes] [Skin] [Hair]

ex: !appearance 20 6'0 180 Blue Tan Brown

**FOR SERVER OWNERS**
Upon adding the discord bot to the server, make sure it has permissions to send messages.  That is about all it will need.

**FOR PLAYERS**
You can also message the bot in private, however it will have !d4, !d6 !d8 !d10 !d12 !d20 and !d100 commands as well as !coinflip to assist in playing the game itself.  These commands are probably best done in your public discord chat, but discuss with your DM how you want to handle it.

* To create a character, use !createcharacter [Name]

From there, the bot will guide you on what you need to do to get set up.  Again, this process best done in private, if multiple people are making characters in 1 chat, it might get confusing.

**If you're using a custom class / race**, you can enter "Custom" on those fields, but be aware that you'll be in charge of choosing your proficiencies and other relevant info to your character.  Meaning manually setting the attribute fields using the proper commands.  In other words, more work for you.

Your character will be available on ANY server that the bot is present on.  Your character progress is persistent and saved.  
Due to character informaton being stored on my own server, **You are limited to 3 characters per discord account**.  There will be an option to donate to unlocked more / unlimited characters.  Again, this is a space issue.  If more people donate, I can afford better hardware, which means bigger harddrives, which means I can afford to store all your character data.



## Donator Benefits
* Unlimited character slots
* Use !donate for more information

More benefits to come...


# Legal Disclaimer Surrounding GDPR

By using this bot on your server, you should be made aware that the bot has access to see EVERY message you send in ANY channel that it has access to.  All discord.py bots have this capability, and I am constantly updating my logging techniques to better handle bugs that occur.  If you are uncomfortable with that, you have the option of not using this bot.

**I do not distribute, sell, or use this information for anything other than debugging and reporting abuse to Discord.**

Again, If you have any issues with this, don't use the bot, or contact me if you need clarification on what I'm logging.
