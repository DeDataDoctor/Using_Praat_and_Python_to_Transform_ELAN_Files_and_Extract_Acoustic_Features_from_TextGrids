# Using_Praat_and_Python_scripts_for_Speech_Research
Praat is a program language often used in the speech/acoustics research community to extract complex acoustic features for (often) University Research. The challenge with PRAAT programming language is that it is very different from popular other languages and that proper examples are difficult to find online (it is an old language :-)). Therefore I descided to share some of the scripts I used during the earlier stages of my PhD to transform .Eaf files into .TextGrid files and extract acoustic features from all the .wav files in a directory based on annotations that we extracted. I used it for some work in the fields of Affective Computing and Social Signal Processing. I hope that other researchers can quickly adopt the code to their needs and use my scripts to get a basic understanding of how to do these tasks in PRAAT. 

## This directory contains two scripts for different steps I used to take:
1) Extracting all .eaf in a (sub)directory and converting them in .TextGrid files using Pympi in Python.
2) Loop through all .TextGrid files and .Wav files and extract all relevant information using Praat.

## Contact
If you need more help or have questions, please contact me on michel[dot]jansen[at]live[dot]nl.