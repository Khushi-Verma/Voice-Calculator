# A Smart Calculator
A smart calculator that accepts voice input.
# Step for speech recognition
- For recording, use The SpeechRecognition interface of the Web Speech API.
#  To manipulate the voice input
- Set the voice input to the output section of the calcultor & after 2s the output section will be overridden by the result.
- Call the evaluate() after 2s using setInterval method in Javascript.
- Now,if it works, it will print d result. if it doesn't, it comes to catch block where the output is set to empty & the exception is printed into d console
