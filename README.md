# IoT Computer Vision Networking App
---

## What
- A webcam that streams a live feed and can send the user a notification if it detects motion or people.

## Why
- Home security remains an important issue. Recently, for example, there have been several cases of thieves stealing packages from people’s porches and front doors. A security camera can help to keep a log of who enters or approaches a home.

## How
- A development board such as a Raspberry Pi/Pi Zero W can be used as a server which streams a live feed and sends notifications to a client.

## Deliverables
1. Network App (IoT Computer Vision)
2. Documentation


## Team Members
- Arianna Burch

- An Huynh

- Sofia Lee

- Tin Wong



## Set Up
1. Check Python requirements
2. Download: https://drive.google.com/file/d/18bWyl_SieLtARy1tdjTIX25OAMIAVXHK/view?usp=sharing and place in `ProcessingServer/datasets` subfolder
3. On command prompt/terminal, cd into `ProcessingServer/src` subfolder for `ProcessingServer.py`
4. On second command prompt/terminal, cd into `CameraServer` subfolder for  `WebSocketServer.py`
5. Download `Brackets` application and open `Web` subfolder in application
6. On third command prompt/terminal, cd into `ProcessingServer/src` subfolder for `ProcessingServer.py` 

## To Run
1. Run `ProcessingServer.py`
2. Run `WebSocketServer.py`
3. Run `objectDetectiontest.py` to jumpstart python3 app (you won't need it after that)
4. Go to brackets open index.html from left sidebar. Click lightening icon on right side.
