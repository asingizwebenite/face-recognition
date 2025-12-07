 # face-recognition


A simple face recognition system that:

Captures your face photos using a camera

Trains a recognition model with those photos

Recognizes you in real-time through the camera

📁 Files Included
capture.py - Takes photos of people for training

train.py - Creates the recognition model from photos

predict.py - Live face recognition

🚀 Quick Start
1. First, install required packages:
text
opencv-python mediapipe numpy
2. Take photos for training:
Run:

text
python capture.py
Press ENTER when ready

It will take 200 photos per person

Press 'q' to stop early

3. Train the model:
text
python train.py
This reads all collected photos

Creates the recognition model

Saves files in models/ folder

4. Run recognition:
text
python predict.py
Looks at camera feed

Shows your name when recognized

Press 'q' to quit

🎯 How It Works
Collection: Takes face photos and saves them in dataset/ folder

Training: Learns to recognize faces from those photos

Recognition: Compares live camera feed to trained faces

⚠️ Notes
Ensure good lighting

Face the camera directly

Works best with consistent background

For 2 people by default (edit persons list to add more)

