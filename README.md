⭐ Star Wars Characters — Interactive Overview
A beautifully designed, fully interactive character encyclopedia spanning the entire Star Wars saga — built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step.


Features

44 iconic characters from across the entire Star Wars universe
Filter by allegiance — All, Light Side, Dark Side, or Neutral
Live search by name, species, or role
Character detail modal with species, origin, role, affiliation, film appearances, and a famous quote
Keyboard accessible — press Escape to close modals
Zero dependencies — single .html file, works offline


Characters Included
Trilogy / SeriesCharactersOriginal TrilogyLuke Skywalker, Leia Organa, Han Solo, Darth Vader, Yoda, Obi-Wan Kenobi, Chewbacca, Lando Calrissian, Wedge Antilles, Mon Mothma, Jabba the Hutt, Boba Fett, Grand Moff Tarkin, C-3PO, R2-D2Prequel TrilogyAnakin Skywalker, Padmé Amidala, Qui-Gon Jinn, Mace Windu, Count Dooku, General Grievous, Darth Maul, Jango Fett, Jar Jar Binks, PalpatineSequel TrilogyRey, Finn, Poe Dameron, Kylo Ren, BB-8, Captain Phasma, Snoke, General HuxClone Wars / RebelsAhsoka Tano, Asajj Ventress, Hera Syndulla, Ezra BridgerRogue One / AndorJyn Erso, Cassian Andor, K-2SO, Saw GerreraThe MandalorianDin Djarin, Grogu, Bo-Katan Kryze

Getting Started
No installation required. Just open the file in any modern browser.
bashgit clone https://github.com/CryptoShorts/star-wars-characters.git
cd star-wars-characters
open star_wars_characters.html
Or simply download the HTML file and open it locally.

Usage

Browse — all 44 characters are displayed in a responsive grid
Filter — click "Light Side", "Dark Side", or "Neutral" to narrow results
Search — type in the search bar to filter by name, species, or role
Explore — click any character card to open a detailed info panel


Project Structure
star-wars-characters/
└── star_wars_characters.html   # Everything in one file

Customization
All character data lives in a single characters array at the top of the <script> block. Adding a new character is as simple as appending a new object:
js{
  name:    "Grogu",
  abbr:    "GR",
  side:    "neutral",       // "light" | "dark" | "neutral"
  bg:      "#0a2a0a",       // avatar background color
  species: "Unknown",
  affil:   "Mandalorian / Jedi Order",
  origin:  "Unknown",
  role:    "Force Sensitive Child",
  film:    "The Mandalorian",
  quote:   "*cooing*"
}

Contributing
Contributions are welcome! Feel free to open an issue or pull request to:

Add missing characters
Improve the design
Add new filter options (e.g. by film, species, or homeworld)
Add image support


License
MIT — free to use, modify, and distribute.

"May the Force be with you." — Luke Skywalker
