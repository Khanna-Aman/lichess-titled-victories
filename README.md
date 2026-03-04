# 🏆 Lichess Titled Players Beaten Tracker

Track how many titled players you've defeated on Lichess! Analyze your games to see victories against Grandmasters, International Masters, and other titled players.

## 🚀 Quick Start

1. **Download** the notebook: `lichess_titled_players_tracker.ipynb`
2. **Open** in Jupyter Notebook, JupyterLab, or Google Colab
3. **Run all cells** (Cell → Run All)
4. **Enter your Lichess username** and click "Analyze Games"

## ✨ Features

- 🎯 **Track all titled players**: GM, IM, FM, CM, WGM, WIM, WFM, WCM, NM, LM
- 📊 **Unique opponents**: See distinct titled players beaten vs total game wins
- 📈 **Rich visualizations**: Bar charts, rating histograms, win timelines, time control breakdown
- 🔄 **Comparison mode**: Compare two players side-by-side with head-to-head charts
- 💾 **Auto-export CSV**: Detailed game data saved automatically
- 🔁 **Retry logic**: Automatic retries with exponential backoff on API errors
- ⚡ **Progress bar**: Live progress tracking during game fetching
- 🆓 **Completely free**: No tokens or authentication required
- 🎮 **Easy to use**: Simple interface, no coding required

## 🎯 What It Tracks

### Titles Supported
- **GM** - Grandmaster
- **IM** - International Master  
- **FM** - FIDE Master
- **CM** - Candidate Master
- **WGM** - Woman Grandmaster
- **WIM** - Woman International Master
- **WFM** - Woman FIDE Master
- **WCM** - Woman Candidate Master
- **NM** - National Master
- **LM** - Lichess Master

### Time Controls
- Bullet (< 3 minutes)
- Blitz (3-8 minutes)
- Rapid (8-25 minutes)
- Classical (25+ minutes)
- Correspondence (turn-based)

## 🆓 Completely Free

- **No registration required** - works immediately
- **No API tokens needed** - uses free Lichess API
- **Respects rate limits** - automatic retry with backoff if rate-limited

## 📋 Requirements

- Python 3.6+
- Jupyter Notebook/Lab or Google Colab
- Internet connection

**Dependencies** (auto-installed):
- `requests` - API calls
- `pandas` - Data analysis
- `ipywidgets` - Interactive interface
- `matplotlib` - Charts and visualizations

## 🎮 Usage Examples

### Basic Analysis
```
Username 1: your_lichess_username
Time Control: All time controls
Game Scope: Recent 500 games
```

### Comparing Two Players
```
Username 1: player_one
Username 2: player_two
Time Control: Blitz
Game Scope: Recent 1000 games
```

### Complete History
```
Username 1: your_lichess_username
Time Control: All time controls
Game Scope: All games (complete history)
```

## 📊 Sample Output

```
🏆 YOUR_USERNAME vs TITLED PLAYERS

📊 RESULTS (wins / unique opponents):
  IM: 5  (3 unique)
  FM: 8  (5 unique)
  CM: 2

🎉 TOTAL: 15 wins against 10 unique titled players!

💾 Results saved to: your_username_titled_players.csv
📁 Contains 15 games with full details
```

### Visualizations Include
- **Wins by Title** - Bar chart showing victories per title category
- **Opponent Rating Distribution** - Histogram with average rating line
- **Titled Wins Over Time** - Cumulative timeline of your titled scalps
- **Wins by Time Control** - Pie chart breakdown (Bullet, Blitz, Rapid, etc.)

## 🔧 Troubleshooting

**No games found?**
- Check username spelling
- Ensure you have rated games

**No titled players found?**
- Try increasing game scope
- This is normal for newer players
- Try different time controls

**Slow analysis?**
- Reduce game scope
- Start with 100-500 games
- Try again later if busy

**Rate limit errors?**
- The tool automatically retries with backoff
- Wait a moment and try again if it persists

## 🛡️ Privacy & Security

- **No data stored**: Analysis happens locally in your browser
- **No authentication**: Uses public API, no login required
- **Read-only access**: Only reads your public game data
- **No personal info**: Only analyzes game results
- **No API keys**: Zero credentials required or stored

## 📝 License

MIT License - See [LICENSE](LICENSE) for details.

## 🤝 Contributing

Found a bug or want to add features? 
- Open an issue
- Submit a pull request
- Share feedback

## 🙏 Credits

- **[Lichess](https://lichess.org)**: For the amazing free chess platform and API
- **Chess community**: For inspiration and feedback

---

**Happy hunting for titled scalps!** 🏆

*Track your chess journey and see how you stack up against the masters!*
