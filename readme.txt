WAR
by Nicholas Weber
Written for Code Fellows Foundations I course.
v 0.3
deck.html is a simple JavaScript implementation of the card game War.

Problem domain:
Implementing War with a standard 52 card deck with players and draw and compare cards. 

Improvements over last version:

- Implemented shuffling the deck and drawing from the top, not take a random card from the deck.

Planned improvements:

- Create Player objects with hands that can be compared.
- Create a discard pile object to put cards from ties in so they're not re-drawn.
- Have a persistent state of the game until one side wins or loses (arguably, this would not be an improvement).