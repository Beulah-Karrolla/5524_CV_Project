# 5524_CV_Project

### Tracking Hand and Eye movements for enhancing AI agent activation

Proposal: The project aims to create a system that tracks hand and eye movements in real time to trigger camera enabled conversational agents. In order to identify these signals, such as waving hand movements and making direct eye contact with the AI agent, our project focuses on tracking hand gestures(wave in our case) and eye gaze patterns in real-time video feeds. These signals operate as prompts to the AI agent to wake up so it may interact with the human. We can precisely track hand movements and eye look directions in real-time by utilizing sophisticated computer vision techniques, such as motion history and motion time images. We plan to do eye and hand detection before proceeding to track their movement. In response to user inputs, we are  enabling the agent to react quickly to wake-up signals. Our project targets the use case where the video of human waving hand and looking at the screen is tracked to activate the system, for instance the the system responds with, "Hi, How can I help you?" once the wake signal is detected.

Methodology: 
* Part 1: Tracking eye movements, from detecting the presence of eyes in the image to tracking its direction of sight to determine the attention and intention of the eyes. (Object detection for eye, using template matching and motion detection using MEI and MHI)

* Part 2: Tracking Hand gestures, From detecting the presence of hand (palm facing camera) to tracking the gesture made by the hand(limiting the use case to ‘hi’ gesture) to determine the user engagement intention with the AI agent.(Object detection for hand/palm, using template matching or medial axis 3D shape skeleton and motion detection using similitude movements

* Integration: Aligning both movements to be in the same time frames for synchronization.

Data Processing:
* During development we plan to use pre-recorded video/image footage to detect the hand wave gesture and eye gaze. Dividing the video into frames and working frame by frame to gather required information.

Testing:
* We plan to use video footage fabricated for testing purposes of us interacting with the AI robot in a variety of contexts, including controlled conditions and real-world situations for testing, examples:
1. Hand waving, eye looking away

2. Hand waving, eye looking towards the agent

3. No hand waving, eye looking away

4. No hand waving, eye looking towards the agent

Results:  
* Initial result on Eye detetion can be found here  https://github.com/Beulah-Karrolla/5524_CV_Project/blob/b2842819e1439c207b2f5ff588fcd0ad7b6b2aab/cvproj_results.docx
