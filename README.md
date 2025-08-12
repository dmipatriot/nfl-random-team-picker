# NFL Super Bowl Draft Picker

A simple one-page web app to randomly assign NFL teams to fantasy football league members.  
Perfect for side pots like:  
> Each league member gets a random NFL team on draft day.  
> If your team wins the Super Bowl, you win the pot.  

Built using React (via CDN) + Tailwind CSS. No build process — just static HTML.

---

## 📌 Features
- **Random Team Assignment** — Click to assign a random NFL team to each entry (no repeats).
- **Custom Names** — Paste your league’s names (or use default `Team 1…Team 12`).
- **Live Remaining Pool** — Shows which teams are still unassigned.
- **Undo / Reset** — Mistake? Undo last pick or reset the whole draft.
- **Copy to Clipboard** — Instantly copy results for sharing.
- **CSV Export** — Download all assignments as a `.csv` file.
- **Mobile-Friendly** — Works on phone, tablet, or desktop.

---

## 🚀 How to Use

1. **Open the App**  
   Visit the GitHub Pages link for this repo (example:  
   `https://YOUR-USERNAME.github.io/nfl-random-team-picker/`).

2. **Enter Names**  
   - Paste one name per line in the text area.  
   - Or leave blank to auto-fill with `Team 1`, `Team 2`, etc.

3. **Start the Draft**  
   Click **Start Draft** to initialize the random team pool.

4. **Assign Teams**  
   - Click the green **Pick Team** button to assign a random NFL team to the next manager.
   - Keep clicking until all names have a team.

5. **Save or Share Results**  
   - Click **Copy Results** to copy to clipboard for a group chat.
   - Click **Download CSV** for a spreadsheet record.

---

## 🛠 Local Setup (Optional)

If you want to run it locally without GitHub Pages:
```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/nfl-random-team-picker.git

# Open index.html in your browser
open index.html
