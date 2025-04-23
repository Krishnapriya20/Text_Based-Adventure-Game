# Text-Based Adventure Game AI

This project uses machine learning to simulate an AI system for a text-based adventure game. The AI is trained to respond to player actions, enabling the creation of an interactive narrative experience.

## Folder Structure

```
/text_based_adventure_game_AI/
│
├── /data/
│   └── game_data.csv             # Simulated player action and AI responses
├── /models/
│   └── ai_adventure_game_model.pkl  # Trained model for AI responses
│   └── vectorizer.pkl               # Vectorizer used for text data transformation
├── /scripts/
│   └── preprocess_data.py         # Data preprocessing script
│   └── train_model.py             # Model training script
│   └── ai_response.py             # Script to interact with the trained model
├── requirements.txt              # Required Python packages
└── README.md                     # Project documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/text-based-adventure-game-ai.git
   cd text-based-adventure-game-ai
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Preprocess the data:
   ```bash
   python scripts/preprocess_data.py
   ```

2. Train the model:
   ```bash
   python scripts/train_model.py
   ```

3. Interact with the AI:
   ```bash
   python scripts/ai_response.py
   ```

## License

This project is licensed under the MIT License.
