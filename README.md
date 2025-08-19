## 🏈 Sleeper Matchups

A TRMNL recipe that displays real-time fantasy football league matchups from Sleeper, showing head-to-head matchups between teams with their scores and performance.

<img width="976" height="656" alt="image" src="https://github.com/user-attachments/assets/a4abd239-0dbb-49e2-9df0-4cba7bcd870c" />

### Configuration

To use this recipe, you'll need to set in `.trmnlp.yml`:

1. **League ID**: Get your Sleeper League ID from the [Sleeper League Finder](https://sleeper-league-finder.divine-wood-7de9.workers.dev/)
2. **Week**: Set the current week to display specific matchups
3. **League Name** (optional): Display your league name in the title bar
4. **Week Reminder**: Shows a hint when the configured week doesn't match the API's current week 


### Data Displayed

The plugin shows the following information for each matchup:
- **Team Names**: Custom team names or fallback to "Team [Display Name]"
- **Owner Names**: Display names of the team owners
- **Scores**: Current fantasy points for each team
- **Matchup Results**: Visual indication of which team is winning

### Development
Can be served via [trmnlp](https://github.com/usetrmnl/trmnlp). Install trmnlp and run
```
trmnlp serve
```
