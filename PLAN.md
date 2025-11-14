# D3: Fuse Me

## Game Design Vision

In this game, the player will gather literary components in the pursuit of developing a collection of works.
Collect components by clicking on nearby cells. Craft by clicking a cell of the same type as the equipped component.

## Technologies

- game source: TypeScript, HTML, CSS
- build: Deno and Vite for building
- automated deployment: GitHub Actions + GitHub Pages

## Assignments

### D3.a: Core mechanics (token collection and crafting)

Key technical challenge: Can you assemble a map-based user interface using the Leaflet mapping framework?
Key gameplay challenge: Can players collect and craft tokens from nearby locations to finally make one of sufficiently high value?

#### Steps

- [x] clear main.ts
- [x] render map with leaflet
- [x] display player location
- [x] use loops to display cell grid
- [x] fade cells that are out of reach
- [x] spawn a letter
- [x] let player collect letter
- [x] let player place letters in cells
- [x] spawn a word
- [x] implement combination of letters to create word
- [x] implement win state upon making a word
