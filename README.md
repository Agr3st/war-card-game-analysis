# War Card Game Simulation and Analysis

This repository contains a simulation and statistical analysis of the classic card game **War**, adapted for varying numbers of players.

---

## 📚 Assumptions

The simulation is based on the following rules and assumptions:

1. **Card Distribution**:
   - Each player receives an equal number of cards: `52 // n`.
   - The total number of cards in play is `(52 // n) * n`.
   - Non-playing cards are chosen from the lowest values in the deck.

2. **War Resolution**:
   - If a war occurs and a player runs out of cards (hand and side stack), that player loses.
   - Wars are counted as **one move**, regardless of how long they last.

3. **Side Stack Mechanics**:
   - When a player runs out of cards in their hand but has cards in the side stack, the side stack is shuffled and moved back to the hand.

---

## 🃏 Example: 3 Players

For a game with `n = 3` players:
- **Number of Cards per Player**:  
  `52 // 3 = 17` cards per player.
- **Total Cards in Play**:  
  `17 * 3 = 51` cards.
- **Deck Composition**:  
  `[2, 2, 2, 3, 3, 3, 3, 4, 4, 4, 4 ...]`.

---
