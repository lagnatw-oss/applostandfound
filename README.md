AI-Powered Lost & Found Matcher
A simple web application that uses the Google Gemini AI to intelligently match lost and found items based on user-provided descriptions. This project was built as a submission for the ED-Cell Technical Wing Induction 2025.

Live Demo: [PASTE YOUR PUBLIC LINK HERE (e.g., from Netlify or Tiiny.host)]

(Replace the placeholder above by uploading a screenshot of your app to your GitHub repository and linking it here.)

Concept
To solve the frustrating problem of losing items on a busy campus, this prototype provides a simple, modern solution. It leverages the power of Large Language Models to analyze and compare text descriptions of lost and found items. By providing a "Match Score," it instantly helps users identify potential matches, saving time and effort.

Key Features
Clean & Simple UI: A user-friendly, responsive interface that is easy for anyone to use without instructions.

AI-Powered Matching: Integrates the Google Gemini API to perform sophisticated text analysis and comparison.

Dynamic Results: Fetches the AI's analysis in real-time and displays the result directly on the page without needing a refresh.

Self-Contained & Portable: The entire application runs from a single HTML file, requiring no installation or complex setup.

Tech Stack
Frontend: HTML5, Tailwind CSS, JavaScript (ES6+)

AI & API: Google Gemini API (v1)

How to Use
To run this project locally, follow these steps:

Clone the repository or download the index.html file.

Get a Google AI API Key: Create a free API key at Google AI Studio.

Update the API Key: Open the index.html file and replace the placeholder "YOUR_API_KEY" with your actual key inside the <script> tag.

Open in Browser: Simply open the index.html file in any modern web browser.

Development Journey & Learnings
This project was a great lesson in adaptability. The initial plan was to build the app with Python and Streamlit, but a critical environment issue related to API versioning blocked progress.

With the deadline approaching, I made a strategic pivot to a robust, dependency-free stack: HTML and JavaScript. This journey highlighted the importance of being flexible and choosing the right tool to overcome obstacles and successfully deliver a final product.
