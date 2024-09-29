Fiverr Auto-Reload Bot
Overview: The Fiverr Auto-Reload Bot is a custom tool designed to automate the reloading of a specific Fiverr page in a pop-up window at randomized intervals. Whether you're a freelancer managing gigs, reviewing offers, or tracking analytics, this bot ensures you can keep an eye on the page without manual refreshes. It operates seamlessly in the background while you work on other tasks, providing both convenience and efficiency.

Key Features:

Automatic Page Reloads: The bot reloads your chosen Fiverr page (e.g., gig management, analytics) at predefined intervals without manual intervention.
Randomized Intervals: You can set custom intervals for reloads, ranging from a few minutes to longer durations, ensuring your page stays updated without predictable patterns.
Always Visible: The page opens in a small popup window that remains visible in the foreground, allowing you to monitor it without switching tabs or disrupting your workflow.
Customizable Popup: Adjust the size and position of the popup window to fit your screen, ensuring it doesn’t interfere with your main tasks.
Start/Stop Functionality: You can easily start and pause the bot, giving you complete control over when the Fiverr page reloads.
Real-Time Countdown: The bot displays a countdown to the next reload, so you always know when the next update will happen.
Who It's For:

Fiverr freelancers and sellers who want to monitor their gig page, offers, or analytics without constantly refreshing the page manually.
Professionals looking for a streamlined solution to keep Fiverr activities visible while focusing on other tasks.
This tool is perfect for anyone who needs to maintain visibility on their Fiverr activity without wasting time on manual reloads.
To run the Fiverr Auto-Reload Bot, follow these steps:

Steps to Run the Fiverr Auto-Reload Bot:
Download the HTML File:

Copy the HTML code provided above (or the version you are using).
Paste it into a new .html file using any text editor (e.g., Notepad, VS Code, Sublime Text).
Save the file with a name like fiverr_auto_reload.html.
Modify the Target URL:

In the script, replace the targetLink variable's value with the Fiverr URL you want to monitor (e.g., your gig management page).
javascript
Copy code
const targetLink = "https://www.fiverr.com/users/yourusername/manage_gigs";
Open the HTML File in a Browser:

Double-click the saved .html file to open it in any modern web browser (Chrome, Firefox, etc.).
Run the Bot:

You'll see a user interface with "Start" and "Pause" buttons.
Click the Start button to initiate the automatic reloading process.
A popup window with your Fiverr page will open and refresh at the specified intervals.
Monitor the Reload Process:

The popup window will refresh automatically at the defined intervals.
The countdown timer and interval will be shown in the main window to let you track when the next reload will happen.
If needed, resize and move the popup window to a convenient spot on your screen.
Pause or Stop:

You can pause the process at any time by clicking the Pause button.
To stop completely, close both the main and popup windows.
Requirements:
Browser: Make sure you are using a modern browser like Chrome, Firefox, or Edge to run the bot smoothly.
Popups: Ensure your browser allows popups for the page you're working with.
Tip: If the popup window doesn't open, check the popup settings in your browser and allow popups for local files or the Fiverr domain.
Adjustments:
Customize Intervals: You can modify the intervals array in the code to adjust the random reload times (in minutes).
javascript
Copy code
const intervals = [1, 3, 5, 7, 2, 3, 4, 1, 6, 4]; // Custom intervals in minutes
Once set up, the Fiverr Auto-Reload Bot will run in the background, periodically reloading your Fiverr page without disturbing your work on other tabs.
