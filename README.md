Webpage uses PC mic to compute microphone energy.

How it works:

    Microphone Capture: It uses navigator.mediaDevices.getUserMedia to request access to the microphone.
    Web Audio API: An AudioContext and AnalyserNode process the audio data.
    Energy Calculation: It calculates the root-mean-square (RMS) energy level of the audio in real-time.
    UI Update: The computed energy is displayed on the webpage and updated continuously.

Customization Suggestions:

    Increase fftSize for finer analysis.
    Display a graphical meter (e.g., a bar or circle) instead of a number.
    Add a stop button to disconnect the microphone.
