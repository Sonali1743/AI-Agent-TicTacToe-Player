# AI-Agent-TicTacToe-Player

Please note below points regarding the code:
- First, I built random Monte Carlo without any playout policy. The agent was not making the best moves and was losing the game.
- Therefore, I improvised the Monte Carlo code to include UCT (Upper Confidence bounds applied to Trees) as the playout policy. With this, agent is making the best possible move, thereby never losing a game.
