## This world is a sandbox... and you are the child. Pull the strings of heroes and villains. And most importantly...
# Happy Hunting...

BUT!

I'm if you're that one person that just scrolls through the shop at 1AM and wondering what kind of game this is... allow me to answer your questions!

# What is a Tower Defense Game?
A Tower Defense Game is a game where waves of enemies follow a path to get to your base. You'll be able to place Towers that have some kind of attack to defeat those enemies. And enemies give you money to buy more towers. But if the enemies reach your base... they'll try to destroy it! Don't let that happen or it's GAME OVER!
It works like this:
```mermaid
flowchart TD

start((enter word beschikbaar)) --> A(drukt op enter)
A --> B(Mechanic start)
B --> C(Bom spawnt en valt naar beneden met een geluid en een smoke effect dat het achterlaat)
C --> D(Bom valt op het slagveld)
D --> E(Bom ontploft)
E --> F(Explosie gaat over het hele slagveld)
F --> G{Staan er vijanden op het slagveld?}
G -- Ja --> H[Iedereen is uitgeroeid. Jouw fort heeft zelf ook wat schade opgelopen]
G -- Nee --> I[You fucked up! Wapen verspild en fort heeft schade opgelopen voor niets!]
G -- Nee EN je fort heeft niet genoeg health meer -->K[Je fort heeft schade opgelopen tot het doodging. Je hebt het spel verloren]
H --> J((Mechanic voorbij! Wacht ongeveer 3 waves zonder de bom))
I --> J((Mechanic voorbij! Wacht ongeveer 3 waves zonder de bom))
J -- Wacht 3 waves --> start


# What makes this Tower Defense Game different?
