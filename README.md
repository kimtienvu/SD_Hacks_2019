# SD_Hacks_2019
Repository for SD Hacks Hackathon Project

Official DevPost Link: https://devpost.com/software/ucsd-real-time-lecture-transcriber

## Real-Time Lecture Transcriber
This program transcribes lectures in real-time, maximizing the learning experience for all students.

## Inspiration
Our inspiration was the UCSD lecture podcasts offered to students. We realized that there is no medium for those with hearing disabilities can use to access the podcasts. The lack of a medium inspired us to build this program for the benefits of all students.

## What it does
The program takes in audio input from the professor's microphone, transcribes it to text and automatically updates a html page for students to see on their electronic devices. The demo is a local version to visualize how the program will be used in a real lecture setup. The program runs a local audio transcriber, together with a local html page. When both programs are running, the html page will display the transcribed text in real time. The html page will be the medium for student interaction. The GUI for the local transcriber will also display the text in real time, allowing professors to see if the program is working.

## How we built it
We built the program using various open source codes, including Amazon Transcribe. We used Amazon open source code written in java to use Amazon transcribe and then we edited that code so that it could continuously write the transcription to a file. We then created an html page that would continuously read from the output file and display the text on the html page.

## Challenges we ran into
Our biggest challenge was to integrate the audio transcriber to an html page that would display the text real-time. We faced issues such as allowing the html page to update while the transcript was being updated. We also faced issues having the transcriber write to the file continuously. Initially, our program became very slow and was not a good representation of what we wanted to implement.

## Accomplishments that we're proud of
We are proud to have accomplished integrating multiple open sources, especially using the aws sdk. It was difficult and challenging to set up the environment under the time constraint, but we successfully managed to put together a working prototype.

## What we learned
We learned how to maximize open source for our project and collaborate with teammates of different disciplines. Composed with a cs major, cs major with a specialization with bioinformatics, and a math-cs major (ex-physics major), our group worked collaboratively to build our ideas into a working prototype.

## What's next?
Ideally, the final product will be on a web server for maximized user interaction and accessibility. We want to be able to allow multiple lectures to use the program. Additionally, we want the program to be interactive so students can add notes to the transcribe and ask questions.

## Built with
* html
* java
* javascript
* xml
