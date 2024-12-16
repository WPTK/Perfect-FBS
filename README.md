# 🏈 The Perfect FBS College Football Schedule  

Welcome to my research project focused on building the **Perfect FBS College Football Schedule**. This project seeks to rethink the way college football schedules are created by removing **strength of schedule bias**, **conference favoritism**, and other unfair advantages that exist in the current system.  

Through analysis, iteration, and thoughtful experimentation, I aim to develop a model that delivers a **fair and balanced schedule** for all FBS teams.

---

## 🎯 Project Goal  

The goal is to create a scheduling system that:  

- **Ensures Fairness**: Every team has an equal shot at success.  
- **Reduces Bias**: No team benefits from conference affiliation, strength of schedule perceptions, or geographic favoritism.  
- **Preserves Tradition**: Historic rivalries (e.g., *Ohio State vs Michigan*) are maintained to enhance the excitement of the season.  
- **Maximizes Balance**: Equally weighted conference and non-conference matchups without repetition of opponents or unfair travel burdens.  

---

## 📖 Why This Matters  

The current FBS scheduling system suffers from:  

- **Strength of Schedule Bias**: Some teams play tougher opponents, artificially boosting or harming their playoff chances.  
- **Conference Bias**: Power conferences dominate, while Group of Five programs are excluded from fair playoff opportunities.  
- **Uneven Matchups**: Certain teams schedule weak out-of-conference opponents to inflate their win totals.  
- **Rivalry Dilution**: Traditional rivalries are sometimes neglected or overshadowed by conference realignment. 

---

## 🔬 Research & Methodology  

This project focuses on **iterative development** and **experimentation**:  

### 1. **Data Collection**  
Gather detailed information about FBS teams, including:  
   - **Schools**: Names, locations, enrollments, and nicknames.  
   - **Current Conferences**: Existing alignments (e.g., SEC, Big Ten).  
   - **Former Conferences**: Historical affiliations for context in out-of-conference games.  
   - **Rivalries**: Traditional matchups that must be prioritized.
   - **Must Plays**: 2nd and 3rd level rivalries that are historically important to the game or the fanbases.

### 2. **Scheduling Rules**  
   - Every team plays **12 games** with **3 bye weeks**.  
   - A designated **"Rivalry Week"** ensures teams play their top rival. May have to make up making 2 Rivalry weeks so people can watch them all.
   - Equal weighting for:  
     - **Conference games** (3-5 per team).  
     - **Out-of-conference games** (3-5 per team), prioritizing teams with shared former conferences.
     - **Everything else**
   - Seems obvious, but: 
       - No team plays more than **one game per week**.
       - No team faces the **same opponent twice** in the regular season.  

### 3. **Iterations**  
   - Start with simple schedule generation.  
   - Incorporate rivalries and former conference relationships.
   - Incorporate "must plays" 
   - Refine to balance **travel distances** and **game diversity**.  

### 4. **Testing Fairness**  
Evaluate fairness by analyzing:  
   - Frequency of matchups across multiple iterations.  
   - Consistency in opponent strength without bias.  
   - Travel distance balance between teams.  

---

## ⚙️ Progress So Far  

### 1. **Data Preparation**  
   - Schools and rivalries have been mapped using real-world FBS data.  
   - Traditional rivalries (e.g., *Alabama-Auburn*, *Army-Navy*) are accounted for.  

### 2. **Schedule Generation**  
   - "Sucessfully" generated a **12-game schedule** for:  
     - 5 Random FBS teams.  
     - Specific conferences
     - They weren't pretty, but did they did generate.
   - Designed **"Rivalry Week"** where all teams play their rivals on the same week.  

### 3. **Rule Implementation**  
   - Enforced **single-game matchups** and **3 evenly spaced bye weeks**.  

---

## 🚧 / 💡 Next Steps / Future Enhancements  

- **Expand Rules**: Introduce travel constraints to ensure fairness in out-of-conference games.  
- **Include "Must Plays" Outside of Rivalries**: Auburn and Georgia are not each others largest rivals, but it's a game that must be played. More examples like this, possibly up to 3. 
- **Historical Context**: Prioritize games with historic conference ties to preserve traditions.
- **Historic W-L**: Not entirely sure on this one, but maybe some way to identify prestige based on a 3, 5, and 10 year W-L for some better matchups

- Explore **travel constraints** to ensure geographic fairness.  
- Develop a **visual tool** for schedule visualization and analysis.  
- Test models to ensure all teams have an equal probability of making playoffs.  
- Consider **user-defined constraints** (e.g., custom rivalry settings or conference rules)

---

## 🛠️ Tools & Technologies  

- **Python**: Core scheduling logic and data manipulation.  
- **Pandas**: Handling large datasets efficiently.  
- **Excel**: Input/output of team data and schedules.
- **ChatGPT**: I am weak 

---

## 🚀 Follow Along  

I'd like to get the first raw data upload by early 2025, at the earliest. 
