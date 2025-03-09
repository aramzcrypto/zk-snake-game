# ZK Snake Game

A classic Snake game with Zero-Knowledge Proof verification on Succinct testnet.

![ZK Snake Game Preview](./assets/preview.png)

## Features

- Classic Snake game mechanics
- Mobile and desktop compatible
- Responsive design
- Zero-Knowledge Proof generation for game results
- Integration with Succinct testnet for on-chain verification
- MetaMask wallet integration
- Touch controls for mobile devices

## Technologies Used

- HTML5 Canvas for game rendering
- CSS3 for styling
- Vanilla JavaScript for game logic
- ethers.js for blockchain interaction
- Succinct SP1 for Zero-Knowledge Proof generation

## Getting Started

### Prerequisites

- Node.js and npm installed
- MetaMask or other Web3 wallet
- Some Sepolia testnet ETH for gas fees

### Local Development

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/zk-snake-game.git
   cd zk-snake-game
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## How to Play

1. Connect your wallet using the "Connect Wallet" button
2. Click "Start Game" to begin
3. Use arrow keys (desktop) or touch controls (mobile) to navigate the snake
4. Eat the food to grow the snake and increase your score
5. Avoid hitting the walls or the snake's body
6. After game over, click "Generate Proof" to create a Zero-Knowledge Proof of your score
7. The proof will be verified on Succinct testnet

## Zero-Knowledge Proof System

This game uses Succinct SP1 to generate Zero-Knowledge Proofs of your game results. The proof verifies:

- Your final score
- The number of moves made
- The history of moves
- That you played according to the rules

The proof is then submitted to a smart contract on the Succinct testnet for verification.

## Deployment

The game is deployed on Netlify at [https://zk-snake-game.netlify.app](https://zk-snake-game.netlify.app)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built by [Aram](https://x.com/AramzCrypto)
- Powered by [Succinct SP1](https://www.succinct.xyz/)
