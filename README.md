## Description
VoiceHCI-Toolkit is a self-contained system for conducting a voice-driven human–computer interaction experiment in which participants place shapes on a grid following spoken instructions. The toolkit includes a Windows executable (`HCI-Testing.exe`), all necessary audio clips and UI assets, and configuration files. A proctor uses the same application to control playback of voice instructions, monitor participant progress, and record data.





## Prerequisites
- **Operating System**: Windows 10 or later (required to run `HCI-Testing.exe`).  
- **Memory**: Minimum 8 GB RAM recommended.  
- **Audio**:  
  - Headphones or speakers (for participant audio playback).  
  - (Optional) Microphone if recording ambient or participant commentary.  
- **Screen Recording Software**: Capable of capturing both system audio and on-screen video.  
- **Access Codes**:  
  - A **proctor code** and a **participant code**, provided by your project lead.

## Installation
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/AJDevCode/VoiceHCI-Toolkit.git

## Features

- **Single Executable**: Both proctor and participant run the same HCI-Testing.exe.
- **Audio Clip Navigation**:

        Play, stop, restart, and tutorial controls.

        Keyboard shortcuts (Spacebar for play/stop).
- **Two-Code Login**: Secure pairing via a proctor code and participant code.
- **Grid-Based UI**: Participants arrange shapes on a grid while following voice instructions.
- **Configurable Assets**: All voice clips, grid images, and settings are stored in assets/.

### User View 
![image](https://github.com/user-attachments/assets/e2aa75f2-c72c-4484-ae9f-d2c7dc4a17d2)
### Proctor View 
![image](https://github.com/user-attachments/assets/7c6efb37-5233-445a-a677-4473a122f29c)

## Technologies Used
- Windows Executable (HCI-Testing.exe)
- Audio Files: WAV/MP3 format voice instructions.
- Static Assets: Grid images (PNG/JPG), configuration JSON/text files.
- Version Control: Git/GitHub for repository hosting.
- Screen Recording Tools: Any application that captures on-screen video and system audio (e.g., OBS Studio, Camtasia).
- Unity for development

## Troubleshooting

- Login Bug
  - Always sign in as proctor first, then participant. Failing to do so may cause a login error that prevents the experiment from starting.
- Audio Playback Issues

        If the voice clips fail to play or you hear stuttering:

            Click “Restart” to play clip0 instead of “Play.”

            Verify that the participant’s PC audio output is not muted and is routed through speakers or headphones.

            Ensure no other application is exclusively occupying the audio device.
