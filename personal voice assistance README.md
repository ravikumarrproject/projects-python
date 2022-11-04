# projects-python
Python external Package Requirements:

-> gTTS – Google Text To Speech, for converting the given text to speech -> speech_recognition – for recognizing the voice command and converting to text -> selenium – for web based work from browser -> wolframalpha – for calculation given by user -> playsound – for playing the saved audio file. -> playaudio – for voice engine in python
We will divide each function as a single code for easy understanding. Here’s the main function, with get_audio() and assistant_speaks function. get_audio() function is created to get the audio from user using microphone, the phrase limit is set to 5 seconds (you can change it). Assistant speaks function is created to provide the output according to the processed data
The next step and the main step is how you want to process your input. This is just basic code, there is a lot of other algorithms(NLP) can be used to process the text in a proper manner. We have made it static. Also, Wolframalpha api has been used to calculate the calculations part.
There are two functions included that is search_web and open_application. search_web is just a web crawler which uses selenium package to process. It can search google, wikipedia and can open YouTube. You just have to say include the name and it will open it in the Firefox browser. For other browsers, you need to install a proper browser package in selenium. Here we are using webdriver for Firefox. open_application is just a function uses os package to open the application present in the system

Here are some of the examples and output, which can help you understand how the above processing works.

1. Say "Search google timer"
2. Say "Play Youtube your favourite song"
3. Say "Wikipedia Dhoni"
4. Say "Open Microsoft Word"
5. Say "Calculate anything you want"
