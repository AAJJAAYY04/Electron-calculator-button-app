# Electron-calculator-button-app
Follow all below steps for run this application.

1. You need VS code application on your PC.

2. create new folder in your workspace folder.<br>
    workspace--<br>
    --Electron-calculator-app <br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--indo.html<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--index.html<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--main.js<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--renderer.js<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--styles.css<br>
        
3. Open all above files in your VS code.

4. Before proceeding with Electron you need to install Node.js.
   To install nodejs run below procees
   Go to the site https://nodejs.org/en/download/ and download the necessary binary files. In our example, we are going to download the 32-bit setup files for Node.js and install it.

5. To check that Node.js was installed correctly, type the following commands in your terminal client:<br>
    node -v<br>
    npm -v<br>

   
6. we need electron framework for run above calculator application.<br>
   run below command in your terminal--><br>
   npm install --save-dev electron
   
7. run below command for your JSON file<br>
   npm init -y<br>
   and modify your JSON file to<br>
   {<br>
    "name": "my-electron-app",<br>
    "version": "0.1.0",<br>
    "author": "your name",<br>
    "description": "My Electron app",<br>
    "main": "main.js"<br>
}

8. By default, the npm start command will run the main script with Node.js. To run the script with Electron, you need to change it as such:<br>
    add "start": "electron ." in your script which is placed in your JSON file. You just need to add.
    
9. In terminal go to your project dir and run below command<br>
    npm start
   
