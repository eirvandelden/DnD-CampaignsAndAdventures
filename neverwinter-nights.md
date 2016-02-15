# Introduction

This campaign is a tabletop adaption of the superb video game Neverwinter Nights by Bioware. The campaign I have played was not meant to be a true adaption of the original game, thus there might be changes in this campaign from the actual video game. If you like anything that you see from this campaign, you are free to use it in your own game.

I have tried to keep this campaign system-agnostic. I happen to have played this campaign using the D&D 5th Edition rules. If you happen to also play 5E AND use the Game Master 5 app by Lion's Den, then you can import the XML files I have used in this campagin from my github!

If you are a D&D fan and haven't played this game, I can really advise it, both as a DM and as a player!

## Background

About year ago, a new plague spread in the city of Neverwinter: the Wailing Death. The Wailing Death quickly spread to become an epidemic. A quarter of the city now lies dead in the streets, rotting where they fell. Half of the city has become ill, riots roam the streets and a food shortage is starting. If a cure is not found soon, it might spell doom for the city once called "the Jewel of the North"

Lord Nasher Alagondar has commanded his most trusted commander, Lady Aribeth de Tylmarande to find a cure. Desther, the leader of the Helmites (a priestly order), has been called in to assist the sickly. She has opened the Heroes Acadamy to train new adventures to assist her in finding a cure. Waterdeep has sent aid, in the form of three creatures that offer the last components for the cure.

## Campaign Synopsis

This campaign in setup as follows:
  - Chapter 0: An introduction within the Heroes Academy where you introduce the game, its rules and the story. During the PCs "examination", the Heroes Academy is attacked and the Waterdhavian Creatures fled.
  - Chapters 1-3: The PCs are employed by Seldra to retrieve the Waterdhavian Creatures. These chapters can be run in any order
  - Chapter 4: The betrayal by Desther and then searching and apprehending him

## What the PCs do not know

- Lady Aribeth is actually her twin-sister Seldra.
- Seldra and Desther are the cause of the Wailing Death. The Helmites has been spreading the disease
- The "Waterdhavian creatures" are needed to make a large batch of an improved Wailing Death, that turns people into controllable, metal enhanced zombies
- Aribeth is still alive, but captured within Helm's Hold

## Changes from the original campaign

In the original campaign…
- …there was only Lady Aribeth. There is no mention of an evil version Seldra
- …the "cure" wouldn't do anything. There is no mention of an "improved Wailing Death"
- …the Wailing Death only kills. There is no mention of grafting or transformation into metallic zombies

# Chapter 0: Heroes Academy


## How Does Attacking Work

## Exams

## The Assault

## Save the Waterdhavian Creatures

# Chapter 1: The Scar

## Peninsula Main Gate

## Save Master Jons and Ms. Dulcimae

## Defeat the Sewer Bandit
## Tanglebrook Estate
## The Prison
### Entering the Prison
### Ground Floor
### Defeat the Intellect Devourer

# Chapter 2: Blacklake District

# Chapter 3: The Docks

# Chapter 4: Helm's Hold

Old XML content
<?xml version="1.0" encoding="UTF-8"?>
<campaign version="5">


<!-- Neverwinter Nights: The Scar District -->
<encounter>
  <name>Scar5: Entering the Prison</name>
  <text>Several ways inside; either via the heavily guarded front-door, the magically guarded burning way, or the sneaky swamp path.</text>
  <combatant monster="Bandit Captain" label="Guard 1" />
  <combatant monster="Bandit Captain" label="Guard 2" />
</encounter>
<encounter>
  <name>Scar6: Figuring out inside</name>
  <text>Make a squarish path. Each piece of the path is cut of with bars. The prisoners let brutes through and pepper the PC's with ranged attacks. Falling back each time</text>
  <combatant monster="Bugbear" label="Bugbear" />
  <combatant monster="Scout" label="Harasser 1" />
  <combatant monster="Scout" label="Harasser 2" />
</encounter>
<encounter>
  <name>Scar7: Defeat The Intellect Devourer</name>
  <text>
    - Weet van de Thran, omdat het zelf psychic is.
    - Alligned met de Illithids
    - Wil een leger maken om zich te beschermen
    Threatens the PC's:
    * "Join me, so we might survive"
    * "I have seen the truth, I have seen the future! We must prepare their coming"
    * "Defeating me will mean the doom of us all!"
    * "You know nothing, and it wil be your doom"
    * "We must join the new master or be destroyed by the Dark Ones!"
    Treasure:
    1900 cp, 1000 sp, 40 gp, Moonstone (50 gp), 2 x Sardonyx (50 gp), Zircon (50 gp)
  </text>
  <combatant monster="Intellect Devourer" label="Intellect Devourer" />
  <combatant monster="Bandit" label="Host 3" />
  <combatant monster="Bandit" label="Host 2" />
  <combatant monster="Bandit" label="Host 1" />
  <combatant monster="Bandit Captain" label="Initial Host" />
</encounter>
<encounter>
  <name>Scar 8: Loot!</name>
  <text>300 GP, Spell Scroll (Compulsion), Potion of Frost Giant Strength, Potion of Superior Healing</text>
</encounter>
<!-- Neverwinter Nights: Blacklake District -->
<encounter>
  <name>Blacklake 1: And now the want us dead</name>
  <text>
    When the PC's enter Blacklacke district, they hear a woman cry out for help. This is a ruse, setup by a bunch of assassins, sent to kill the PC's.
    - All assassins have a poison filled tooth
  </text>
  <combatant monster="Sahuagin Priestess" label="Lady in need" />
  <combatant monster="Hobgoblin" label="Thug 1" />
  <combatant monster="Hobgoblin" label="Thug 2" />
</encounter>
<encounter>
  <name>Blacklake 2: Desther and the grocer</name>
  <text>
    - Players meet Desther
    - Grocer Devaron is being harassed, being protected by Priests of Rathma
    - Mob is angry at grocer for selling his supply. Grocer didn't know his sell (for a good price) would lead to such havoc
    - First mention of Meldanen
    - The Grocer's nephew, Samuel, is missing. He works in Devarons shop. He wast last seen out back
  </text>
</encounter>
<encounter>
  <name>Blacklake 3: Investigations</name>
  <text>
    Possible NPC's:
      1) Eldery man, Duran. Duran is the owner of a carriage company. He knows Meldanen as someone who likes to be alone, which everyone has a right for. He's a bit grumpy, but so are a lot of rich people. On a DC 20 check, he doesn't look as hungry, nor as urgent to get to the groceries, he is only there to act as if he is hungry. Duran has done business with Meldanen, he has transported creatures for. In he return, he has a received a Sylph (DC 25).
      2) Fat woman, Lady Arisa. Lady Arisa is a member of the city council. She finds Meldanen an irritating man, who does not behave as a lord should. She wants to leave as quickly as possible and uses the hunger as an excuse. On a DC 20, it is apparant that there is something she is not saying. Lady Arisa, has used her influence to fake papers. In return, she has received her own Halfling.
      3) His butler Jenkins; halfling, has a new job at the Home of the Elderly. He did old the dirty work for Meldanen (he calls it "cleanup"), but deathly fears retribution. He suspects Meldanen has put a spell on him to track him. He only gives up real information for a large sum of money (1,000GP).

      When walking away from Jenkins, it's night.

    - Meldanen has bought all new shipments of food of the last week
    - DC 5: When the Meldanen has always been grumpy, ever since he arrived in Neverwinter two years ago
    - DC 10: Meldanen lives on Mime streets
    - DC 10: He hasn't been seen in a week
    - DC 15: He has more guards in front of his house
    - DC 15: His butler, Jenkins, has been fired
    - DC 20: Meldanen is a wizard, according to rumours he was once an adventurer, but stopped being one all of a sudden
    - DC 25: Meldanen's name has been mentioned once, with shady dealings.
    - DC 25: Get key of Jenkins
  </text>
</encounter>
<encounter>
  <name>Blacklake 4a: Entering Blacklake via Jenkins</name>
  <text>
    DC 25: Get key of Jenkins
    Jenkins was payed well by Meldanen. He never entered the basement, that was forbidden area. Jenkins knows Meldanen is a dangerous wizard, who also has an apprentice. He sometimes did jobs that included getting "packages", which usually were big masked cages.
    Jenkins wants to be paid 300GP, so he can escape Neverwinter and assume another identity, in return for the key. He would rather die than give it up for much less.
  </text>
</encounter>
<encounter>
  <name>Blacklake 4b: Entering via the front door</name>
  <text>
    Het buurmeisje van tegen over zit vanuit een steegje het huis te bestuderen. Ze vind dat er iets raars binnen gebeurt.
  </text>
  <combatant monster="Bugbear" label="Gnoll Guard 1" />
  <combatant monster="Bugbear" label="Gnoll Guard 2" />
</encounter>
<encounter>
  <name>Blacklake 5: Guards on the inside</name>
  <text>
    These two guards are stationed to keep guard of a door to the cellar. They are here to keep people IN, not out.
  </text>
  <combatant monster="Bugbear" label="Gnoll Guard 1" />
  <combatant monster="Bugbear" label="Gnoll Guard 2" />
</encounter>
<encounter>
  <name>Blacklake 6: The Cellars of Meldanen's Mansion</name>
  <text>
    - Vanuit daar vinden ze een deur naar de ondergrondse gevangenis cellen, waar o.a. Samuel zit. Samuel blijkt een Thiefling te zijn. Er zijn allemaal cellen met verschillende wezens
    - Verder is een ruimte voor zijn apprentice
    - Daarna vinden ze de Dryad. Na heel even met haar te spreken, verschijnt Meldanen en begint meteen aan te vallen.
    - Meldanen is altijd chagrijnig tegen iedereen geweest omdat hij liefdesverdriet had wegens het verlies van zijn vrouw en kinderen in een aangevallen caravan
    - Heeft een nieuwe liefde gevonden in de Dryad, en zij in hem. Heeft eten verzameld om voor de Dryad te zorgen
    - Wil haar niet kwijt raken, dus houd hij haar geheim
    - Hij zou ook “magical abominations” sparen.
  </text>
  <combatant monster="Evil Mage" label="Meldanen" />
  <combatant monster="Evil Mage" label="Apprentice" />
  <combatant monster="Bugbear" label="Gnoll Guard 1" />
  <combatant monster="Bugbear" label="Gnoll Guard 2" />
  <combatant monster="Dryad" label="Dryad" role="ally"/>
</encounter>

<!-- Neverwinter Nights: Docks District -->
<encounter>
  <name>The Docks chapter</name>
  <text>
  - Find Yuan-Ti
  - Heet Gulnan
  - Is er achter gekomen dat de lijken makkelijk metaal opnemen
  - Maakt een zombie leger van metaal enhanced mensen
  - Heeft twee groepen tegen elkaar in gespeeld
      - De Fire Knives en de Blood Sailors
      - De Yuan-Ti heeft de Blood Sailors over genomen. Zij gebruikt de Wailing Death om knives te graften aan de leden. De Blood Sailors hebben een bloedige oorlog begonnen, en grotendeels gewonnen, met de Fire Knives. Ze hebben een ultimatum gekregen, 100,000GP betalen of weggevaagd worden.
      - De Fire Knives vallen nu iedereen aan, in de hoop het geld bij elkaar te krijgen.

  when entering the docks, they are surprised by a dead body of an Augmented Fire Knife falling from a roof.
  find a map on an enemy?
  </text>
</encounter>
<encounter>
  <name>The Docks 1: Introducing the Docks</name>
  <text>
    Skill/Combat Encounter
    When the PC's arrive, read:
    You walk towards the wall that separates the Docks from the rest of Neverwinter. The guards must have heard of your work for Lady Aribeth, as they open up


    Long Jump: move 10ft jump up to STR feet.
  </text>
  <combatant label="Fire Knife runner" />
</encounter>
<encounter>
  <name>The Docks 2a: The Neverwinter Theater</name>
  <text>
    Primary Skills DC 20: Stealth, Sleight of Hand, Investigation
    Secondary Skills DC 15: Perception, Bluf, Diplomacy, Performance
    Skill challenge: 6 successen voor 3 failures.
    Secondary Skills give a +2 bonus to Primary Skills

    - meerder fire knives in het theater
    - zij zijn verstopt tussen/onder het publiek
    - ze moeten de fire knives proberen te vinden
    - Einde van de challenge; zakje pruimen

    At the end of the Encounter, they capture a Fire Knife. He can note that he found a sack of fruit, prumes he believes, on some of the Blood Sailors during previous confrontations.
    Treasure: a sack of prumes, Potion of Healing (2d4+2)
  </text>
</encounter>
<encounter>
  <name>The Docks 2b: The Neverwinter Bridges</name>
  <text>
    - three bridges, with a bomb under one of the three (make three notes and lay them down by random)
    - the PC's must find which of the three bridges contains the bomb
    - waves of Fire Knives try to stop the PCs. Some Blood Sailor converts try to stop them all.
    - When defeated, they can tell that the Blood Sailors always smell stale

    Three waves of Fire Knives try to stop the PC's.
    Note: One of the Blood Sailors has a walking cane as an arm.

    When a Fire Knife is captured, he can tell that Bloodsailor's smell musty.
    Treasure: Potion of Healing (2d4+2), Potion of Fire Breathing (3x DC 13 Dex; 4d6/2;), Potion of Frost Giant (Str = 23; 1 hour)
    XP: 3x650XP
  </text>
  <combatant monster="Bandit" label="Fire Knive 1" />
  <combatant monster="Bandit" label="Fire Knive 2" />
  <combatant monster="Bandit" label="Fire Knive 3" />
  <combatant monster="Bandit" label="Fire Knive 4" />
  <combatant monster="Bandit" label="Fire Knive 5" />
  <combatant monster="Ice Mephit" label="Fire Knive Water Wizard" />
  <combatant monster="Zombie" label="Blood Sailor 1"/>
  <combatant monster="Zombie" label="Blood Sailor 2"/>
</encounter>
<encounter>
  <name>The Docks 3: Sherry</name>
  <text>
    Treasure: Player's find a walking cane on Sherry
    Normal encounter: solo
  </text>
  <combatant monster="Spectator" label="Sherry" />
</encounter>
<encounter>
  <name>The Docks 4: The Yuan-Ti</name>
  <text>
    - underneath the Neverwinter Home for the Elderly
    - when they guess correctly where the Yuan-Ti is, they capture the yuan-ti off-guard (hard encounter)
    - when they guess wrong, the Yuan-Ti is prepared (deadly encounter)
    - three encounters: she starts in a glass research thingy, when the yuan-ti is 'defeated', she retreats to another glass thingy and activates two or three new zombies.

    Treasure: 2000 cp, 1100 sp, 80 gp, Bloodstone (50 gp), Chalcedony (50 gp), 3 x Jasper (50 gp), Onyx (50 gp), Star rose quartz (50 gp), Zircon (50 gp)
    XP: 3x 525XP
  </text>
  <combatant monster="Zombie" label="Zombie 1" />
  <combatant monster="Zombie" label="Zombie 2" />
  <combatant monster="Zombie" label="Zombie 3" />
  <combatant monster="Yuan-Ti Pureblood" label="Yuan-Ti" />
</encounter>
<encounter>
  <name>The Cure</name>
  <text>
    - Verwachting: ze komen de ingredienten wel brengen, maar zijn huiverig voor Lady Aribeth. Ze is echt geintresseerd in de ingredienten en wil echt graag het drankje maken. Ze ziet het zelf ook echt als een "Cure", maar alleen een cure voor de zwakheid van het lichaam, niet de Wailing Death.

    - when the Pcs reach ARibeth, she is in discussion with Desther. He believs it was wrong to trust "young whelps" and he believes to PCs will be too late. Aribeth says to trust that the PC believe that they can do good and they should believe in them.

    - Ritueel met Desther die de pot omgooit en ontsnapt
    - Aribeth is oprecht ontzet

    Treasure: 5 Potions of Healing (2+2d4), 5 Acid Flask (4sq; 2d6 acid), 350 GP
    XP: 900 XP
  </text>
</encounter>
<encounter>
  <name>Neverwinter: Desther's escape</name>
  <text>
    If the PCs are in the vicinity, they get the change to defeat Desther early.

    Skill Challenge:
      6 Success before 3 failures

      DC 15
      Primary: Acrobatics/Athletics
      Secondary: Perception, Streetwise
  </text>
  <combatant monster="Desther"/>
</encounter>

<encounter>
  <name>Helm's Hold: The Dungeon Delve</name>
  <text>
    - Try to gain entry to Helm's Hold
    - Lot's of priests (spellcasters), some lesser zombies
    - Two paths to take. If the PC's take the time to inspect either path, they hear screaming from the basement and arguing from the upper levels:
      - Basement: they find a prison. Within the prison is a cell block with the real Lady Aribeth and Deekin. Lady Aribeth explains that she was ambushed and imprisoned over a year ago her sister Seldra. Though Seldra ordered her death, Desther has kept Lady Aribeth alive, torturing her for knowledge of the location of the Thran (of which she has no idea what it might be).
      - Up leads to "Helm's Hold: Facing Desther"

    XP: 900
    Treasure: 230 GP
  </text>
  <combatant monster="Zombie" label="Zombie 1" />
  <combatant monster="Zombie" label="Zombie 2" />
  <combatant monster="Zombie" label="Zombie 3" />
  <combatant monster="Zombie" label="Zombie 4" />
  <combatant monster="Thran Acolyte" label="Acolyte 1" />
  <combatant monster="Thran Acolyte" label="Acolyte 2" />
</encounter>
<encounter>
  <name>Helm's Hold: Facing Desther</name>
  <text>
    - When the PCs go up, read:
    Going up the stairs you hear the arguing. TK Describe the scene
    - If Lady Aribeth is present; read
    - TK: Seldra die geshocked is dat Aribeth leeft

    Read: Aribeth spawnt een vleugel en vliegt weg en laat Desther alleen.

    - Use the last Shadowfell Keep map
    - Desther is zijn eigen leger aan het bouwen

    XP: 1600
    Treasure: 1720 sp, 70 gp, Chalcedony (50 gp), Citrine (50 gp), 3 x Jasper (50 gp), 2 x Moonstone (50 gp), Quartz (50 gp), Sickle of Warning (Weapon of warning; monk weapon), Teapot of Endless Tea (Decanter of Endless Water), Hunters Sniper Rifle (See Above), Warpick of Wounding (See Above), 5 Potions of Healing
  </text>
  <combatant monster="Zombie" label="Zombie 1" />
  <combatant monster="Zombie" label="Zombie 2" />
  <combatant monster="Zombie" label="Zombie 3" />
  <combatant monster="Thran Acolyte" label="Acolyte" />
  <combatant monster="Desther" label="Desther" />
</encounter>

<!-- NPCs -->
<npc>
  <label>Seldra de Tylmarande</label>
  <name>CR 10, Half elf</name>
  <size>M</size>
  <hp>152</hp>
  <ac>18</ac>
  <type>Humanoid (half-elf)</type>
  <alignment>White</alignment>
  <cr>10</cr>
  <description>
- Sister of Aribeth de Tylmarande
- Has a disease that makes her weak
- Met the Thran, via their scout ship, the Ravager
- Now works for the Thran and has been upgraded to not be weak
- Was ordered to test a plague on humans to accept metaal into their bodies
- Captured and replaced her Twin Aribeth
  </description>
</npc>
<npc>
  <label>Lady Aribeth de Tylmarande</label>
</npc>





</campaign>