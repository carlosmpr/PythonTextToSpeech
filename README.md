# Text to Speech

Python program that transform text into an audio file, using Google Text to Speech API know as gTTS

## Install
Install the gTTS

        pip install gTTS
## Run the code:

1. Import the gtts:

        from gtts import gTTS
        
2. Run the code:

         mytext = 'The text to speech'
         language = 'en'
         audio = gTTS(text=mytext, lang=language, slow=False)
         audio.save("fileName.mp3")
         