
# LUMI: Lifestyle Utility and Monitoring Interface

## Introduction
LUMI is a multifunctional desktop assistant robot designed to perform various tasks and interact with users in an engaging way. It responds to voice commands, displays emotions on a screen, controls devices using IR signals, and provides task management features such as setting reminders, alarms, and timers.

## Objective
- Develop an affordable, multifunctional desktop robot.
- Reduce distractions and improve productivity.
- Engage users through expressive emotion display.

## Problem Statement
To create an affordable, emotionally expressive desktop companion robot that offers personal assistance, smart home control, and task management using Raspberry Pi 5.

## Features
- Voice command recognition and response.
- Emotion display on a 2-inch LCD screen.
- IR signal capture and device control.
- Task management: reminders, alarms, timers.
- Integration with IoT devices for home automation.
- Offline operation to reduce cloud dependency.

## Hardware Components
- Raspberry Pi 5
- 2 Inch LCD Display (240×320 px)
- IR Blaster/Receiver (HW-201)
- 0.5W Speaker
- 9g Mini/Micro Servo Motor (Tower Pro SG90 Servo)
- Servo Motor Driver I2C (PCA9685 12-Bit PWM)
- Capacitive Touch Sensor (TTP223)
- Vibration Shock Sensor

## Software Methodology
- Voice input acquisition via microphone and PyAudio.
- Audio preprocessing using pydub.
- Speech-to-text conversion using OpenAI’s Whisper model.
- Command parsing and intent classification.
- Task management and response handling using SpaCy for text-to-speech.
- Emotion interpolation for smooth transitions on display.

## Results
- Successfully implemented user interface with emotional engagement.
- Integrated motion detection and real-time notifications via Mi Home Security Camera 360.
- Captured and replayed IR signals for remote device control.
- Seamless integration of IoT functionalities and task management on Raspberry Pi 5.
- Robot effectively understands and responds to voice commands.
- Emotion display enhances user interaction.
- Supports home automation and improves accessibility.

## Conclusion
LUMI is an affordable, emotionally expressive desktop companion robot that combines voice recognition, smart home control, and emotion display to provide a personalized and engaging user experience. It enhances daily interactions, improves accessibility through intuitive voice commands, supports IoT integration, and operates efficiently offline.

## Guided By
Dr. Sonal Ayyappan  
Associate Professor & HOD, Department of Artificial Intelligence & Data Science

## References
1. Iván Froiz-Míguez et al., "Design, Implementation, and Practical Evaluation of a Voice Recognition Based IoT Home Automation System for Low-Resource Languages and Resource-Constrained Edge IoT Devices," IEEE Access, 2023.  
2. Mahmoud Abbasi et al., "Security in the Internet of Things Application Layer: Requirements, Threats, and Solutions," IEEE Access, 2022.  
3. Jiaxiong Hu et al., "The Acoustically Emotion-Aware Conversational Agent with Speech Emotion Recognition and Empathetic Responses," IEEE Transactions on Affective Computing, 2022.  
4. Zeeshan Shaikh et al., "An implementation on-surveillance robot using Raspberry-Pi technology," International Research Journal of Engineering and Technology, 2017.
