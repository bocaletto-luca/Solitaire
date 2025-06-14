# Solitaire – WEBGAME
#### Author: Bocaletto Luca

[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-E34F26?logo=html5)](https://www.w3.org/html/)
[![Made with CSS3](https://img.shields.io/badge/Made%20with-CSS3-1572B6?logo=css3)](https://www.w3.org/Style/CSS/)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?logo=javascript)](https://developer.mozilla.org/docs/Web/JavaScript)

[![Test Online](https://img.shields.io/badge/Test%20Online-Click%20Here-brightgreen?style=for-the-badge)](https://bocaletto-luca.github.io/Solitaire/)

## Overview

**Klondike Solitaire – Final Release** is a modern, fully responsive web adaptation of the classic Klondike Solitaire game. This project faithfully implements the official solitaire rules—including proper deck shuffling, dealing into tableau piles (with only the last card face-up), Stock, Waste, and four Foundation piles—with the added benefit of native drag & drop support for an intuitive moving of individual cards or entire sequences.  
The design is sleek and responsive, ensuring an excellent user experience on both desktop and mobile devices.

## Features

- **Responsive Design:** Adapts perfectly to various screen sizes including desktops, tablets, and smartphones.
- **Official Klondike Rules:** Shuffling, dealing into the tableau, Stock, Waste, and Foundations are implemented as per the original rules.
- **Drag & Drop Interface:** Easily drag and drop cards or card sequences between piles.
- **Automatic Card Flipping:** Cards in the tableau are automatically turned face-up when their covering card is moved.
- **Interactive Help Modal:** Provides clear instructions on gameplay.
- **Dynamic Feedback:** Informative messages guide you when attempting moves.
- **Easy New Game Restart:** Restart the game with a single click.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/bocaletto-luca/Solitaire.git
2.  Start Server Example Apache2 e open index.html in Web Browser

## Usage

**Stock & Waste:**  
Click on the Stock pile to move a card to the Waste. Only the top card of the Waste is visible.

**Moving Cards:**  
Drag and drop a card (or an entire sequence from the tableau) from the Waste or any Tableau pile to a valid destination:

- **Tableau:** Cards can be built in descending order with alternating colors. An empty tableau accepts only a King (with its entire sequence).
- **Foundation:** Cards are built in ascending order (Ace to King) within the same suit.

**Auto Flipping:**  
When a card is moved from a Tableau pile, the new top card is automatically flipped face-up.

**Win Condition:**  
You win when all 52 cards are moved to the Foundation piles.

## Contributing

Contributions, bug reports, and feature suggestions are always welcome!  
Feel free to fork the repository and submit pull requests.  
For major changes, please open an issue first to discuss your ideas.

## License

This project is licensed under the GPL License.

## Developer

Developed by **Bocaletto Luca**

Enjoy playing Klondike Solitaire!
