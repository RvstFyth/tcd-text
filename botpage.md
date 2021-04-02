Join the world of the undead. almost everyone you know has died...The world is in pieces but a few strong survivors are still alive trying to make it out there...
# The Crawling Dead
Text based zombie survival game. 
## Getting started

In all example commands below `<argument>` means a optional argument, `[argument]` means it's required.  
This bot has more then 100 unique commands that can influenc game states, making it impossible to explain them all on this page.  
You can join our support server if you need any help. 

Use `cd register [name]` to create a account for the crawling dead. You should receive a DM from the bot after that with some info to get started.  
The first thing you should do is check your inventory for a weapon. You can use `cd inventory` or `cd iv` for this. After you have found the weapon, 
you can equip it with `cd equip [item]`. `[item]` can be the item name or the item id.  
If you check `cd profile` you can see what you are wearing and some more information about your character.
## Usefull commands to stay alive
`cd heal`  
`cd eat [item] <amount>`  
`cd drink [item] <amount>`  
`cd use [item] <amount>`  
`cd inf` Lists your health, hunger, thirst and inventory space  
`cd item [item]` Query item info  
`cd craft [item] <amount>`
## Supplies
### Looting
You will need supplies to survive. For this you can use the `cd loot` command. When triggered you get a prompt with a few locations. Each location holds a different
loot type. You can select a location by reacting with the same emoji.  
### Garden
You have a garden where you can grow your own food. Use `cd garden` or `cd g` to see information about your garden.  
The `cd hourly` command will give you random seeds. You can plant these with `cd g plant <amount>`. You can also plant specific seeds, which are found while looting.
To plant these `cd g plant [id] <amount>`. This only works with the item id of the seed you want to plant. Random seeds are excluded from inventory count and displayed in the `cd g` command.
Specific seeds are placed inside your inventory, and do take slots. When your crops are ready, harvest them with `cd harvest`.
### Fishing
Fishing requires a rod and bait. Bait can be found with the `cd dig` command. The amount you will get from it depends on the weather. When it's raining you can find more earthworms!  
Rods can be found or crafted. See `cd i 200` for a craftable rod.
### Hunting
Sometimes a hunting event is triggered in a channel. You can shoot it with `shoot` (without prefix). The player that is able to kill it, will get the reward!
### Cooking
Raw fish and meat should be cooked before you eat it. You can get sick by eating raw food. Being sick has some annoying side effects, and takes some time to recover.  
Use the ` cd item [name]` command for finding possible recipes for a item, and the `cd cook [item] <amount>` to start cooking.
The `cd cook` command lists the things you are cooking. The `.cook collect` command collects all the things that are ready.
  
A campfire is required for the `cd cook` command. Campfires are bound to a channel, and there can only be one campfire active in each channel.
Creating a fire requires the fire skill (you can get this by reading the scout book) and a 'fireplace kit'. 
After the fire is active, everyone in the channel can use it or add items to it. You can extend the fire timer by adding items to it `cd fire add [item]`. Use `cd fire` command to see if there is a active fire.   

### Market
The market can be accessed with the `cd market` command. This is where you can sell your items, or buy items from other players.
## Shelter
The shelter gives some advantages and upgrades to unlock more commands. See `cd shelter` to get started. The number next to the upgrade name is the level or 0 when not build yet.
## Curing diseases
When you eat raw fish or meat you can get salmonella. To cure salmonella you have to eat a activated charcoal tablet. After taking them it takes a few hours before you are cured.
You can speed up this process by eating a multivitamine pill before you take the charcoal tablet. Multivitamine pills boosts the immune system. 
  
When you have influenza, apply same steps as with salmonella, but replace activated charcoal tablet with Zanamivir. Influenza is contagious, so be carefull with commands where multiple players can join, as there is a huge risk you will infect them!  

## Changing the bot prefix
By default this bot reacts on two prefixes, `cd` and `.`.  
You can change the prefix of the bot with `cd server prefix [prefix]`. You will need administrator perms for this!  
Note, this command only replaces the `.` prefix, `cd` can't be replaced. This should be handled by the server owner and discords permissions management.
