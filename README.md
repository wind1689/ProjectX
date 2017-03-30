# How to run Webgl:
## Step 1 Enable Webgl on Chrome Browser
- Go to "chrome://settings"
- Click the "+ Show advanced settings" button
- In the "System" section, ensure the "Use hardware acceleration when available" checkbox is checked (you'll need to relaunch Chrome for any changes to take effect)
- Go to "chrome://flags"
- Ensure that "Disable WebGL" is not activated (you'll need to relaunch Chrome for any changes to take effect)
- Go to "chrome://gpu"
- Inspect the WebGL item in the Graphics Feature Status list. The status should be "Hardware accelerated".
- Open "https://get.webgl.org/". If you can see a spinning cube, then your browser support webgl right now.

## Step 2 Start a local server
- Make sure your computer has properly install pyton. If not, please install one.
- Open terminal and go to the folder of webgl project.
- Run "python -m http.server".

## Step 3 Browse the webgl on Chrome
- Open Chrome Browser and browse "localhost:8000".
- Click "Code" folder.
- Click the html file if needed.
