🎮 WordCraft - Interactive Word Game

A responsive word-scrambling game built with vanilla JavaScript, demonstrating modern web development practices and clean code architecture.

🎯 Play Live Demo: https://yourusername.github.io/wordcraft-game/

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✨ Features

🚀 Pure Vanilla JavaScript - No frameworks or dependencies, just clean ES6+ code
📱 Responsive Design - Seamless experience across mobile, tablet, and desktop devices
📊 Real-time Statistics - Dynamic tracking of score, attempts, games played, and win streaks
💡 Progressive Hint System - Optional hints with strategic point penalties
🏆 Achievement System - Visual feedback and rewards for maintaining win streaks
✨ Smooth Animations - Polished UI with CSS transitions and keyframe animations
⌨️  Keyboard Support - Full keyboard navigation and Enter key submission

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🛠️ Technologies

💻 Vanilla JavaScript (ES6+)
🌐 HTML5
🎨 CSS3 (Flexbox, Grid, Gradients, Animations)
🔧 Modern DOM APIs

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🎯 Key Technical Highlights

⚡ Efficient DOM Manipulation - Cached element references and minimal reflows
🔀 Fisher-Yates Shuffle Algorithm - Proper randomization for word scrambling
🎪 Event-Driven Architecture - Clean separation of game logic and UI updates
💾 State Management - In-memory state tracking with organized data structures
🌍 Cross-browser Compatibility - Works on all modern browsers
📐 Mobile-first Design - Responsive breakpoints and touch-friendly controls

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📖 How to Play

1️⃣ Look at the scrambled word displayed on screen
2️⃣ Type your answer in the input field
3️⃣ Press Enter or click Submit to check your answer
4️⃣ Use hints if you're stuck (each hint costs 2 points)
5️⃣ Skip difficult words or reset the game anytime
6️⃣ Build the longest winning streak possible!

┌─────────────────────────────────────────────┐
│  🎮 GAME STATS                              │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  │
│  📈 Score: Track your points                │
│  🎯 Attempts: Total guesses made            │
│  🎲 Games: Words completed                  │
│  🔥 Streak: Consecutive wins                │
└─────────────────────────────────────────────┘

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🏗️ Project Structure

📦 wordcraft-game/
 └── 📄 index.html          (Complete self-contained game)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

💻 Local Development

🔽 Clone the repository:
   git clone https://github.com/yourusername/wordcraft-game.git

📂 Navigate to directory:
   cd wordcraft-game

🌐 Open in browser:

   Option 1: Direct file open
   open index.html

   Option 2: Local server (recommended)
   python -m http.server 8000
   🔗 Visit http://localhost:8000

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🌐 Browser Support

✅ Chrome/Edge 90+
✅ Firefox 88+
✅ Safari 14+
✅ Mobile browsers (iOS Safari, Chrome Mobile)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📱 Responsive Design

The game adapts to different screen sizes:

📱 Mobile: < 640px 
   → Optimized touch controls and simplified layout
   
📱 Tablet: 640px - 1024px
   → Balanced grid layouts
   
🖥️ Desktop: > 1024px
   → Full-featured experience with hover effects

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🎨 Customization

🔤 Adding Custom Words

Edit the words array in the JavaScript section:

const words = [
    'REACT', 'JAVASCRIPT', 'PYTHON', 
    'YOUR', 'CUSTOM', 'WORDS'
];

🎨 Changing Colors

Modify the gradient backgrounds in the CSS:

body {
    background: linear-gradient(135deg, #your-color-1, #your-color-2);
}

⚙️ Adjusting Difficulty

Modify the scoring system:

// Change point calculation in checkAnswer function
let points = Math.max(10 - hintsUsed * 2, 1); // Adjust multiplier

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

⚡ Performance Features

🎯 Minimal DOM queries through element caching
🚀 CSS animations using transform and opacity (GPU-accelerated)
⚙️ Efficient O(n) scrambling algorithm
🧹 Event listener cleanup and proper memory management
📊 Optimized repaint/reflow cycles

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🎓 Learning Outcomes

This project demonstrates:

✔️ DOM manipulation and event handling
✔️ Algorithm implementation (Fisher-Yates shuffle)
✔️ State management without frameworks
✔️ Responsive CSS design patterns
✔️ User experience and feedback design
✔️ Game logic and scoring systems

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🤝 Contributing

Contributions are welcome! Feel free to:

1️⃣ 🍴 Fork the repository
2️⃣ 🌿 Create a feature branch (git checkout -b feature/AmazingFeature)
3️⃣ 💾 Commit your changes (git commit -m 'Add some AmazingFeature')
4️⃣ 📤 Push to the branch (git push origin feature/AmazingFeature)
5️⃣ 🔃 Open a Pull Request

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🔮 Future Enhancements

⭐ Difficulty levels (Easy/Medium/Hard)
⏱️ Timer mode for speed challenges
🏅 Leaderboard system
🔊 Sound effects and audio feedback
📚 Multiple word categories
📅 Daily challenges
👥 Multiplayer mode
🌙 Dark mode toggle
🎯 Achievement badges
📊 Progress tracking graphs

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📊 Game Statistics

┌───────────────────────────────────────────┐
│  💯 Points System                         │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  │
│  🎯 Correct Answer: 10 points             │
│  💡 First Hint: -2 points                 │
│  💡 Second Hint: -2 points                │
│  🔥 Streak Bonus: Visual achievement      │
└───────────────────────────────────────────┘

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

👤 Author

👨‍💻 Aditya Keshari Swain

🔗 GitHub: @adityakswain190 (https://github.com/adityakswain190)
💼 LinkedIn: Aditya Swain ([https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/aditya-swain-186827309/))
📧 Email: adityaswain190@gmail.com

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🙏 Acknowledgments

💭 Inspired by classic word puzzle games
🎯 Built as a portfolio demonstration project
♿ Designed with accessibility and user experience in mind
📚 Created for educational purposes

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

⭐ If you found this project helpful, please consider giving it a star!

📧 Questions or feedback? Open an issue or reach out directly.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Made with ❤️ and ☕ by Aditya Swain

🎮 Happy Gaming! 🎮
