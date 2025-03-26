#Quiz App 
<p>The Quiz App is a dynamic quiz application that fetches trivia questions from the <strong>OpenTDB API</strong>. Users can select quiz categories and difficulty levels, answer multiple-choice questions, and track their scores.</p>

<h2>✨ Features</h2>
<ul>
    <li><strong>Category & Difficulty Selection:</strong> Customize your quiz experience.</li>
    <li><strong>Real-time Question Fetching:</strong> Questions are retrieved dynamically from the OpenTDB API.</li>
    <li><strong>Score Tracking:</strong> Keeps track of correct answers and displays final results.</li>
    <li><strong>Responsive UI:</strong> Built with Tailwind CSS for a seamless experience across devices.</li>
</ul>

<h2>🛠️ Tech Stack</h2>
<ul>
    <li>Frontend: React.js, Tailwind CSS</li>
    <li>API: OpenTDB API</li>
    <li>State Management: React useState & useEffect</li>
</ul>

<h2>⚡ Installation & Setup</h2>
<h3>1️⃣ Clone the Repository</h3>
<pre><code>git clone https://github.com/yourusername/quiz-app.git

<h3>2️⃣ Install Dependencies</h3>
<pre><code>npm install</code></pre>

<h3>3️⃣ Start the Application</h3>
<pre><code>npm start</code></pre>
<p>The application will be running at <strong>http://localhost:3000</strong>.</p>

<h2>📜 API Usage</h2>
<p>The app fetches quiz questions from OpenTDB API using the following endpoint:</p>
<pre><code>https://opentdb.com/api.php?amount=10&category=XX&difficulty=medium&type=multiple</code></pre>
<p>Replace <code>XX</code> with the desired category ID.</p>

<h2>🚀 Future Enhancements</h2>
<ul>
    <li>Leaderboard system to track top scores.</li>
    <li>Timer-based quizzes for a more challenging experience.</li>
    <li>Dark mode support.</li>
</ul>

<h2>💡 Contributing</h2>
<p>Contributions are welcome! Fork the repository and submit a pull request.</p>
