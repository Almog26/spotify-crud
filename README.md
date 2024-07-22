Howto Setup & Run this Project

Install NodeJs ( Ignore If Already Installed)
 1. Visit the official Node.js website i.e) https://nodejs.org/en/download/
 2. Download the Node.js installer
 3. Run the installer.
 4. Follow the prompts in the installer.
 —First Run Backend then Frontend & Admin—
 ❖ StepsToSetup Backend Of The Project
 1. OpenProject Folder In VS Code
 2. OpenIntegrated Terminal
Right Click on ‘spotify-backend’ > Select “Open In Integrated Terminal”
 3. Type “npm install” and press Enter and Wait for Installation to be completed
 (requires Internet)
 4.
 5. Setup Cloudinary for file storage.
 Create account and login to: https://cloudinary.com/
The go to Dashboard
 Copy and paste the Cloud Name, API Key, And Secret Key in the .env file:
 6. Setup The MongoDB
 a. Open this link- LINK
 b. After that Sign Up on the website.
 c. Click on New Project Option
d. After Creating Project go to Database Section & Build a database
 e. Select M0 & Your Region & Create Database
 f. Setup Username & Password & Create User
Note: Do not use ‘@’ symbol in the password
 g. NowClick on Finish & Close
 h. Whitelist IP 0.0.0.0 & Click on Add Entry
 i.
 Now Click on Connect
j.
 Now Select Compass Option
 k. And Copy the Connection String
 l.
 And Paste It in .env file and replace the password with the password
 you set previously in 4.F & save changes.
 7. To Run Backend use npm run server in Integrated Terminal
❖ StepsToRunFrontend of The Project
 1. Right Click on ‘spotify-clone’ > Select “Open In Integrated Terminal”
 2. Type “npm install” and press Enter and Wait for Installation to be completed
 (requires Internet)
 3. After Installation You will See ‘node_modules’ Folder in the Sidebar
 4. After that type “npm run dev” in terminal
 5. Nowyou will see the ‘localhost’ link in that terminal. Open that link in the
 browser.
 ❖ StepsToRunAdminPanel of The Project
 1. Right Click on ‘spotify-admin’ > Select “Open In Integrated Terminal”
 2. Type “npm install” and press Enter and Wait for Installation to be
 completed (requires Internet)
 3. After Installation You will See ‘node_modules’ Folder in the Sidebar
 4. After that type “npm run dev” in terminal
 5. Nowyou will see the ‘localhost’ link in that terminal. Open that link in
 the browser.
