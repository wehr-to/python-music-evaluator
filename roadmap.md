# roadmap

## Phase 1: Setup & API Basics
- [ ] Register a Spotify Developer app (get Client ID, Secret, Redirect URI).
- [X] Set up environment variables or `.env` file for secrets.
- [ ] Install dependencies: `spotipy`, `pandas`, `numpy`, `matplotlib`, `python-dotenv`.
- [ ] Authenticate with Spotify API and fetch top tracks.

## Phase 2: Data Wrangling
- [ ] Parse track metadata into a Pandas DataFrame.
- [ ] Extract useful fields: `artist`, `release_year`, `popularity`, audio features (energy, valence, tempo).
- [ ] Write simple analysis functions (e.g., average popularity, release year range).

## Phase 3: Metrics & Scoring
- [ ] Implement **Obscurity Score** (inverse popularity).
- [ ] Implement **Era Breadth** (spread of years).
- [ ] Implement **Genre Diversity** (Shannon entropy, optional).
- [ ] Implement **Recency Bias** (share of tracks from last N years).
- [ ] Implement **Audio Feature Variety** (variance across tempo, energy, valence).
- [ ] Combine metrics into a single composite “Edgy Taste Score”.

## Phase 4: Evaluation Outputs
- [ ] Create thresholds & labels (e.g., "Gatekeeper Supreme", "Algorithm Normie").
- [ ] Print a textual roast report with scores and commentary.
- [ ] Add optional ASCII art or emojis for extra flair.

## Phase 5: Visualization
- [ ] Plot metrics as a bar chart or radar chart with Matplotlib.
- [ ] Save charts as PNG for sharing.
- [ ] Add option to export results as JSON/CSV.

## Phase 6: Packaging & Polish
- [ ] Build a CLI with `argparse` (e.g., `python taste.py --limit 50`).
- [ ] Add config file (`config.yml`) for metric weights.
- [ ] Document usage in a `README.md`.
- [ ] Add example roast outputs and screenshots.

## Phase 7: Stretch Goals
- [ ] Fetch playlists instead of just top tracks.
- [ ] Compare two users’ scores (friend roast mode).
- [ ] Deploy as a simple Flask web app.
- [ ] Add a “roast generator” with randomized insult phrasing.

