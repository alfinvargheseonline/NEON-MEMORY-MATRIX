# NEON-MEMORY-MATRIX
GAMECRAFT 2026

# Neon Memory Matrix

## GameCraft 2026 Submission

### Participant / Team Name

**Q-Void**

### Team Members

- Alfin Varghese
- Sachin John Thomas

---

## Brief Description

**Neon Memory Matrix** is a fast-paced neon arcade-style memory matching game set in a futuristic cyberpunk environment. Players must identify matching pairs of cards before the 60-second countdown expires.

The game combines classic memory gameplay with progressive difficulty, streak-based scoring, neon visual effects, particle animations, and responsive controls. As each board is cleared, the grid expands, increasing the challenge and rewarding skilled memory recall.

---

## Objective and Rules

### Objective

Match as many card pairs as possible before the 60-second timer reaches zero.

### Rules

- The player must enter a name before gameplay begins.
- The countdown starts only after pressing **Start Game**.
- Two cards can be flipped per turn.
- Matching pairs remain revealed.
- Non-matching cards automatically flip back.
- Consecutive successful matches create score multipliers through streak bonuses.
- Clearing an entire board awards a round completion bonus.
- Larger boards are generated after each completed round.
- The score never drops below zero.
- When time expires, gameplay ends immediately and the final score is locked.

---

## Key Features

- 60-second arcade challenge
- Progressive board expansion after every round
- Neon cyberpunk-inspired design
- Animated particle effects and glowing UI
- Streak bonus scoring system
- Responsive design for desktop and mobile devices
- Keyboard and accessibility support
- Real-time timer warnings
- Runtime-generated sound effects
- Local Storage support for personal best scores
- Sound toggle (Mute / Unmute)

---

## How to Play

1. Open `index.html` in Microsoft Edge or Google Chrome.
2. Enter your player name.
3. Review the game instructions.
4. Press **Start Game** to begin the 60-second countdown.
5. Flip cards and locate matching pairs.
6. Build consecutive match streaks to earn bonus points.
7. Clear the entire board to unlock a larger grid.
8. Score as many points as possible before time expires.

---

## Controls

### Mouse / Touch

- Click or tap a card to flip it.
- Tap buttons to interact with menus and settings.

### Keyboard

| Key | Function |
|------|----------|
| Tab | Move between controls and cards |
| Arrow Keys | Navigate card grid |
| Enter | Flip selected card / activate button |
| Space | Flip selected card / activate button |

### Audio

- 🔊 Toggle sound effects On / Off

---

## Scoring Rules

| Action | Points |
|----------|--------:|
| Pair Matched | +20 |
| Streak Bonus | +5 per streak level |
| Maximum Streak Bonus | +25 |
| Mismatch | -5 |
| Round Completion Bonus | +50 |

### Scoring Notes

- Score can never become negative.
- Streak bonuses increase with consecutive successful matches.
- Any mismatch resets the current streak.
- The final score freezes immediately when time expires.

---

## Game Progression

| Round | Grid Size | Number of Pairs |
|---------|-----------|----------------|
| 1 | 4 × 4 | 8 |
| 2 | 5 × 4 | 10 |
| 3 | 6 × 4 | 12 |
| 4 | 7 × 4 | 14 |
| 5 | 8 × 4 | 16 |

Each completed round increases the board size and number of pairs, creating a progressively more challenging memory experience.

---

## User Interface Features

### Heads-Up Display (HUD)

Displays:

- Player Name
- Current Score
- Time Remaining
- Current Round
- Best Score

### Visual Effects

- Neon glow animations
- Animated background grid
- Floating particle effects
- Match celebration effects
- Streak bonus popups
- Card flip and reveal animations
- Dynamic timer warning effects

### Timer Alerts

- Gold warning when 10 seconds remain
- Red critical alert when 5 seconds remain
- Visual pulse effects during critical countdown

---

## Accessibility Support

The game includes several accessibility-focused features:

- Full keyboard navigation
- Focus-based card selection
- Enter and Space key activation
- Responsive layouts
- High-contrast visual design
- Name validation before gameplay
- Touch-friendly controls

---

## Technologies Used

### Front-End Technologies

- HTML5
- CSS3
- Vanilla JavaScript (ES6)

### Browser APIs

- Web Audio API
- Local Storage API

### Design Techniques

- CSS Grid
- CSS Flexbox
- CSS Animations
- Responsive Web Design

---

## Sound Design

All game sounds are generated dynamically using the **Web Audio API**.

Sound effects include:

- Card Flip
- Match Success
- Mismatch Feedback
- Round Completion
- Timer Warning
- Button Interaction

No external audio files are used.

---

## Data Storage

### Local Storage

The browser stores:

- Personal Best Score
- Audio Preference (Muted / Unmuted)

No personal information is collected, shared, or transmitted.

---

## Browser Requirements

### Supported Browsers

- Microsoft Edge (Current Version)
- Google Chrome (Current Version)

### Required Browser Features

- ES6 JavaScript Support
- CSS Grid Support
- Web Audio API Support
- Local Storage Support

---

## Launch Instructions

### Direct Launch

1. Download or extract the project folder.
2. Open `index.html` using:
   - Microsoft Edge
   - Google Chrome
3. Enter your name and press **Start Game**.
4. Enjoy the game.

### Static Server (Optional)

The project may also be served through any static file server.

No installation or build process is required.

---

## Internet Dependency

**None**

The game works fully offline and does not make any external network requests.

---

## Mobile Support

The game is optimized for:

- Android Devices
- iPhone Devices
- Tablets
- Touchscreen Laptops

Responsive layouts ensure usability across multiple screen sizes and orientations.

---

## Assets and Credits

### Visual Assets

- Standard Unicode Emoji Characters
- CSS-Generated Background Effects
- CSS-Based Cards and Animations

### Audio Assets

- Generated dynamically using the Web Audio API

### Third-Party Resources

None

### External Libraries

None

### External Fonts

None

### External Images

None

---

## AI Tool Used

**Microsoft Copilot**

### AI Contribution

Microsoft Copilot assisted with:

- Game logic refinement
- User interface improvements
- Accessibility enhancements
- Visual effect concepts
- Code review and debugging
- Performance optimization suggestions
- Documentation drafting

All AI-assisted content was reviewed, tested, modified, and validated by the team. The participants remain fully responsible for the functionality, security, quality, originality, and competition compliance of the final submission.

---

## Browsers Tested

- [ ] Microsoft Edge (Current Version)
- [ ] Google Chrome (Current Version)


---

## Known Limitations

- Local Storage may not persist in private or incognito browsing modes.
- Browser autoplay policies may delay sound initialization until the first user interaction.
- Very large board sizes may require slight vertical scrolling on smaller mobile devices.
- Game progress is not saved between sessions except for the personal best score.

---

## Compliance Statement

- Fully offline browser application
- No external servers required
- No analytics or tracking
- No network requests
- No account registration required
- No third-party libraries used
- All gameplay executes locally within the browser

---

# Thank You for Playing Neon Memory Matrix

### **Remember Fast. Match Faster. Beat Your Best.**

**Team Q-Void**
- Alfin Varghese
- Sachin John Thomas
