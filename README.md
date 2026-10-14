# Jukebot 🕺
This project builds a custom playlist generator website for our EECS 449 (Conversational AI) Final Project. The program asks the user for a prompt, utilizes Ollama AI to generate a playlist, stores the user's data in SQLite, and returns a playlist list and Spotify link to add playlist to spotify. The website allows for logins and remembers previous information using SQLite for future playlist recommendations.


**Instructions on how to build/run JukeBot**    
~ Make sure Ollama is installed (create virtual environment if you want, then run `pip install ollama` and `brew install ollama`)  
~ Start Ollama (`brew services start ollama`)  
~ Pull the model (`ollama pull llama3.2`)  
~ Make sure Flask is installed (`pip install Flask`)  
~ Run the Flask server (`python server/ollamaAPICall.py`)  
~ Navigate to http://localhost:8000/ in browser and you should see JukeBot  
