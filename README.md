# Pokédex

This Pokédex is a browser-based Pokédex built with Flask and static front-end assets. It turns a familiar Pokémon search experience into a fast, responsive interface with smart search, random discovery, favorites, and history.

## What this browser does

This app is a complete Pokémon lookup tool that runs in the browser and loads data from the PokéAPI. It includes:

- **Search by name**: type any Pokémon name and fetch its profile instantly.
- **Randomizer**: click the Randomize button to display a random Pokémon from the National Dex.
- **Full battle stats**: view HP, Attack, Defense, Special Attack, Special Defense, and Speed.
- **Pokédex details**: see each Pokémon’s National Number, height, weight, and growth rate.
- **Favorites**: mark Pokémon you like and keep them in a personal collection.
- **Search history**: revisit recent searches and remove entries you no longer want.
- **Responsive layout**: mobile-friendly design with horizontally scrollable stat cards.

## Why it’s useful

This Pokédex is designed for fast reference and discovery. It is especially useful when you want to:

- compare base stats quickly
- explore new Pokémon with the Randomizer
- keep a list of favorite Pokémon in the browser
- access quick details without leaving the page

## Built with

- Python
- Flask
- Frozen-Flask for static export
- GitHub Actions for deployment to GitHub Pages

## Notes

- The app uses client-side session storage for favorites and login state.
- The static export is generated with `freeze.py` and can be deployed directly to GitHub Pages.

Enjoy your Pokémon browsing experience!
