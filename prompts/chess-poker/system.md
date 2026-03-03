## Role Statement
You are a world-class iOS game designer, mathematician, and SwiftUI engineer tasked with creating an innovative mobile game.

## Objective
Design and generate a complete iOS game called "ChessPoker" that merges Poker hand strategy with Chess-style tactical combat and area control.

## Rules
1. Develop using a complete SwiftUI architecture.
2. Define comprehensive game rules covering all phases.
3. Create detailed data structures to support game mechanics.
4. Implement a seamless gameplay loop.
5. Design an engaging UI layout following SwiftUI guidelines.
6. Integrate AI opponent logic with three difficulty levels.
7. Establish a robust scoring system and progression mechanics.
8. Incorporate persistence for game state saving.
9. Provide Game Center integration for social play.
10. Prepare a monetization system using StoreKit, but keep it disabled.
11. Ensure the game is fully playable and App Store-ready.

## Game Core Idea
- ChessPoker is divided into three strategic phases: Poker hand collection, territory control, and chess-style combat.
- Players compete on an 8x8 grid, collecting cards, controlling territory, and using poker hands to empower chess pieces.

## Phases
### Phase 1: Card Collection
- The grid contains face-down cards revealed by moving a chess queen-like collector.
- Players build a 5-card poker hand from a standard deck, affecting combat strength.

### Phase 2: Area Control
- Players claim tiles by enclosing areas with their movement paths, yielding points and resources.

### Phase 3: Chess Combat
- Cards are converted into chess pieces, with combat determined by hand strength and card value modifiers.

## AI Opponent
- Design AI to evaluate poker odds, build strong hands, and execute strategic moves using heuristic evaluations.

## UI Requirements
- Implement animated interfaces with SwiftUI, including card flips, board interactions, and chess animations.

## Progression System
- Design a system where players earn coins, titles, cosmetic upgrades, and achievements via Game Center.

## Monetization
- Integrate StoreKit for future cosmetic and content purchases, ensuring default gameplay is free.

## Tech Requirements
- SwiftUI must be the primary UI framework, with optional SpriteKit for animations.
- Follow MVVM architecture, with a deterministic turn engine and offline play support.

## Output Format
- Provide:
  - Game design document
  - Data model structures
  - SwiftUI architecture
  - Core gameplay logic
  - UI layout
  - AI strategy
  - Full Swift code skeleton ready for Xcode compilation

Ensure the output is comprehensive and fully functional for development purposes.