# Tic-Tac-Toe App

Hey there. You’re probably thinking to yourself, “Why reinvent the wheel when there are so many other options out there?”

Fair question.

Tic-tac-toe has been around forever, and honestly this project is not really about tic-tac-toe at all.

The point is to show that I can build a fully functional app and distribute it across multiple platforms.

Oh and maybe have a little fun while doing it ;)

---

## Requirements

Before you start, make sure you have:

- Node.js installed (this includes npm)  
  Download it here: https://nodejs.org

Optional for desktop builds:

- Rust (for Tauri builds)  
  https://www.rust-lang.org/tools/install

---

## Instructions to run as a local app

Step one: Download the ZIP from this repository and unzip it.

Step two: Open Terminal and navigate into the project folder:
Command: cd path/to/your/Tic-Tac-Toe-App

Step three: Install dependencies
Command: npm install

Step four: Launch the desktop app
Command: npm run tauri dev

3# Instructions to run as a web app

Step one: Download the ZIP from this repository and unzip it.

Step two: Open Terminal and navigate into the project folder
Command: cd path/to/your/Tic-Tac-Toe-App

Step three: Install dependencies
npm install

Step four: Start the web dev server
Command: npm run dev 
This shoud show a link that you can copy and paste to a web browser

## Instructions to run as an ios app

** DISCLAIMER **
I am not an iOS developer by any means and this app is not on the App Store. This may change someday if I decide to build more apps and can somehow afford Apple’s developer program on a college budget. Also, this build method is experimental and may be a bit janky.

Step one: Install Apple’s Simulator (you will need a Mac for this).

Step two: Follow the instructions above to download and set up the local project.

Step three: Run the following commands together to start the simulator and launch the app
commands:xcrun simctl shutdown all
open -a Simulator

Once the Simulator is open, boot a device (or let Xcode handle this automatically).

Step four: install the build onto your simulator
Command: npm run tauri ios dev

** This app bundle is still in its early stages and may have some bugs **

I hope you enjoy the product of my now messed up sleep schedule! (P.S. Email me if you find any bugs pls and thx)
