# Shipping Ships API

## Debug Configuration

1. Clone this project and open the directory in Visual Studio Code.
2. Go to the debug panel.
3. In the select menu at the top, open the menu and choose the **Add configuration...** option.
4. VS Code will immediately make a `launch.json` file and open it in the editor.
5. Delete everything in the file.
6. Replace it with the contents below and save the file.
   ```json
   {
       // Use IntelliSense to learn about possible attributes.
       // Hover to view descriptions of existing attributes.
       // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
       "version": "0.2.0",
       "configurations": [
           {
               "name": "JSON Server",
               "type": "python",
               "request": "launch",
               "program": "json-server.py",
               "justMyCode": true,
               "console": "integratedTerminal"
           }
       ]
   }
   ```
7. Close the file.