
**Smart Glasses for PWD (people with disabilities) Face Contact

This project presents an assistive smart glasses system designed to help individuals with Alzheimer’s, cognitive impairments, and visual disabilities recognize people in real time.

👓 What It Does

Face Identification: Uses smart glasses to recognize faces from a known contact list. 

Phone Integration: When a known face is detected, the person’s name is displayed on the user’s connected smartphone.

Self-Updating System: If the face is unknown, the system:

Captures the image

Augments it for training

Retrains the face recognition model using one-shot learning

Adds the new person to the user’s contact list

**Who It’s For**

Individuals with Alzheimer’s or dementia

People with visual impairments

Anyone experiencing memory or recognition difficulties

**Purpose**

The system aims to improve independence and social confidence by passively assisting users in recognizing people around them — without the need for manual input or prior memory recall.





**Instructions**

R7sound.py: This python file utilized face_recognition library and can be run on the RaspberryPi. Future purposes the API url and Firebase Configs can be changed.

**One-Shot Learning Models**


Models aren't configured for Smart Glasses but can be for future works.

Siamese Nueral Netork:  Trained and Tested NNs on one-shot learning to see if can be used in glasses. Code is .ipynb large and not viewable on github but can be downloaded.

TrasnferLearning using VGG-16:  Model is trained and tested directories of training and testing can be placed to re-train and test. Augmentation file should be used to get better accuracy for one-shot Learning.





**Smart Glasses Application:**
https://github.com/VladPavlovich/SmartGlassesApp

Application built React Native using Expo
Expo Doc to Run App: https://docs.expo.dev/bare/overview/

App:
https://github.com/VladPavlovich/SmartGlassesApp
-API branch is most updated

**FastAPI for AWS (communication between the App and RaspberryPI):**

FastAPI
https://github.com/VladPavlovich/FastAPI



![Frame 15 (1)](https://github.com/user-attachments/assets/70a5dc50-d265-4f3c-b908-260201cc6e08)


## License

Copyright (c) 2025 Vlad Pavlovich. All rights reserved.

This source code is proprietary and confidential.

You are not permitted to:
- Use
- Copy
- Modify
- Distribute
- Compile
- Decompile
- Run
- Mirror
- Reproduce

any part of this code or its contents in any form without explicit written permission from the author.

Any unauthorized use of this code is strictly prohibited and may result in legal consequences.
