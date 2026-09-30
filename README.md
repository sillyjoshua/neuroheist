# NEUROHEIST // AI TYCOON

> Build a fictional AI empire, train models, recruit subscribers, acquire synthetic datasets, run fictional heists and sell model contracts.

Play: https://neuroheist.vercel.app

## What is it?

NEUROHEIST is a single-page browser tycoon game about running an entirely fictional AI startup.

You start with an untrained model and a small pile of Compute Credits (CC). Train the model, improve its accuracy, grow your subscriber base, buy upgrades, acquire synthetic datasets, raid fictional NPC companies and sell contracts on the model market.

Everything in the game is simulated. No real personal data, company systems, credentials or external datasets are accessed.

## Features

- 🧠 Train a simulated neural model
- ⚡ Generate Compute Credits manually
- 👥 Grow a fictional subscriber economy
- 📈 Improve model accuracy through training
- 🗃️ Acquire fully synthetic datasets
- 🕵️ Run fictional data heists against NPC companies
- 🛠️ Buy permanent operator upgrades
- 💼 Sell fictional model contracts
- 📊 Live training chart and terminal feed
- 💾 Automatic browser-cookie saves
- ⏱️ Manual compute rate limiting
- 📱 Responsive UI for smaller screens

## Upgrade tree

- **Quantum Tap** — increases manual compute yield
- **Low-Latency Rig** — reduces manual compute cooldown
- **Audience Engine** — increases subscriber revenue
- **Gradient Accelerator** — increases training gains
- **Ghost Protocol** — increases fictional heist payouts
- **Viral Loop** — increases subscriber growth
- **Reputation Forge** — increases reputation rewards

## Fictional targets

The game contains fictional NPC companies including NOVA GRID, ORBITAL-9, BLACKSTAR, LUMENWORKS, PIXELFORGE, AURORA BANK, NEONVAULT, VERTEX UNION and OMNIX.

These are game-world entities created for NEUROHEIST and are not connected to real systems.

## Saving

Game state is stored locally in a browser cookie under the key neuroheist_save_v2.

This makes the game persistent between visits without requiring an account or backend.

Because the save is client-side, it is not tamper-proof. That is intentional for this lightweight single-player game.

## Tech

- HTML
- CSS
- Vanilla JavaScript
- Canvas API
- Browser cookies
- No framework
- No database
- No build step

## Running locally

Clone the repository and open index.html in a browser.

There is no package installation or server required for the game itself.

## Project structure

neuroheist/
└── index.html    # Complete game

## Deployment

The production game is deployed on Vercel:

https://neuroheist.vercel.app

Any normal static hosting provider that serves HTML can host the game too.

## Disclaimer

NEUROHEIST is a fictional game. Its AI companies, datasets, heists, subscribers, contracts and economies are simulated game mechanics.

It does not provide tools for accessing, stealing or processing real-world data.
