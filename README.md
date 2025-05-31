# Flash-card-game
เกมแฟลชการ์ด - Flash-card-game
 
# Interactive Flashcard Game

This project is a simple yet interactive flashcard game designed to help users learn vocabulary effectively. The initial setup includes Arabic greetings and their English translations. The game tracks user progress and features a clean flip-card animation.

## Features

* **Flashcard System**: Interactive cards that flip to reveal the answer.
* **Progress Tracking**: Visual progress bar to track user learning.
* **Clean Design**: Simple and user-friendly interface.

## How to Use

1. Open the HTML file in a browser.
2. Click on the card to flip it and reveal the meaning.
3. The progress bar updates as you cycle through the cards.

## Customization

### Adding More Flashcards

To add more flashcards, update the `flashcards` array in the script section:

```javascript
const flashcards = [
  { front: 'مرحبا (Marhaban)', back: 'Hello' },
  { front: 'كيف حالك؟ (Kayfa Haluka?)', back: 'How are you?' },
  // Add more cards here
];
```

### Styling

Modify the CSS section to change the appearance of the flashcards or the overall layout.

### Progress Bar Behavior

Adjust the progress bar logic in the `flipCard` function:

```javascript
progress += 10; // Example increment
if (progress > 100) progress = 100;
```

## Future Enhancements

* **Scoring System**: Add points for correct answers.
* **Hints**: Provide hints for difficult words.
* **Multiple Languages**: Support other languages.
* **Audio Pronunciation**: Include audio for better learning.

## Requirements

No special dependencies are required. The game is built using plain HTML, CSS, and JavaScript.

## License

This project is open-source and available under the MIT License.

---

Feel free to contribute or suggest improvements if you do you can new repo !
