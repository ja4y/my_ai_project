# my_ai_project
"MoodTunes"

building Ai course project

## Summary  
MoodTunes is an AI-based music player that suggests songs based on your facial expression and mood.  
It helps you discover the right music at the right moment.  

![image of a headphone](/headphone-ai.jpg)


## Idea in a nutshell  
MoodTunes is a smart music player that uses your webcam to detect your mood (like happy, sad, focused) and recommends songs that match your emotion. It uses facial recognition and AI to understand your current feeling and suggest personalized music.

## Background  
Many people use music to support their emotions – to relax, to focus, or to feel better. However, choosing the right music for your mood takes time and effort.  
MoodTunes solves this by making music choice automatic, fast, and more emotional.  

This idea is personal to me because I often study or work listening music, and I’ve noticed how my mood changes depending on the song. I wanted to create a tool that understands me better and offers support without asking.

![image of a cat](/smiley-ai.jpg)

## Data and AI techniques  
MoodTunes uses facial emotion detection as its main AI feature. It could use open-source emotion detection libraries like DeepFace.
The AI model detects emotions such as joy, sadness, anger, surprise, and neutral. Based on this, it matches the mood with music categories.  

Music data (songs and mood tags) can be taken from free APIs such as Spotify (with mood metadata) or pre-created playlists.


## How is it used  
The user opens MoodTunes in a browser or app. The camera reads their face (with permission), analyzes the mood in real-time, and starts playing music that matches the emotion.  

Users can skip songs, give feedback, or let it play automatically. The tool can help students, workers, or anyone who wants to connect music to their emotional state.


## Challenges  
Mood detection is not always accurate, especially if the face is not fully visible or if the person is masking emotions.  
Privacy concerns must be taken seriously – camera access and emotional data must be handled securely and with user consent.  
Also, music taste is personal, so AI suggestions won’t always be perfect.


## What next  
MoodTunes could improve by learning user preferences over time and using voice input or typing mood instead of face detection. It could connect with other platforms like Spotify or YouTube Music.  

## Acknowledgments  
Inspired by Spotify mood playlists.
If I build a demo, I will use open-source libraries like DeepFace and free image datasets for emotion detection.





