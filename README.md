My first React program based on `create-react-app`.

I created it by running `create-react-app react-demo-2` and then tweaking things to work with VS Code.

After creating it, I ran `npm start`, which starts a web server on http://localhost:3000/

Then I started Visual Studio Code, and opened the react-demo-2 folder.

To get the debugging working, I clicked the "Add configuration" combo in the debug panel, and chose Chrome, and then replaced the resulting  `.vscode\launch.json` with the stuff from https://github.com/dominicprior/react-demo-2#debugging-in-the-editor

At that point, F5 works and launches a new Chrome.  To make it actually hit any breakpoints, I had to do a Restart Debugging (Ctrl-Shift-F5).
