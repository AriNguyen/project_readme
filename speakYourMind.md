# Speak Your Mind - Help paraplegia to communicate with other people and interact with other people in their daily life

## Inspiration
Due to some disease that leads to paralysis, some people experience difficulty in interacting with other people in their daily life. Inspired to help these people make a normal conversation,  we came up with an idea to create an app to help severely paralytic people to speak out loud their thoughts by using their eyes and head movement. 

## What it does
By gazing their eyes right, left and center, blinking, winking, and move their head slightly, the user can drag and click the mouse cursor. The GUI comprises an onscreen keyboard to construct sentences and a list of suggested sentences to quickly generate simple conversation. This app is an inexpensive alternative for dedicated speech devices that are available on the market right now.

## How we built it
We use Python packages OpenCv, Dlib, and trained model of facial features to track the shape and position of eye pupils to analyze if the eyes are gazing to the left, right, center, blinking, or winking to drag and click mouse cursor.

Tkinter and Pygame python packages are used to create the GUI. We also use Google Cloud Text to Speech Client Libraries to generate speech after the user completes making a sentence using the onscreen keyboard or after clicking on the suggested sentences. 

## Challenges we ran into
There is some extent of delay in mouse cursor movement when using eye-tracking. Therefore, we adding head pose estimation algorithm to accelerate the process of converting facial movement to computer commands. 

## Accomplishments that we're proud of
We did not come with an idea or any plan but luckily we went through the daunting challenge of brainstorming and came up with an application that solves a very important problem that people with severe paralysis are facing every day: communication.

## What we learned
This was a very first hackathon to some of our members. We hadn't known much about eye-tracking, head pose estimation, or google cloud text to speech libraries before this hackathon. It was definitely a great opportunity to broaden our horizons, cultivate new skills, and improve public speaking skills. 

## What's next for Speech and Communication Support for Disabled Patients
We're planning to create a more user-friendly GUI for the paralyzed patients that gives them the non-lagging experiences.