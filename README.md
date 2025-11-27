<img width="707" height="685" alt="Screenshot 2025-11-27 at 9 07 43 at night" src="https://github.com/user-attachments/assets/5afa279d-026a-45d8-95a7-44c08e92dc67" />
# Kla-Klouk
គម្រោង "ខ្លាឃ្លោក" (Kla Klouk Game)  គម្រោងនេះគឺជាការបង្កើតដ៏រីករាយ សាមញ្ញ និងងាយស្រួលធ្វើ ដែលជាហ្គេម Kla Klouk ឌីជីថល (ល្បែងគ្រាប់ឡុកឡាក់ខ្មែរ)។
🇰🇭 Kla Klouk Game (Khmer Dice Game)

🎲 Overview

This is a fun, simple, and fully responsive web application replicating the traditional Cambodian dice game, Kla Klouk (ខ្លាឃ្លោក).

This project was developed using a conversational AI model (Google Gemini) for free, showcasing a quick and effective way to build a functional, modern web game entirely within a single HTML file.

✨ Key Features

Full Responsiveness: Optimized for dynamic viewing on all modern devices, including PCs, tablets, and smartphones.

Multilingual Support (i18n): Easy language switching between Khmer (🇰🇭) and English (🇺🇸).

Persistence: Integrates with Firebase Firestore to securely save and load the player's balance, ensuring game progress is never lost.

Modern UI: Built with Tailwind CSS for a clean, bright, and engaging user interface.

Fair Game Logic: Implements standard Kla Klouk payout rules based on the frequency of the rolled symbols (1x, 2x, 3x).

🛠️ Technologies Used

This application is intentionally built as a single, self-contained file to maximize portability and ease of use.

HTML5 / JavaScript: Core structure and game logic.

Tailwind CSS: Used exclusively for modern, utility-first styling and responsive design.

Firebase SDKs:

Firebase Auth: For initial user authentication (signInAnonymously or signInWithCustomToken).

Firebase Firestore: For persistent storage of the player's game balance.

Google Gemini: The Large Language Model used to generate and refine the entire codebase.

🚀 Installation and Setup

Since this entire game is contained within one file (index.html), setup is extremely straightforward.

1. Clone or Download

git clone <repository-link>
cd kla-klouk-game


2. Running Locally

Simply open the index.html file in any modern web browser.

Note on Firebase:
When running outside of a compatible environment (like Google's Canvas), the Firebase components related to authentication and data persistence will likely fail or use fallback random IDs. To make persistence work properly, you would need to:

Set up your own Firebase project.

Replace the placeholder global variables (e.g., __firebase_config) with your actual configuration details.

3. Game Instructions

Place Bet: Click on any of the six symbol cards (ខ្លា, ឃ្លោក, មាន់, បង្កង, ក្តាម, ត្រី) to place a minimum bet (100 chips) on that symbol.

Roll: Click the "ក្រឡុក!" / "Roll!" button.

Winnings: If a symbol you bet on appears once, you get your bet back + 1x the bet amount. If it appears twice, you get 2x the bet amount, and if it appears three times, you get 3x the bet amount.

💡 Customization

Change Language: Modify the translations object in the <script> block to add or edit language strings.

Adjust Betting: Change MIN_BET_AMOUNT or INITIAL_BALANCE variables in the JavaScript section.

Visuals: Tailwind classes are used throughout; feel free to adjust them for a different theme!

📜 License and Attribution

This project is open-source and available for use, modification, and distribution. If you use this code, please consider attributing its initial generation to the Google Gemini model.
