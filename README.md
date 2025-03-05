# Coin-Dodge-Game
# Coin Dodge Game

## Setup and Hosting Instructions

### Prerequisites
- GitHub Account
- Git installed on your computer

### Hosting Steps
1. Create a New Repository
   ```bash
   # Create a new directory for your project
   mkdir coin-dodge-game
   cd coin-dodge-game

   # Initialize a new git repository
   git init
   ```

2. Create Game Files
   - Create an `index.html` file with the contents provided
   - Create a `.gitignore` file (optional)

3. Push to GitHub
   ```bash
   # Add files to git
   git add .
   git commit -m "Initial commit of Coin Dodge Game"

   # Create a new repository on GitHub
   # Then add the remote and push
   git remote add origin https://github.com/YOUR-USERNAME/coin-dodge-game.git
   git branch -M main
   git push -u origin main
   ```

4. Enable GitHub Pages
   - Go to your repository on GitHub
   - Settings > Pages
   - Select "main" branch
   - Save

### Deployment Notes
- The game will be live at `https://YOUR-USERNAME.github.io/coin-dodge-game/`
- Update the `GAME_URL` constant in the HTML with this exact URL

### Gameplay
- Move your mouse to control the blue player
- Collect gold coins to increase score
- Avoid red bullets
- Game ends when lives reach zero
