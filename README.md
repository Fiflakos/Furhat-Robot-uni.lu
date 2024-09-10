#Hello
![Watch the video](Furhat-Robot-uni.lu/Demo_3.0.1.mp4)
# SkillWizard Documentation

## Introduction

Welcome to SkillWizard! SkillWizard is a powerful tool designed to augment your project using the Furhat SDK. This documentation provides a comprehensive guide on installing the Furhat SDK and executing the SkillWizard program to interact with our virtual Furhat interface.

## Installation

### Furhat SDK

Before diving into SkillWizard, ensure the Furhat SDK is correctly set up on your system. Follow these steps:

1. **Download Furhat SDK:**
   - Visit the [Furhat SDK Download Page](https://docs.furhat.io/launcher/) to download the latest version.

2. **Installation:**
   - Follow the installation instructions provided for your operating system.

### SkillWizard

Now that you have the Furhat SDK installed, proceed with SkillWizard installation:

1. **Download SkillWizard:**
   - [SkillWizard-0.143.1.skill](https://www.mediafire.com/file/5tf19etha9bq1wz/SkillWizard-0.143.1.skill/file)

2. **Placement:**
   - Place the SkillWizard-0.143.1.skill file in the appropriate directory.

## Executing SkillWizard

### SDK Access

1. **Open FurhatSDK:**
   - Launch FurhatSDK.

2. **Start Skill:**
   - Navigate to the "Start Skill" button.

3. **Select SkillWizard:**
   - Choose the file SkillWizard-0.143.1.skill.

4. **Open Web Interface:**
   - After execution, navigate to the "Open Web interface" button.

5. **Access Interface:**
   - To fully access it, use the password: "admin" (when using localhost).

### Command Prompt Access

#### Opening the Web Interface

1. **Open Terminal or Command Prompt:**
   - Navigate to the directory containing SkillWizard-0.143.1.skill.

2. **Run the Command:**
   ```bash
   furhat -t SkillWizard-0.143.1.skill

   ## Initialization

- Wait for SkillWizard to initialize.

## Access in Browser

- Open a web browser and go to [http://localhost:8080](http://localhost:8080).

## Console Commands

While SkillWizard is running, interact with it using the console:

- `help`: Display a list of available commands.
- `start`: Start the SkillWizard program.
- `stop`: Stop the SkillWizard program.
- `exit`: Exit the console and stop SkillWizard.

## Troubleshooting

If you encounter issues during installation or execution:

- Ensure the correct Furhat SDK version is installed.
- Double-check SkillWizard-0.143.1.skill for errors or corruption.
- Check the console for error messages and consult the [Furhat SDK documentation](https://docs.furhat.io/furhatos).

# Connecting to the Furhat Robot-Phisycal

After continuing the Quickstart guide:

## Step 1: Powering On and Accessing the Hotspot


1. **Open the Hotspot**:
    - Press the **Hotspot button** on the robot to enable its WiFi hotspot.

2. **Connect to the Robot's WiFi**:
    - On your computer, search for the robot’s WiFi network. The network name should be displayed on the robot's screen.
    - Connect to the robot's WiFi.

## Step 2: Accessing the Robot via Web Interface

1. **Open Your Web Browser**:
    - Once connected to the robot's WiFi, open any web browser.

2. **Enter the IP Address**:
    - Type the IP address displayed on the robot’s screen into your browser’s search bar (e.g., `192.168.x.x`).

3. **Enter Password**:
    - On the login page, enter the password: `"admin"` (for localhost or default access).

## Step 3: Uploading the Skill File

1. **Navigate to the Skills Section**:
    - On the left sidebar of the web interface, click on the **Skills** section.

2. **Upload the Skill File**:
    - In the Skills section, you can easily upload a new skill.
    - Select the latest `.skill` file you have (e.g., `Parsa_V3.0.skill`) from your local directory.
    - You can not run the skill form IDE so convert your code to .skill.
3. **Execute the Skill**:
    - Once uploaded, you can start the skill directly from the web interface.

## Optional Experience: Using LAN Cable for Easier WiFi Setup

**My Experience**: I recommend first connecting the Furhat robot to the internet using a LAN cable. This way, you can configure the robot’s WiFi settings from the dashboard without the potential issues that can occur when entering symbols in WiFi passwords on the robot. 

## Step-by-Step for LAN Connection:

1. **Connect LAN Cable**:
    - Plug a LAN cable directly into the robot and ensure it is connected to the internet.

2. **Set Up Hotspot**:
    - Now, open the hotspot of the robot as described earlier.

3. **Configure WiFi from Dashboard**:
    - In the dashboard's network settings, you can connect the robot to your desired WiFi network.
    - Make sure to type in the correct WiFi password and verify all symbols, as WiFi connection on the robot can sometimes be finicky with special characters.

By following this process, you should have a smooth experience connecting the robot to your network and uploading your latest skill file for testing.


# Feedback and Support

For questions, suggestions, or issues, contact: [ysak.filip.001@student.uni.lu](mailto:ysak.filip.001@student.uni.lu), [Parsa.vares.001@student.uni.lu](parsa.vares.001@student.uni.lu)



