# Automate-Discord-Messages
Welcome, everyone! In this video, I'll guide you through the process of automating your messages on Discord. Automating messages can save you time and increase your productivity, whether you're into trading on DeBok or need automation for any other Discord-related tasks.

## Why Automate?

Automating messages not only frees up your time but also enhances your ability to receive more offers efficiently. This tool isn't limited to DeBok trading; you can adapt it for various Discord tasks. Today, I'll show you how to set it up step by step.

### Prerequisites

Before we begin, make sure to download the following:

1. [Python](https://www.python.org/downloads/) - Make sure to check "Add Python 3.9 to PATH" during installation.
2. [Notepad++](https://notepad-plus-plus.org/downloads/) or [Microsoft Visual Studio](https://visualstudio.microsoft.com/downloads/) - For this tutorial, I'll use Visual Studio, but Notepad++ is recommended.

### Getting Started

1. **Install Python:**
   - Follow the link provided to download Python.
   - During installation, check the option to add Python to the PATH.
   - Once installed, you won't need to interact with Python directly.

2. **Download the Automation Script:**
   - Click on the provided link to access the script code.
   - Download the zip file and extract it to a location you can easily find, like your desktop.

3. **Configure Script:**
   - Open the extracted folder and locate the 'Main' file.
   - If using Visual Studio, it will open automatically. For Notepad++, open it there.
   - Fill in the required fields:
      - `authorization`: Your Discord account token (find it by searching online).
      - `url`: Copy the Discord Channel URL from the channel you want to use.
      - `channelID`: Copy the Channel ID (enable developer mode in Discord to find this).

   - For the `content` section, copy your message but format it using Python triple-single-quotes. Remove unnecessary characters at the beginning and end.

   - Save your changes.

4. **Adjust Timing:**
   - In the script, locate the line `sleep 3600`. Change it to `sleep 120` to send messages every 2 minutes.

### Running the Script

1. Open a command prompt in the folder where your script is located.
2. Type `py main.py` and press Enter.

If everything is set up correctly, you should see a message in Spanish confirming that the message was sent. Your messages will now be sent automatically at the specified interval.

**Note:** Ensure that your last line in the script says `sleep 120` for smooth functioning.

That's it! You've successfully set up an automated Discord messaging system. Feel free to customize it for different servers and tasks. If you found this tutorial helpful, drop a like, subscribe, and don't forget to enter the giveaway mentioned in the video for a chance to win. Stay tuned for more exciting content and giveaways! Peace out!

# Video Tutorials:
1. [HOW TO AUTOMATE YOUR DISCORD MESSAGE](https://youtu.be/QWy3KxL1CDI?si=yjsNNTQa7Xn9z8rv)
2. [How to Find Your Discord Token](https://youtu.be/YEgFvgg7ZPI?si=Wglf-B_IBjeTNMYv)
