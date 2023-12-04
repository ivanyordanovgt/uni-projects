# How to use
To open, go to ```/templates``` and open ```board.html``` as a server.

board.html should be opened as a server! Not as a file!
If you want to open it as a file go to ```board.html``` and edit line 71 by commenting it

To comment add ```//``` before the line

# Open with Visual Studio Code
Open Visual Studio Code and go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window. Search for "Live Server" and install the one provided by Ritwick Dey.

Right-click on the HTML file in the editor:

From the context menu, select "Open with Live Server."

# Using Node.js (with http-server package):
1. Install http-server globally (if you haven't already):

    ```npm install -g http-server```

2. Navigate to the directory containing your HTML file using the terminal:

    ``` cd /path/to/your/html/file ```

3. Run http-server:

    ``` http-server ```

This will start a server on port 8080 by default.

4. Open your browser and go to http://localhost:8080/ or the port shown in the terminal. You should see your HTML file.

# Using Python

1. Navigate to the directory containing your HTML file using the terminal:

``` cd /path/to/your/html/file ```

Run a simple Python HTTP server:
For Python 2:

``` python -m SimpleHTTPServer ```

For Python 3:
``` python -m http.server ```

This will start a server on port 8000 by default.

3. Open your browser and go to http://localhost:8000/ or the port shown in the terminal. You should see your HTML file.