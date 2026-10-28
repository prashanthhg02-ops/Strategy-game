# Strategy-game
# Emberfall

Emberfall is a small, turn-based kingdom strategy game that runs directly in your browser. No installation, build step, or server is required.

## Play

Open [index.html](./index.html) in a modern web browser.

## How to play

Lead your army from your keep on the western edge of the map to the enemy stronghold on the eastern edge.

- **Move:** Select one of your units, then choose a highlighted tile. Water cannot be crossed.
- **Attack:** Select a unit and click a highlighted enemy. Units can attack once per turn.
- **Use terrain:** Forests and hills reduce incoming damage by 1.
- **Recruit:** Raise militia, archers, or knights at your keep using gold. You start with 12 gold and earn 3 gold at the start of each new turn.
- **End your turn:** Choose **End your turn** to let the enemy army act. Your units are ready again when your next turn begins.
- **Win:** Move any unit onto the enemy keep. You lose if your army is defeated.

### Units

| Unit | Cost | Health | Attack | Movement | Range |
|---|---:|---:|---:|---:|---:|
| Militia | 5 gold | 3 | 1 | 2 tiles | 1 tile |
| Archer | 7 gold | 2 | 1 | 2 tiles | 2 tiles in a straight line |
| Knight | 9 gold | 4 | 2 | 3 tiles | 1 tile |

## Built with

The game uses plain HTML, CSS, and JavaScript. Game state is kept in memory, so refreshing the page starts a new game.
