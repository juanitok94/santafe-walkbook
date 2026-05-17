# Santa Fe Walkbook

A digital art passport for Canyon Road — Santa Fe's most concentrated mile of art.

Ten stops. One road. Walk it.

## What this is

A warmly narrated neighborhood guide and passport game built on the
Camino de Santiago pilgrim passport model. Collect stamps at each of
the 10 core stops on Canyon Road. Earn your True Local badge.

Made with love by a longtime Canyon Road walker.

## Stack

- Next.js 16 (Turbopack)
- TypeScript
- Tailwind CSS 4
- Static JSON data layer
- localStorage for stamp state

## Run locally

git clone https://github.com/juanitok94/santafe-walkbook.git
cd santafe-walkbook
npm install
npm run dev

Open http://localhost:3000

## Data

All business data lives in /src/data/
- shops.json — Canyon Road stops, full data model
- layers.json — layer definitions
- badges.json — badge tiers
- trivia.json — per-stop trivia

Community corrections welcome via PR to the JSON files.

## Design principles

- Steve Krug: Don't Make Me Think
- Camino de Santiago: personal, directional, earned
- Hygge: warmth without friction

## Hashtags

#CanyonRoadWalkbook #SantaFeArt #SantaFeLocal
