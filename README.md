# 🏆 Lichess Titled Players Beaten Tracker

Track how many titled players you've defeated on Lichess! Analyze your games to see victories against Grandmasters, International Masters, and other titled players.

## 🚀 Quick Start

1. **Download** the notebook: `lichess_titled_players_tracker.ipynb`
2. **Open** in Jupyter Notebook, JupyterLab, or Google Colab
3. **Run all cells** (Cell → Run All)
4. **Enter your Lichess username** and click "Analyze Games"

## ✨ Features

- 🎯 **Track all titled players**: GM, IM, FM, CM, WGM, WIM, WFM, WCM, NM, LM
- 📊 **Clean summary**: Just the counts you want to see
- 💾 **Auto-export CSV**: Detailed game data saved automatically
- ⚡ **Flexible analysis**: Choose time controls and game scope
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
- **No rate limits** - reasonable usage is always allowed

## 📋 Requirements

- Python 3.6+
- Jupyter Notebook/Lab or Google Colab
- Internet connection

**Dependencies** (auto-installed):
- `requests` - API calls
- `pandas` - Data analysis
- `ipywidgets` - Interactive interface

## 🎮 Usage Examples

### Basic Analysis
```
Username: your_lichess_username
Time Control: All time controls
Game Scope: Recent 500 games
```

### Specific Format
```
Username: your_lichess_username  
Time Control: Bullet
Game Scope: Recent 1000 games
```

### Complete History
```
Username: your_lichess_username
Time Control: All time controls
Game Scope: All games (complete history)
```

## 📊 Sample Output

```
🏆 YOUR_USERNAME vs TITLED PLAYERS

📊 RESULTS:
  IM: 3
  FM: 8
  CM: 2

🎉 TOTAL: 13 titled players beaten!

💾 Results saved to: your_username_titled_players.csv
📁 Contains 13 games with full details

📋 Preview (first 3 games):
Title | Opponent    | Rating | Date       | Time_Control
IM    | PlayerName1 | 2650   | 2024-01-15 | Bullet
FM    | PlayerName2 | 2450   | 2024-01-20 | Blitz
IM    | PlayerName3 | 2580   | 2024-01-10 | Rapid
```

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
- Wait a moment and try again
- Lichess API is very generous with free usage

## 🛡️ Privacy & Security

- **No data stored**: Analysis happens locally in your browser
- **No authentication**: Uses public API, no login required
- **Read-only access**: Only reads your public game data
- **No personal info**: Only analyzes game results

## 📝 License

MIT License - Feel free to use, modify, and share!

## 🤝 Contributing

Found a bug or want to add features? 
- Open an issue
- Submit a pull request
- Share feedback

## 🙏 Credits

- **Lichess**: For the amazing free chess platform and API
- **Chess community**: For inspiration and feedback
- **Contributors**: Everyone who helped improve this tool

---

**Happy hunting for titled scalps!** 🏆

*Track your chess journey and see how you stack up against the masters!*
