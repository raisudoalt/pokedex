# CLI Pokédex

A simple command-line Pokédex that lets you explore Pokémon locations, catch them, and inspect their stats using data from the PokéAPI.

## Features

- `help` – List all available commands
- `map` – Show nearby locations (paginated)
- `explore <location>` – Explore a specific location and list wild Pokémon
- `catch <pokemon>` – Attempt to catch a Pokémon and store its data locally
- `inspect <pokemon>` – View details (height, weight, stats, types) of a caught Pokémon
- `exit` – Quit the Pokédex

> Note: You can only inspect Pokémon you’ve already caught.

---

## Requirements

- [Node.js](https://nodejs.org/) (version 18+ recommended)
- [npm](https://www.npmjs.com/) (usually comes with Node)

---

## Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

# Install dependencies
npm install

## How to run it and use
npm run dev | tee repl.log  //to run it. You can view repl.log to view the recorded session
Pokedex > help
Pokedex > map
Pokedex > explore viridian-forest
Pokedex > catch pidgey
Pokedex > inspect pidgey
```

## Sample Run
<img width="475" height="320" alt="image" src="https://github.com/user-attachments/assets/175b81fa-51e1-4b3f-9cf7-0f205eb61c57" />


