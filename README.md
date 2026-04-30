 🪙 CoinWise
CoinWise is a web-based smart optimization tool that compares Greedy and Dynamic Programming (DP) approaches to determine the minimum number of coins required for a given amount.

Built using C, Node.js, and a modern web interface, CoinWise highlights optimal vs non-optimal solutions while maintaining computation history for analysis.

🚀 Features
🪙 Real-time comparison of Greedy vs Dynamic Programming
📊 Interactive dashboard with clear result visualization
💾 History tracking with export functionality
⚡ High-performance C-based computation engine
🪟 Cross-platform support (Windows, Linux, macOS)
✅ Strong input validation and error handling
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js (Express)
Core Engine: C Programming
▶️ Getting Started
🔹 Clone the Repository
git clone https://github.com/your-username/CoinWise.git
cd CoinWise
🔹 Install Backend Dependencies
cd backend
npm install
🔹 Start the Server
npm start
🔹 Open in Browser
http://localhost:3000
📂 Project Structure
CoinWise/
│
├── backend/              # Node.js Express server
│   ├── server.js         # API & routing
│   ├── package.json
│   └── package-lock.json
│
├── c_program/            # Core algorithm engine
│   ├── coin_optimizer.c  # Greedy & DP logic
│   ├── Makefile          # Build configuration
│   └── history.txt       # Auto-generated history
│
├── frontend/             # User interface
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md
⚙️ How It Works
Frontend: Collects user input and displays comparison results

Backend (Node.js): Handles API requests and communicates with the C executable

C Program: Executes:

Greedy algorithm
Dynamic Programming algorithm
History System: Stores all computations in history.txt

🧮 Algorithm Details
🔹 Greedy Approach
Selects the largest coin first
Faster execution
❌ May not produce optimal result
🔹 Dynamic Programming
Uses subproblems to compute minimum coins
✅ Always produces optimal result
Slightly higher computation cost
🌟 Future Enhancements
📈 Graph-based performance comparison
📱 Fully responsive mobile UI
🔐 User authentication system
☁️ Cloud deployment improvements
📜 License
This project is licensed under the MIT License.
