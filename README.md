# FlappyBirdAI

A NEAT-based AI for the classic Flappy Bird game. Watch as the AI learns to navigate pipes, improving over generations!

![Flappy Bird AI](imgs/running_program.png)

## Installation

1. Clone the repo:

    ```bash
    git clone https://github.com/yourusername/FlappyBirdAI.git
    cd FlappyBirdAI
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the AI:

    ```bash
    python3 main.py
    ```

## Usage

- When prompted:
  - `y` to train a new model
  - `n` to load an existing model (`winner.pkl`)

## How It Works

The AI uses the NEAT algorithm to evolve a neural network that controls the bird. The network improves each generation, learning to avoid pipes by being rewarded for longer survival and successful passes.

## Configuration

Adjust training parameters in `config-feedforward.txt`.

## License

MIT License
