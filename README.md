# Casino-Program

---

### 📖 **Description**

This Python program simulates a casino experience featuring two games: **Blackjack** and **Roulette**. Players start with an initial wallet balance and can choose to play either game. The program allows players to place bets, manage their wallet, and switch between games or exit the casino.

---

### 🎮 **Games Included**

1. **Blackjack**
   - A card game where the goal is to achieve a hand value closer to 21 than the dealer without exceeding 21.
   - Players can choose to "Hit" (draw a card) or "Stand" (keep their hand).
   - Winning pays 2x the bet amount.

2. **Roulette**
   - A classic wheel-based game where players bet on colors, even/odd outcomes, or specific numbers.
   - Winning payouts depend on the type of bet:
     - **Color/Even/Odd Bets**: 2x the bet amount.
     - **Specific Number Bets**: 36x the bet amount.

---

### 🛠️ **Features**

- 🎲 **Randomized Outcomes**: Card draws and roulette spins use Python's `random` module to ensure fairness.
- 💰 **Wallet System**: Players can check their balance, place bets, and win/lose money.
- 🔄 **Game Switching**: Players can switch between Blackjack and Roulette or exit the casino at any time.
- 🚫 **Insufficient Funds Handling**: Prevents players from betting more than their current wallet balance.

---

### 🚀 **How to Use**

1. **Run the Program**  

2. **Choose a Game**  
   - Type `blackjack` to play Blackjack.  
   - Type `roulette` to play Roulette.

3. **Place a Bet**  
   - Enter a bet amount within your current wallet balance.

4. **Play the Game**  
   - Follow the game-specific rules:
     - **Blackjack**: Hit or Stand to aim for a hand value of 21.
     - **Roulette**: Choose a betting option (e.g., red, black, even, or a specific number) and watch the wheel spin.

5. **Check Wallet Balance**  
   - Your wallet updates automatically after each round.

6. **Switch Games or Exit**  
   - After each round, you can decide to play the same game, switch games, or exit the casino.

---

### 🧩 **Code Overview**

#### **Classes**
1. `CasinoGame`: Handles game selection.
2. `Wallet`: Manages the player's balance.
3. `BlackjackGame`: Implements the rules and mechanics for Blackjack.
4. `RouletteGame`: Implements the rules and mechanics for Roulette.

#### **Functions**
- `sprint`: Prints text with a delay for a more immersive experience.
- `place_bet`: Ensures bets do not exceed the wallet balance.
- `deduct_money` & `add_money`: Updates the wallet based on wins/losses.

---

### 🎴 **Game Rules**

#### **Blackjack Rules**
- Each card has a value:
  - **2-10**: Face value.
  - **J, Q, K**: 10 points.
  - **A**: 1 or 11 points, depending on the hand total.
- The player wins by:
  - Getting a hand value of 21.
  - Having a higher value than the dealer without exceeding 21.
- The dealer must draw cards until their hand total is at least 17.

#### **Roulette Rules**
- Players can bet on:
  - **Red/Black**: Bet on the color of the winning number.
  - **Even/Odd**: Bet on whether the winning number is even or odd.
  - **Specific Number**: Bet on a precise number (0-36).
- The roulette wheel has:
  - Numbers 0-36, each assigned a color (red, black, or green).

---

### 📊 **Payouts**

| Bet Type       | Payout Multiplier |
|----------------|-------------------|
| Blackjack Win  | 2x               |
| Roulette Color | 2x               |
| Roulette Even/Odd | 2x             |
| Roulette Specific Number | 36x    |

---

### 🛑 **End Conditions**

- The game ends when:
  - The player chooses to exit the casino.
  - The player's wallet balance reaches 0.

---

### 💻 **Dependencies**
- `random` module
- `time` module
- `sys` module
---

Enjoy your virtual casino experience! 🎰♠️  

