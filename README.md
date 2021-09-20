# iPhone
Instructions for iPhone App

The iPhone app will have 8 different states:

1. First Time Initialization mode
2. Login in password training mode
3. Login in standard mode
4. Dashboard Mode
5. Importing mode
6. Exporting mode
7. Tools and information mode.
8. Password Recovery Mode

## First Time Initialization Mode
When the program starts for the first time it must:
1. Ask the user to agree to the terms as shown below.
2. Ask the user to create and confirm a password.
3. Ask the user if they want to enter a recovery email.
4. Give the user a randomly created "picture password" with a "remember statement". See Picture passwords below.
5. Switch to Login in password Traning mode


Terms
```
CloudCoin iPhone Edition
Version: September 19, 2021
Used to Authenticate, Store and Export CloudCoins
This software is provided as is with all faults, defects
and errors, and without any warranty of any kind. 
Free from the CloudCoin Consortium. 
```

## Login Traning Mode
The behavior changes everytime the user logs in.
1. The user is promted for their password.
2. If the user has already logged in seven times, go to Login in standard mode
3. The user is show page one of the six picture tables. They are given hits according to the hint table. 
4. If the user chooses the wrong picture, they are corrected and told the correct picture.
5. The user repeats this for six pciture tables. 
6. Go To Dashboard

## Login in Standard Mode
1. The user is promted for their password.
2. The user is show page one of the six picture tables. No hints are given
3. The user repeats this for six pciture tables. 
4. If the user cannot enter their password correctly, go to Password Recovery Mode. 
5. Go To Dashboard


## Dashboard Mode
User sees their balance. 
They have the option to import coins
They have the option to export coins
They have the option to look at tools

## Importing mode
Use existing plans
## Exporting mode
Use existing plans

# Picture Password System

The iPhone App will be the first CloudCoin program that will not store CloudCoin Authenticity Numbers in files. Instead it will only store Serial Numbers
and they will all be stored in one PNG file. 

When coins are POWNed, the ANs will be created based on the user's password. For this reason, we will use a new technique to create very strong passwords that can be remembered using new memory techniques. 

To increase the security, the login will use a combination of pictograms and a traditional password. The first part of the password will be generated by random. The second part of the password will be choosen by the user. 

## Graphics Password

The first time the user uses the program, the system will generate a story for the user using the following logic.

```
"There once was a _(character)__ who was _(verb)_ near a _(place)_ when a magic _(thing)_ appeared. When the _(Character)_ _(verb)_ it, it caused a _(event)_"

Samples:
There once was a viking who was digging near a zoo when a magic chicken appeared. When the Viking studied it, it caused a Ice Age.

There once was a Robot who was talking near a theater when a magic flashlight appeared. When the robot poked it, it caused a time warp.

There once was a Farmer who was drinking near a museum when a magic necklass appeared. When the farmer sat on it, it caused a Fire.
```

There will be six screens that the user will need to go through to log into the program along with a password at the end.


The user will be shown a screen with 32 icons on it. Each icon will have a position of 1 through 32. Each postion shall have its own color and the icon shall be of that color. 

| 1 | 2 | 3 | 4
---|---|---|---
5 | 6| 7| 8
9| 10| 11 | 12
13 | 14| 15| 16
17 | 18| 19| 20
21 | 22| 23| 24
25 | 26| 27| 28
29 | 30| 31| 32


The user will be provided a pictogram and they will be expected to create their own password

Number | Color | Character | Verb | Place | Thing | Verb | Event
---|---|---|---|---|---|---|---
1 | #CC0000 | Minitar      | Swimming | Pyramid     | Bottle | Kicked | Explosion
2 | #FF4500 | Doctor       | Running  | River       | Rabbit | Spit on | Solar Eclips
3 | #FFD700 | Athelete     | Walking  | Mountain    | Skull | Looked at | Metior Shower
4 | #808000 | Business Man | Eating   | Effel Tower | watermellon | Touched | Blizzard
5 | #ADFF2F | Nerd         | Hunting  | Statue of Liberty | Doll House | Rubbed | Wind
6 | #2F4F4F | Gangster     | Fishing  | Hills       | Flag | Sat On | Hurricane
7 | #00808 | Hippy         | Shopping | Desert      | Toy | Threw | Landslide
8 | #00BFFF | Punk         | Reading  | Sea         | Pot | Hugged | Heart atack
9 | #191970 | Princess     | Drawing  | Jungle      | Wallet | Kissed | Fire
 10 | #0000CD | Dentist | laughing | skyscraper | camera |lifted |War 
 11 | #8A2BE2 | cyclops | lounging | park | cell phone | rolled|tornato   
12  | #8B008B | Dragon |  cooking| pond | glasses | sold |tsunami 
13  | #FF1493| Unicorn |  digging|  sewer|  pen| dropped|heat wave  
14  |  	#FFE4C4 |bigfoot  | thinking | dump | flashlight | broke| Plague   
15  | #D2691E | Viking | dancing |  zoo| rock | poked | Miracle  
16  | #BC8F8F |  Witch| sitting | theater | gold nugget | burried |Alien encouter   
17  | #FFF0F5 | Robot |  dressing| bathroom | brick | lost |famine   
18  | #708090 | Cheerleader | working |  Cave| brifcase | pocketed |infestation   
19  |  	#778899 | Farmer | hiding | Palace | picture | washed |time warp   
20  |  	#000000 | Clown |searching  | Carnival | statue | gifted |  Stench
21  | #008000 | Solider | visiting | Party |  necklass| stole |  Ship Wreck
22  |#00CED1  | Pirate | playing | Casino | chicken | displayed |  Oil SPill
23  | #1E90FF | scientist |gardening| Post Office | forgot |  |  Grow
24  | #87CEFA | professor | Sunbathing | Castle | ignored |  |  shrink
25  |#4B0082  |  King| Drinking | Museum |  snake| smelled |  To Disapear
26  |#800080  | Giant | gambling | Forest | hat| measured |  Revelution
27  | #FF00FF | Troll | smoking | Well |  book| ran from |  Ice Age
28  | #F5DEB3 | mermaid | flying | Dog House | wand  | left | mud slide
29  | #A0522D | Dinosaur | Bird Watching | back yard | fairy | studied |  flood
30  | #696969 |Dwarf  | Showering | Airport | flute | avoided |   lighting strike
31  | #CD853F | Vampire | Talking | Football Field | lantern | licked |  animal attack,
32  | #8B0000 | Magistion | Complaining | Gymnasium |  ring | punched |  drought

lifted, rolled, dropped, broke, stabbed, bit, ate, lost,  yelled, 
	currsed, studied, avoided, licked, punched

Earthquake. , wreck, War, tornato, tsunami, 
	heat wave, election, Stampeed, Plague, Miracle, beam of light, Alien encouter, famine, oil spill, infestation, time warp, lighting strike, THunder, flood, 
	animal attack, silence, Party, murder, Sink holde, mud slide, drought, dictaorship, ship wreck. Metriorrite.  
	Give the user a person, verb, place, thing that was adjitive, Event happened
	
EW LOGIN for IPHONE


User opesn the program

is it the first time?
	Yes: Go through the initialization process
	
	No: Go To LOGIN
	
Initialization: 
	Show the user five icons.
	1. Person   Albert Eighten, Minitar, Doctor, Fooball Payjer, Business man, Nerd, Gangster, Athelet, Hppy, Punk, maid, princess, actress, Dentist, 
	Leprican, mermaid, cyclops, Dragon, Unicorn, bigfoot, Viking, Witch, Vampire, Werewolf, Robot, Magitian, nurse, Cheerleader, Troll, Zombi, Farmer, waitress, 
	Nun, Clown, Solider, Pirate, scientist, carpender, professor, Dwarf, Dinosaur, King, Giant, Naked WOman, Bald Man, 
	
	2. Verb   Swimming, running, walking, speaking, eating, hunting, fishing, shopping, reading, drawing, laughing, lounging, shooting,
	cooking, digging, thinking, sleeping, dancing, sitting, dressing, working, hiding, searching, visiting, playing, watching TV, guardening, Sunbathing, Drinking,
	gambling, smoking, flying, sick, 
	
	3. Place  Greate Pyramid, River, mountain, effel tower, statue of liberty, hills, desert, sea, jungle, skyscraper, park, pond, sewer, dump, zoo, theater
	bathroom, Cave, 
	
	4. THing  Bottle, Plate, rabbit, bone, skull, watermellon, doll house, flag, toy, pot, wallet, camera, cell phone, glasses, pen, flashlight, rock, 
	gold nugget, brick, brifcase, picture, statue, necklass, chicken, snake, hat, book, wand, trash can, run, fairy, shoe, flute, cat, lantern, chest, 
	pipe, ring, wrench, purse, space ship, 
	
	5. verb Kicked, spit on, Shot, looked at, touched, rubbed, Sat on, Threw, hugged, kissed, lifted, rolled, dropped, broke, stabbed, bit, ate, lost,  yelled, 
	currsed, studied, avoided, licked, punched
	
	
	6. Event and then there as an Earthquake. Explostion, Solar Ecips, Rain, Snow, Wind, Hurricane, Landslide, Horse race, Fire, wreck, War, tornato, tsunami, 
	heat wave, election, Stampeed, Plague, Miracle, beam of light, Alien encouter, famine, oil spill, infestation, time warp, lighting strike, THunder, flood, 
	animal attack, silence, Party, murder, Sink holde, mud slide, drought, dictaorship, ship wreck. Metriorrite.  
	Give the user a person, verb, place, thing that was adjitive, Event happened
	
	
	A "Doctor" was "speaking" near the "Great Pyramid" when s/he found a magic "Skull". The "Doctore "touched" it and it caused a "earthquake". 
	
States of rememberance
1. First time logggin int, all other pictures are not there. Color and position are the same. There is a golden border around correct ones. 
2. Second time logging in, There is a ghost of the other images. Golden boarder still is there. 
3. Third, fourth and fifth time, The other images become clearer until on the sixth one, they are all gone. 
4. Sixth one all images can be seen. Golden boarder is still there.
6. Seventh, golden boarder is only half way there.
8. Golden boarder is gone. But if they make a mistake it will be corrected.
9. Password is forgotten and delted. 

Then it asks for their password.


==============================
We will use the new "Store in Mind" technology for the iPhone. There is one catch. We need to store the serial numbers of the coins. 
There will be three PNGs that will act as databases for the serial numbers and they will use the PNG file format.

Files include:
1. cloudcoin.bank.png
2. cloudcoin.counterfeit.png
3. cloudcoin.fracked.png
4. cloudcoin.limbo.png

==============================
Ace at Freedomfest
-300 Million Coins
-Central Banks
-

