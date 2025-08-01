# JS-Project

<img width="1863" height="869" alt="Screenshot 2025-08-01 234423" src="https://github.com/user-attachments/assets/0b6d4654-10a6-4cf7-9c21-a02673f27a8d" />

<h4>🎮 Simon Says</h4>
<p>A simple memory-based game where the player must repeat an ever-growing sequence of signals.</p>


🛠️ Setup
<p>Create source files for HTML/CSS/JS (or your chosen language).
Add interactive components: Start button, visual pads (e.g. 4 colored buttons), status display.</p>


🚀 Game Flow
<p>◆ Start Game
Player clicks Start → interface resets → computer begins the sequence.
◆ Computer Turn
Randomly select and display a new step (e.g. flash a pad + play tone).
Append it to the computer’s sequence array.
◆ Player Turn
Player repeats the sequence by clicking pads.
After each click, check if input matches the corresponding computer value.
◆ Validation
If a mismatch: show a failure message and reset.
If correct and sequence is complete: proceed to next round.
Optionally, win the game after reaching a defined maximum length (e.g. 20 rounds).</p>

🎯 UI
<p>Show current level or round.
Disable clicks during the computer’s turn.
Update status messages.</p>


📂 Suggested File Structure (example)
<p></p>
├── index.html       ← Game layout and controls  
├── styles.css       ← Visual design  
└── app.js          ← Game logic,sequence control,event handlers 


✅ Summary
<p>
Step 1: Player clicks Start.
Step 2: Computer displays a growing random sequence.
Step 3: Player repeats the sequence.
Step 4: Game checks input; continues or resets.
Step 5  Player wins after high Score🏆.</p>


<img width="1863" height="858" alt="Screenshot 2025-08-01 234354" src="https://github.com/user-attachments/assets/b40f56c7-7bf4-462e-9269-44aab5a5ed24" />
