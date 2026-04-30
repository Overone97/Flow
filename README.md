# Flow

Prototype web 3D orienté **vertical slice MMORPG light**.

## Version
- `0.4.0` — phase 4 lite

## Ce qu'il y a dedans
- 1 zone jouable : **Whispering Grove**
- déplacement third-person
- caméra souris
- 4 wisps hostiles
- ciblage
- attaque de base
- 3 skills (`Q`, `E`, `R`)
- loot d'âmes
- sanctuaire de soin
- HUD combat / quête / log
- impacts visuels, bursts et morts plus lisibles
- axe caméra horizontal + vertical inversé pour une visée plus naturelle
- XP, niveau, montée de stats de base
- inventaire visible et vrai loot récupérable
- second type d’ennemi: loups ronces
- mini PNJ avec quête plus MMO

## Lancer
```bash
python3 -m http.server 8000
```
Puis ouvrir <http://localhost:8000>

## Contrôles
- `WASD / ZQSD` : déplacement
- `Souris` : caméra
- `T` : cible la cible la plus proche
- `Clic gauche` : attaque de base
- `1` : Arc Pulse
- `2` : Star Bolt
- `3` : Sanctify
- `F` : interaction sanctuaire
