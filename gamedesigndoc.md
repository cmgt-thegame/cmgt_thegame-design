# Game Design Document (CMGT: The Game)
2022-06-08


<!-- TODO: insert conceptart pics -->

## 1. Global Idea

Kind of Fun: Discovery & Challenge
Game Mechanic: Fight & Explore
X-Factor: Docenten, Schoolgebouw & Rotterdam

pixelart
topdown 2 point front isometric
32~ colors
inspiration: enter the gungeon / binding of isaac / minecraft dungeons / hack n slash / rogeu

Doelen: Areas exploren en ememies vechten
Endgoal: Defeat endboss and go to next floor

## 2. Eerste Conceptschets

<!-- TODO: insert eerste conceptschets -->

## 3. Doelgroep

CMGTers
- Studenten (18-29 jaar)
- Docenten (25+)
  
De twee hoofddoelgroepen bestaan uit studenten en docenten van CMGT die toevallig langs de arcade machine komen. Ook zullen er een paar mensen van andere studies of die op bezoek zijn langs lopen. 

De doelgroep bestaat voor het grootste gedeelte uit ervaren gamers vanuit veel verschillende genres. Ook hebben de meeste mensen in de doelgroep ervaring met game design.

Omdat de arcade machine een kleine tijdverdrijf is (Bijvoorbeeld in de lunchpauze) en je niet mensen onproductief wil maken moet de game kort en duidelijk zijn. Ook moet het niet te moeilijk zijn om te zorgen voor een ontspannend/satisfied gevoel.

Daarom moet de game in het begin makkelijk zijn en gefocust zijn op exploration. Later kunnen er een paar moeilijkere elementen bijgevoegd worden. Het heeft een lage "skill floor" nodig.


### Bartle Player Type
Het is lastig in te delen welke bartle player type deze doelgroep is aangezien het een brede groep players is. Mijn gok is dat het redelijk verdeelt is en er van elke soort wel evenveel mensen zijn. Hier zou nog grondig gebruikersonderzoek naar gedaan moeten worden.

### NewZoo Player Type
Ook hier heb je waarschijnlijk weer van elke type wel een boel mensen. Wel is het merendeel van de mensen in het verleden een committed gamer geweest en is tegenwoordig iets meer casual. Die valt in de categorie (The Lapsed Gamer)

Waarschijnlijk zijn dit de 4 groepen die het meest voorkomen: (deze komen sowieso al veel voor in een gemiddelde populatie)
- The Lapsed Gamer
- The All-Round Enthusiast
- The Popcorn Gamer
- The Time Filler

## 4. Platform

De game word als hoofdplatform voor de CMGT Arcade machine ontwikkeld. Dit heeft een 16:9 1080p scherm. 2 player input met per player een joystick en 6 button.
Ook willen we het speelbaar maken voor normale desktop/web.

CMGT Arcade
- joysticks & buttons

Web (Desktop)
- keyboard

De game is mainly singleplayer maar we willen er ook een mogelijkheid voor local co-op in maken. Dan werk je samen om hetzelfde doel te bereiken.

## 5. Mechanics

### 5.1 Mechanics

Main Mechanics:

1. Move

2. Attack (hack sword)

3. Dash

Combos:
- Dash + Attack 

### 5.2 Regels

Een player kan vrij rondlopen door het level, interacten met items en deuren openen. Bij het binnenkomen van een nieuwe kamer worden de enemies wakker en moeten die bevecht worden.

De `floor` (een samenkomst van meerdere `rooms`) is procedurally gegenereerd met een vaste compositie van soorten rooms. De eerste floor moet een generic hogeschool rotterdam wijnhaven feel hebben.

Je hebt als player de `energy bar`, wanneer je aangevallen word gaat deze bar naar beneden. Als deze op 0 staat ben je uitgeput en ben je gameover. Om energie erbij te krijgen kun je items of buffs gebruiken.
De energybar bestaat uit 3 delen die per deel ook half kunnen zijn. Dit zorgt voor een scale van 0-5. Het kan ook hoger dan de max komen en met een buff kan het max permanent hoger worden.

Bij het vechten obtain je `XP` punten, die kan je later gebruiken om buffs van te krijgen. Ook word de totale XP gebruikt om je op een leaderboard te kunnen plaatsten.

De eerste floor moet ongeveer 5 min speeltijd zijn bij een gemiddelde playthrough. Op het einde laten we zien hoelang je over het level hebt gedaan voor eventuele speedrunners. (Hier komt dan ook een scoreboard voor)

De balangrijkste dingen die een player doet is areas exploren en enemies vechten. Het eindgoal per floor is de endboss verslaan en advancen naar de volgende floor. Totdat je bij de laatste floor bent aangekomen (in de MVP is er maar 1 floor) en dan heb je die run gewonnen en krijg je je stats te zien.

### 5.3 Entities

De enemies zijn op hol geslagen IoT robots, waar je later in het verhaal meer over te weten komt. Elke robot heeft zijn eigen karakteristieken en vormgeving. 

Elke floor heeft een `endboss` deze moet je verslaan om die floor te halen. Na het killen van de endboss krijg je rewards in de vorm van items, buffs en XP. De endbosses zijn elke keer een CMGT docent.

Sommige speciale rooms hebben ook hun eigen `minibosses` met een eigen verhaal en speciale abilities.


### 5.4 Items

Redbull
- 1 deel erbij (kan extra)

Koffie
- 1 extra deel erbij

Patatje
- 2 delen erbij (tot max)

Bitterballen
- 4 delen erbij (tot max)

Tosti
- Refill (tot max)


### 5.5 Buffs

De buffs worden als permanent item toegepast en de vormgeving is buildingblocks. Om een buff te kopen moet je xp points gebruiken.

Clever (100xp)
- 1 energy bar part added

Iron Man (250xp)
- 25% damage reduction

Front-end (250xp)
- 25% faster moving

Being-a-Boss (500xp)
- 50% more damage to bosses and minibosses

Doelgroep (500xp)
- 25% more damage to enemies


## 6. Thema

CMGT: The Game is in een retro pixelart style. Het is vanuit een topdown 2 point front isometric perspectief. De pixelart tiles in de game zijn 16x16 pixels en een scherm heeft. Een gemiddelde room is 16x12 tiles. Het kleurpallet heeft 36 kleuren, waarvan 8 hoofd gradients. Het licht valt in het algemeen vanaf boven links.
De grootste inpiratiebronnen van de style zijn: Enter the Gungeon / Binding of Isaac / Minecraft Dungeons / Hack 'n Slash / Rogeu


### Moodboard

<!-- TODO: insert moodboard screens -->

### Colorpalette

Het kleurpalette Wat gebruikt word is: MATT36 (https://lospec.com/palette-list/matt36)

<!-- TODO: insert pic matt36 palette -->

## 7. Octalysis Model

https://yukaichou.com/gamification-examples/octalysis-complete-gamification-framework/
https://yukaichou.com/octalysis-tool/

Als extra info vanuit de geleerde theorie heb ik het octalysis model gepakt. Dit model geeft mooi weer wat voor soort game het is.

### 7.1 Epic meaning and Calling [6]
Verhaal over CMGT
Herkenbare CMGT dingen
Een fantasiewereld van school maken

### 7.2 Development and Accomplishment [9]
Enemies vechten
Bosses vechten
Rooms overwinnen
XP
Leaderboards
Timer

### 7.3 Empowerment of Creativity and Feedback [5]
Kiezen van buffs
Wanneer gebruik maken van items
Zelf weten welke route je neemt en of je veel wil exploren

### 7.4 Ownership and Possession [3]
Het kiezen van buffs
Het hebben van items
verdiende XP

### 7.5 Social Influence and Relatedness [2]
Co-op
Spelen terwijl andere mensen meekijken
Herkenbare dingen van CMGT
mensen die praten over de game

### 7.6 Scarcity and Impatience [1]
Je kan niet alle buffs kopen

### 7.7 Curiosity and Unpredictability [9]
Nieuwe rooms exploren in de floor
Nieuwe emenies ontdekkeen
nieuwe items/buffs ontdekken
Elke playthorugh een andere indeling


### 7.8 Loss and Avoidance [7]
Je kan doodgaan en alles verliezen (progress loss)
De indeling van rooms zal maar 1x zo zijn


<!-- TODO: insert oct model pic -->


## 8. Uiteindelijke Conceptschets

<!-- TODO: insert final conceptschets -->