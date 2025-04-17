# 🧠 Chess Opening Trainer

A web application to practice and expand your chess opening repertoire using predefined lines, Stockfish analysis, and a Lichess-style interface.

---

## 🎯 Project Goals

- Build a browser-based interface for practicing chess openings.
- Allow users to upload, edit, and play through predefined move trees.
- Integrate Stockfish to recommend additions to the repertoire.
- Use Lichess open source tools (board UI, Stockfish integration, etc.).
- Support Google SSO for saving user repertoires.
- Deploy a secure, scalable version on DigitalOcean.

---

## 🚧 MVP Features

- [ ] Load PGN or FEN-based opening repertoires
- [ ] Practice vs computer using set move trees
- [ ] Show correct/incorrect feedback after each move
- [ ] Display opening lines visually like a study
- [ ] Google SSO authentication
- [ ] Save and retrieve user's repertoire from the backend
- [ ] Deploy to DigitalOcean with HTTPS + scalable DB

---

## 🛣️ Planned Stack

- **Frontend**: React + Tailwind CSS + Lichess board component
- **Backend**: Node.js/Express OR Django/FastAPI
- **Database**: PostgreSQL
- **Auth**: Google OAuth 2.0 (via Firebase or Auth0, or custom)
- **Engine**: Stockfish (WASM or UCI over backend)
- **Deployment**: Docker + DigitalOcean App Platform

---

## 🗺️ Roadmap

### v0.1 – MVP
- [ ] Chessboard with lichess-style move input
- [ ] Opening trainer using hardcoded PGN
- [ ] Local evaluation via Stockfish WASM
- [ ] Simple save/load from localStorage

### v0.2 – Auth & Cloud Sync
- [ ] Google SSO
- [ ] User-specific repertoires in DB
- [ ] Multi-line and branching studies

### v0.3 – Import & Recommendations
- [ ] Import PGNs
- [ ] Stockfish-powered suggestions

---

## 🔧 Local Dev Setup

```bash
git clone https://github.com/YOUR_USERNAME/chess-opening-trainer.git
cd barnesopening
npm install
npm run dev
