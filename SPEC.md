# Texas Hold'em Poker Game

## Project Overview
- **Type**: Single HTML file browser game
- **Core Functionality**: Texas Hold'em poker with AI opponents
- **Target Users**: Casual poker players

## Visual Specification

### Theme & Style
- Dark felt-green table background with subtle texture
- Playing cards with classic red/black suits
- Chip-styled betting indicators
- Smooth CSS animations for card dealing and reveals

### Color Palette
- Table: `#1a5f2a` (felt green)
- Card backs: `#c41e3a` (crimson)
- Chips: Gold `#d4af37`, Red `#e74c3c`, Blue `#3498db`
- UI accents: `#f5e6c8` (cream)

## Game Mechanics

### Players
- 1 human player (bottom of table)
- 4 AI opponents (around table)

### Deck
- Standard 52-card deck
- Cards shuffled before each hand

### Betting Rounds
1. **Pre-flop**: Each player receives 2 hole cards
2. **Flop**: 3 community cards revealed
3. **Turn**: 4th community card
4. **River**: 5th community card
5. **Showdown**: Best 5-card hand wins

### Hand Rankings (low to high)
1. High Card
2. One Pair
3. Two Pair
4. Three of a Kind
5. Straight
6. Flush
7. Full House
8. Four of a Kind
9. Straight Flush

### AI Behavior
- Basic decision making based on hand strength
- Random raises/calls with weighted probability
- Folds weak hands, calls/raises with good hands

## Interaction Specification

### Controls
- **Bet/Chip buttons**: Add chips to pot
- **Check**: Pass action if possible
- **Call**: Match current bet
- **Fold**: Discard hand and exit round
- **Raise**: Increase current bet
- **All-in**: Bet all remaining chips

### Game Flow
1. Deal hole cards to all players
2. Pre-flop betting round
3. Deal flop (3 cards)
4. Betting round
5. Deal turn (1 card)
6. Betting round
7. Deal river (1 card)
8. Final betting round
9. Showdown - reveal hands
10. Winner collects pot

### UI Elements
- Player labels with chip counts
- Pot amount display
- Current bet indicator
- Action buttons (contextual)
- Card animations

## Acceptance Criteria
- [ ] All 52 cards render correctly
- [ ] Cards shuffle properly each hand
- [ ] All betting actions work (check, call, fold, raise, all-in)
- [ ] AI players make decisions
- [ ] Hand evaluation correctly identifies winners
- [ ] Pot updates correctly
- [ ] Game resets properly for new hand
- [ ] Works in modern browsers (Chrome, Firefox, Safari)
