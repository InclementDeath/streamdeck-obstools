# streamdeck-obstools
 Advanced OBS commands and tools to use on your Elgato Stream Deck

## Features:
- Instant Replay Action - Click to save the last seconds of your stream to your OBS "Recordings" folder.
  - Long-Press the button to toggle whether the Instant Replay buffer is recording or not
- Dropped Frames Alarm - Shows the current amount of dropped frames and starts alerting if it increases.
  - Choose between 3 different dropped frame types: Dropped Frames, Output Skipped Frames, Render Missed Frames
  - You can now customize the color of the alert
- OBS CPU Usage - Shows how much CPU is being utilized by OBS
- Previous Scene Action - Allows you to switch back to your previously used scene. Writes the name of the scene on the key.

# INSTALLATION
**Important:** You must download and install obs-websocket before using this plugin. Install from here: https://github.com/Palakis/obs-websocket/releases/download/4.6.1/obs-websocket-4.6.1-Windows-Installer.exe

2. After installing, enable from inside OBS: Tools -> WebSockets Server Setting 
[You can keep the port as is, but It is ***highly recommended you Enable authentication and set a password***]

3. For instant replay to work, you must check the **Enabled Replay Buffer** from File->Settings->Output->Recording

## Usage
OBS must be streaming for the majority of the features to work
For instant replay to work, you must check the **Enabled Replay Buffer** from File->Settings->Output->Recording
