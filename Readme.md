Voice Assistant  

This is a Python-based voice assistant developed by Sujeet Vishwakarma. It can perform various tasks such as searching Wikipedia, opening websites, playing music, telling the time, and sending emails. The assistant listens to voice commands and executes actions accordingly.  

Developer  

Name: Sujeet Kumar  
Email: vishwakarma.sujeet1626@gmail.com   

Features  

- Greets the user based on the time of day  
- Recognizes voice commands using speech recognition  
- Searches Wikipedia for information  
- Opens websites like YouTube, Google, and Stack Overflow  
- Plays music from a specified directory  
- Tells the current time  
- Opens Visual Studio Code  
- Sends emails via Gmail  

Requirements  

Before running the program, install the necessary dependencies using:  

pip install pyaudio pyttsx3 speechRecognition wikipedia  

How to Use  

1. Run the script, and the assistant will greet you  
2. Speak commands like:  
   - open YouTube to open YouTube  
   - search Wikipedia for [topic] to get Wikipedia results  
   - play music to play music from a specified directory  
   - what's the time to get the current time  
   - email to Friend to send an email  
3. The assistant will process your voice and perform the action  

Customization  

- Change the voice in engine.setProperty('voice', voices[0].id)  
- Modify the music directory in music_dir = 'D:\\Music'  
- Update email credentials in the sendEmail function to use your own  

Known Issues  

- Background noise can affect voice recognition accuracy  
- Email functionality requires enabling Less Secure Apps in Gmail or using an app password  

Future Improvements  

- Add more commands for automation tasks  
- Improve error handling and response accuracy  
- Integrate AI models for smarter interactions  

License  

This project is licensed under the MIT License. See the LICENSE file for more details.  
