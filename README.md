EduGenie 🧞‍♂️💻
Google Gemini-Powered AI Learning & Coding Assistant

================================================================================

1. OVERVIEW
EduGenie is an intelligent, interactive learning platform designed to help students 
and developers master computer science and programming concepts. Powered by Google 
Gemini, EduGenie acts as an adaptive tutor that explains complex algorithms, debugs 
code step-by-step, and generates interactive quizzes to reinforce core concepts.

================================================================================

2. FEATURES
• Socratic Code Tutoring: Guides users through bugs and logic errors with hint-based 
  steps instead of just dumping answers.
• Line-by-Line Code Breakdown: Paste any code snippet (Python, JavaScript, C++, 
  Java, Rust, SQL, etc.) to get an instant structural explanation.
• Automated Quiz & Flashcard Generator: Automatically converts coding topics into 
  adaptive quizzes and spaced-repetition flashcards.
• Refactoring & Optimization: Analyzes code for time and space complexity 
  (O(n) analysis) and suggests cleaner patterns.
• Interactive Chat Context: Retains multi-turn conversation context to adapt to 
  your learning pace and preferred style.

================================================================================

3. TECH STACK
• AI Model: Google Gemini API (gemini-1.5-pro / gemini-1.5-flash)
• Frontend: Next.js / React, Tailwind CSS
• Backend: Node.js / Express or Python (FastAPI)
• Database: PostgreSQL / Supabase or MongoDB (for user progress & saved flashcards)

================================================================================

4. QUICK START GUIDE

Step 1: Prerequisites
- Node.js (v18 or higher) or Python 3.10+
- A Google Gemini API Key from Google AI Studio (https://aistudio.google.com/)

Step 2: Clone the Repository
$ git clone https://github.com/your-username/edugenie.git
$ cd edugenie

Step 3: Environment Setup
Create a .env.local file in the root directory:
GEMINI_API_KEY=your_google_gemini_api_key_here
PORT=3000

Step 4: Install Dependencies
# Node.js / Next.js:
$ npm install

# Python FastAPI:
$ pip install -r requirements.txt

Step 5: Run the Application
# Node / Next.js:
$ npm run dev

# Python FastAPI:
$ uvicorn main:app --reload

Open http://localhost:3000 in your browser to start using EduGenie.

================================================================================

5. SYSTEM PROMPT EXAMPLE
You are EduGenie, an encouraging and highly skilled computer science tutor powered 
by Google Gemini. Your goal is to guide students through coding challenges using the 
Socratic method.
- Explain concepts using concise language, helpful metaphors, and step-by-step breakdowns.
- When reviewing student code errors, point out the issue gently and ask guiding 
  questions before providing full solutions.
- Include time/space complexity analysis (O(n)) when reviewing algorithms.

================================================================================

6. LICENSE & CONTRIBUTIONS
Distributed under the MIT License. Contributions are welcome via GitHub Pull Requests.
