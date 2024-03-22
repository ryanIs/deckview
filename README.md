# DeckView - Magic The Gather Arena Deck Assistant

This application helps display every card in your (obviously 250-sized) deck. 
Certain game-situations require exact knowledge of what ETB and active abilities your deck can perform when 
using cards that can pull from the deck.

This helps you quickly access your deck in such sticky situations.

<img src="example1.png" />

# Usage:

In your MTGA client - Export your desired deck.

Paste it into the `INPUT.js` `let myDeckPasteStr = ` template string.

Open `index.html`. 

(You may use `index.html?d=seconddeck`) if you have them loaded as variables as well (eval).

## Notes:

You use the navigation at the top to goto spells by their costs.

Cards such as [Rocco, Cabaretti Caterer](https://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=555419&type=card) that 
pull out a card based on available mana will benefit greatly from this application.

# Credit

Thank you to https://gatherer.wizards.com (Wizards of the Coast) for the card image API and amazing game Magic the Gathering.

Thank you to https://mtgjson.com for the card information JSON API.