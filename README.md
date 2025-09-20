#  Support & Resistance – TradingView Pine Script

This is a small TradingView Pine Script I made that automatically draws **support and resistance levels** based on swing highs and swing lows. Super useful for spotting where price might bounce, reverse, or break out.

---

## How it Works

- **Support** = a “floor” where price tends to stop falling. Usually formed at **swing lows**.  
- **Resistance** = a “ceiling” where price tends to stop rising. Usually formed at **swing highs**.  

Basically, the script looks for swing highs/lows and draws horizontal lines so you can see key levels at a glance.

---

## What You Get

<img width="735" height="351" alt="Screenshot 2025-09-20 143425" src="https://github.com/user-attachments/assets/52d39aab-a47b-4d54-9a71-79de5145b24f" />


- Detects swing highs and swing lows automatically.  
- Draws **horizontal lines** for support/resistance that extend across the chart.  
- Optional **labels** (“S” for support, “R” for resistance).  
- Adjustable **swing length** so you can capture bigger or smaller moves.  
- Automatically cleans up old lines so your chart doesn’t get messy.

---

## Inputs

| Input | What it does | Default |
|-------|-------------|---------|
| Swing Length | How many candles before/after to check for a swing | 5 |
| Show Labels | Toggle “S” and “R” labels on/off | true |
| Max Lines | Max number of lines to show on chart | 50 |

---

## How to Use

1. Open TradingView and go to **Pine Editor**.  
2. Paste the script (`support_resistance.pine`).  
3. Click **Add to Chart**.  
4. Adjust inputs if you like:
   - Increase **Swing Length** to catch bigger swings.  
   - Toggle **Show Labels** if you want it cleaner.  
   - Change **Max Lines** to avoid clutter.  

---

## Why It’s Handy

- Quickly see areas where price might bounce or reverse.  
- Spot potential **breakouts** when price passes support or resistance.  
- Great for swing trading, day trading, or just getting a feel for key levels.  

---

## Author

[Radin Ansari](https://github.com/RADINANSARI) 
