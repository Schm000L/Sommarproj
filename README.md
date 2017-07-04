# Sommarproj
2017, sommarprojekt

# TODO

* Texturer
  * Flipbooks
    * Spelaren (Idle, Run, Jump, Dubble jump, Crouch, Idle Crouch, Slide)
    * Fienden (Run)
  * Sprites
    * ~~Vapen~~ (+arm) (Jesper)
    * ~~Kulor~~ 
    * Blocks (Kanske inte behövs)
    * Bakgrund(er)
  
* Visuals
  * ~~Få vapen att "sitta fast" på spelaren~~
  * Få vapen att följa pekaren (Jesper)

* Tema
  * Genrellt tema för spel? Mörkt, ljust, retro, djungel, tencho!??!
  * Story?
  * Intro-scen
  * Outro

* Gameplay
  * Slide
  * ~~Ledge grabbing (Samsam)~~
    * Fixa bugg
    * Enkelhopp om man släpper?
  * Vapen
    * ~~Vilka vapen?~~
    * Kulor (hastighet, skada mm)
    * Få att kulorna åker mot pekaren (Jesper)
    * Pickup-vapen? Få ett nytt vapen efter varje level?
    * Skjuta i musriktning
   
    * ~~Pistol - P99 (https://en.wikipedia.org/wiki/Walther_P99)~~
    * ~~Shotgun - SPAS (https://en.wikipedia.org/wiki/Franchi_SPAS-12)~~
    * ~~Assault Rifle - SCAR (https://en.wikipedia.org/wiki/FN_SCAR)~~
    * ~~Crossbow - (https://en.wikipedia.org/wiki/Crossbow#/media/File:Horton_Hunter_Supreme_by_IvE.jpg)~~
    * ~~Granate Launcher - (https://en.wikipedia.org/wiki/Milkor_MGL)~~
    * ~~IMBA Melee - Eeeeehh..... katanahandtag+scimitar~~

    * Special (Granade TP)
    
    
  * Fiender (ny blueprint)
    * AI (finns inbyggt tror ja)
  * HP, ta skada, få HP (pickups?, life-steal?)
  * Skapa mål som triggar en ny karta (eller end-credits), borde finnas inbyggt
  
* Kartdesign
  * Skapa kartor (med olika teman?)

* Ljud
  * Inspelning
    * Hitta "gratis-ljud"
    * Spela in egna ljud
    * Ta ljud som ingår i "Starter Pack"
  * Ljud till
    * Vapen (Jesper)
    * Fiender (?)
    * Hopp (?), Landning (?)
  * Musik
 
* Övrigt
  * Meny
  * Credits
  * Inställningar
    * Ändra ljud/musik-volym
    * Kontroller (?)
    * Upplösning
    * Window/Fullscreen
  * Beta testing
  
* Publishing
  * Greenlight?
  
# How to
* Ledge grabbing
  * För att objekt ska kunna spåras och tas tag i:
    * Collision Preset: Custom
    * Collision Enabled: Collision Enabled
    * Trace Responses: LedgeTrace: Block
    * Object Responses: CircleTracer: Overlap
    

 
