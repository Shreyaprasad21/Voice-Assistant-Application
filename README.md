# Voice Assistant Application            
        
This is a Python-based voice assistant application that can perform a variety of tasks, such as searching Wikipedia, opening websites, and providing the current time. The app utilizes several libraries to achieve these functionalities, including `pyttsx3` for text-to-speech, `speech_recognition` for converting speech to text, and `wikipedia` for fetching data from Wikipedia.

## Features        
  
- Greets the user based on the time of day                                               
- Converts speech to text and executes commands                                                      
- Searches Wikipedia and reads a summary        
- Opens popular websites like Instagram, YouTube, Google, Kaggle, and more
- Provides the current time
- Opens Anaconda Navigator                     

## Libraries Used

- `pyttsx3`: Text to speech conversion
- `datetime`: To get the current time
- `speech_recognition`: To recognize and convert speech to text
- `wikipedia`: To fetch summaries from Wikipedia
- `os`: To open local files    
- `webbrowser`: To open websites

## Installation

1. **Clone the repository**:
   ```bash
   https://github.com/Shreyaprasad21/Voice-Assistant-Application.git

 2. **Install the required libraries**:
     ```bash
    pip install pyttsx3
    pip install SpeechRecognition
    pip install wikipedia

 3. **Ensure you have the following additional dependencies**:
     ```bash
     pip install pyaudio

## Usage

1. **Run the application**:
   ```bash
    voicee.ipynb

 2. **Interact with the assistant**:

  - Upon starting, the assistant will greet you based on the time of day.
  - You can give voice commands such as:
    ```bash
    Search Wikipedia
    Open YouTube
    What is the Time
    Open Anaconda
  - The assistant will respond to your commands by performing the requested actions.

## Contributing
- Fork the repository.
- Create your feature branch (git checkout -b feature/fooBar).
- Commit your changes (git commit -am 'Add some fooBar').
- Push to the branch (git push origin feature/fooBar).
- Create a new Pull Request.
