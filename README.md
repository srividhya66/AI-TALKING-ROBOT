🤖 AI Talking Robot — Your Voice-Controlled Smart Assistant

AI Talking Robot is not just a script — it's a fully interactive voice-controlled AI assistant that listens, understands, and acts on your commands like a real personal companion.
Built with Python + Speech Recognition + Google Gemini AI, it combines Natural Language Understanding, Text-to-Speech, System Automation, API Integrations, and even Webcam Control into one intelligent bot!

🧠 What Can It Do?
Category	Example Command	Action Performed
🌦 Weather	“What’s the weather in London?”	Fetches live weather report
🕒 Time/Timer	“Set a timer for 2 minutes”	Counts down & plays alarm
📸 Camera Control	“Take a picture”	Captures photo via webcam
📂 System Control	“Open Notepad / Close Chrome”	Launches or kills applications
💹 Stock Market	“How is Apple stock today?”	Gets live stock updates
😂 Fun Mode	“Tell me a joke”	Fetches real-time jokes
🔊 Chat Mode	“Who is Abdul Kalam?”	Responds with predefined or AI-generated answer
🔮 AI Reasoning	Any random question	Uses Gemini to infer intent & respond
💡 Why This Project Is Special

✔ 100% Voice-Operated — No Keyboard Required
✔ Understands Complex Human Language using Gemini AI
✔ Self-Decides Which Module to Use via JSON Logic
✔ Acts Like J.A.R.V.I.S (but Open Source 😎)
✔ Easy to Extend — Just Add More Modules!



Features

Voice Interaction

Recognizes user speech using speech_recognition.

Responds with natural speech via pyttsx3.

Multi-Module AI Assistant
The assistant can handle multiple tasks using a modular design:

Weather Updates: Get real-time weather information for any city.

Reminders & Timers: Set reminders or countdown timers.

Translation: Translate text between languages.

News Updates: Fetch news by category and region.

Jokes: Tell jokes based on category.

Currency Conversion: Convert currencies (API ready for implementation).

Stock Market Updates: Fetch latest stock prices.

Music Player: Play music via YouTube (future enhancement).

Navigation: Provide directions between locations.

Cooking Recipes: Suggest recipes based on dish or cuisine.

Health Advice & Fitness Tracking: Track activities and provide tips.

Device Control: Open/close applications like Calculator, Notepad, and Chrome.

Photography: Take pictures with webcam.

Time & Date: Get the current time.

Emergency Alerts & Trip Planning: Future enhancements planned.

Smart Responses & Custom Commands

Responds intelligently to predefined queries like:

“Who is Abdul Kalam?”

“What is Machine Learning?”

“Good afternoon”

“What is Cyber Security?”

Real-Time Timer Notifications

Timer functionality with audio alerts using pygame.

Webcam Capture

Take pictures with real-time webcam feed using OpenCV.

AI-Powered Text Understanding

Uses OpenAI Gemini-1.5 for natural language understanding and module classification.

Converts user speech into JSON instructions to determine the appropriate task/module.

Extensible & Modular

Easy to integrate new modules like quizzes, horoscopes, travel planning, or AI explanations.

Technologies Used

Python 3

speech_recognition: Speech-to-text processing

pyttsx3: Text-to-speech synthesis

pygame: Audio playback for notifications

OpenCV (cv2): Webcam integration for pictures

Requests: API requests for weather, stock updates, jokes, etc.

OpenAI Gemini API: Advanced AI understanding and JSON-based responses

Subprocess: Control local applications

How It Works

The robot greets the user.

User gives a voice command.

Speech is recognized and converted to text.

Text is processed by the Gemini model to determine the module and parameters.

Relevant API or local functionality executes the task.

Robot responds via voice and/or performs actions (e.g., opening apps, taking a picture).

Installation

Clone the repository:

git clone https://github.com/yourusername/ai-talking-robot.git
cd ai-talking-robot


Install dependencies:

pip install -r requirements.txt


Set your Gemini API key in the script:

genai.configure(api_key="YOUR_API_KEY_HERE")


Run the assistant:

python main.py

Usage

Speak commands naturally:

Example: “What is the weather in New York?”

Example: “Set a timer for 2 minutes.”

Example: “Open Notepad.”

Predefined queries are recognized and answered instantly.

For unsupported commands, the assistant uses AI to attempt a smart response.

Future Enhancements

Music playback from YouTube links.

Advanced travel planning and itinerary suggestions.

Integration with IoT devices for home automation.

Expanded health advice and fitness tracking.

Multi-language support.


License

MIT License
