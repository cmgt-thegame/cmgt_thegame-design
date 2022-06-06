# Game Design Document (CMGT: The Game)
2022-05-11


<!-- TODO: insert conceptart pics -->

## 1. Global Idea

Kind of Fun: Discovery & Challenge
Game Mechanic: Fight & Explore
X-Factor: Docenten, Schoolgebouw & Rotterdam

pixelart
topdown 2 point front isometric
32 colors
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

De doelgroep bestaat voor het grooste gedeelte uit ervaren gamers vanuit veel verschillende genres. Ook hebben de meeste mensen in de doelgroep ervaring met game design.

Omdat de arcade machine een kleine tijdverdrijf is (Bijvoorbeeld in de lunchpauze) en je niet mensen onproductief wil maken moet de game kort en duidelijk zijn. Ook moet het niet te moeilijk zijn om te zorgen voor een ontspannend/satisfied gevoel.

Daarom moet de game in het begin makkelijk zijn en gefocust zijn op exploration. Later kunnen er een paar moeilijkere elementen bijgevoegd worden. Het heeft een lage "skill floor" nodig.


### Bartle Player Type
Het is lastig in te delen welke bartle player type deze doelgroep is aangezien het een brede groep players is. Mijn gok is dat het redelijk verdeelt is en er van elke soort wel evenveel mensen zijn. Hier zou nog grondig gebruikersonderzoek naar gedaan moeten worden.

### NewZoo Plater Type
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

lopen
attack (weapons)
    hack sword (tech explosion death)
dash
combos

sleeping points / awake bar (hp)

xp (gained by fighting)

items (gained by exploring)
    koffie
    redbull
    eten

buffs (building blocks)

playable characters (skins)
    zino
    dani
    lucas

enemies
    robots
        #1 slow accurate melee robot (cle1 robot, servo arm)
        #2 fast inaccurate charge delay melee robot (op hol geslagen deelscooter)
        #3 fast inaccurate shooting robot (cle1 robot, schiet pcb board stukjes)
        #4 slow accurate shooting robot (cle1 robot, confetti kanon)
    minibosses
        Marloes
            stadslab
            lasers
        Rene
            following
            appears out of nowhere
    bosses
        Erik    
            capibaras
            tamagochi
            AI
            games

floors (per leerjaar 1 floor, 5 min per floor)
    subareas (generating areas, multiple rooms, camera zoom)
        stadslab
        cmgt hal
        generic cmi gebouw area
        wijnhaven straat
        markthal
        metro/ beurs
    rooms (parts of subareas)
        classroomx
        hallway
        bathroom
        stairwell  
        docentenhok
        dakterras
        kantine
        bossroom   


scope eerste versie = floor 1 (eerste 5 min)



### Mechanics

Main Mechanics

1. Move

2. Attack (hack sword)

3. Dash

Combos:
- Dash + Attack 

### Regels

Een player kan vrij rondlopen door het level, interacten met items en deuren openen. Bij het binnenkomen van een nieuwe kamer worden de enemies wakker en moeten die bevecht worden.

De `floor` (een samenkomst van meerdere `rooms`) is procedurally gegenereerd met een vaste compositie van soorten rooms. De eerste floor moet een generic hogeschool rotterdam wijnhaven feel hebben.

Je hebt als player de `energy bar`, wanneer je aangevallen word gaat deze bar naar beneden. Als deze op 0 staat ben je uitgeput en ben je gameover. Om energie erbij te krijgen kun je items of buffs gebruiken.

Bij het vechten obtain je `XP` punten, die kan je later gebruiken om buffs van te krijgen. Ook word de totale XP gebruikt om je op een leaderboard te kunnen plaatsten.

De enemies zijn op hol geslagen IoT robots, waar je later in het verhaal meer over te weten komt. Elke robot heeft zijn eigen karakteristieken en vormgeving. 

Elke floor heeft een `endboss` deze moet je verslaan om die floor te halen. Na het killen van de endboss krijg je rewards in de vorm van items, buffs en XP. De endbosses zijn elke keer een CMGT docent.

Sommige speciale rooms hebben ook hun eigen `minibosses` met een eigen verhaal en speciale abilities.

### Items/entities

## 6. Thema

pixelart
topdown 2 point front isometric
32 colors
(inspiration: enter the gungeon / binding of isaac / minecraft dungeons / hack n slash / rogeu)

### Moodboard

### Styleguide

## 7. Octalysis Model

## 8. Uiteindelijke Conceptschets
