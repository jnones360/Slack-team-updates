# Slack-team-updates
Fun and creative way to share updates based on your vibe

# 🎮 Friday Standup Games

A collection of interactive mini-games for Friday morning standup updates! Because standups should be fun. 🎉

## 🔗 Current Week's Game
👉 **[Play This Week's Game](https://jnones360.github.io/Slack-team-updates/)**
```

## ✅ Test Your Game Directly:

**Right now, open this URL in a new tab:**
```
https://jnones360.github.io/Slack-team-updates/

## 📅 How It Works

Every Friday morning, play a quick 2-minute game before getting the standup update. Games rotate weekly to keep things fresh and fun!

## 🗂️ Game Archive

- **Week of Feb 14, 2025** - [🦆 Duck Race](week-2025-02-14.html)
- _(More games added each week!)_

## 🎯 Games Library

### Current Games:
1. **🦆 Duck Race** - Bet on racing ducks, see who wins!
2. _(More coming soon!)_

## 🛠️ For Maintainers

### Adding a New Game Each Week:

1. **Create the dated file:**
   ```bash
   # Copy template or create new game
   cp template.html week-2025-02-XX.html
   ```

2. **Update your standup info** in the new file:
   - Find the `standup-update` section
   - Update "Yesterday" and "Today" bullets
   - Update your meme-scale number

3. **Make it live:**
   ```bash
   # Copy to index.html so main link always works
   cp week-2025-02-XX.html index.html
   
   # Commit and push
   git add .
   git commit -m "Add week of Feb XX game"
   git push
   ```

4. **Share in Slack:**
   ```
   Good morning team! 🎮
   Friday game time before the update!
   👉 https://[your-company].github.io/standup-games/
   
   Drop your results in the thread! 🎉
   ```

### Quick Update Template:
```html
<!-- Find this section in your HTML file -->
<div class="meme-scale">
    On a meme scale, I'm feeling like a <strong>6</strong>! Happy Friday! 🎉
</div>

<div class="standup-section">
    <h3>🔙 Yesterday</h3>
    <ul>
        <li>UPDATE THIS</li>
        <li>UPDATE THIS</li>
    </ul>
</div>

<div class="standup-section">
    <h3>📅 Today</h3>
    <ul>
        <li>UPDATE THIS</li>
        <li>UPDATE THIS</li>
    </ul>
</div>
```

## 🎨 Game Ideas for Future Weeks

- 🎲 Dice rolling prediction game
- 🎯 Target shooting game
- 🏇 Horse racing
- 🎰 Slot machine
- 🎪 Carnival games
- 🌈 Color matching game

## 📝 Notes

- Games are designed to take ~2 minutes max
- All games are self-contained HTML files (no external dependencies)
- Mobile-friendly and accessible
- Standup update appears at the end of each game

## 🤝 Contributing

Have a fun game idea? Feel free to add it to the collection!

---

**Made with ❤️ for fun Friday standups**
