# blockchain-workshop

## Software Installation
Please complete the following steps to install the required software. You can skip any steps for software you already have installed if there is no stated minimum version, otherwise please ensure your version is equal to or greater than the stated minimum version of the software. If your version is less than the stated minimum version, please upgrade to the latest version as per the instructions below.

### METAMASK
Download and install MetaMask, a browser extension that you’ll use as a wallet for interacting with your smart contracts and the Ethereum network. MetaMask requires either Google Chrome or Brave browser, and also has limited support for Firefox and Opera. We recommend Chrome or Brave. 

Open your MetaMask browser extension (look for the fox symbol in your extensions on the top right of the browser), and setup your account.

Once your account is setup, change the Ethereum network that MetaMask is connected to, to the Kovan Testnet by selecting the dropdown at the top, and changing it to ‘Kovan Test Network’.


### NODE.JS
Minimum Required Version : 12.0.0

Minimum Windows O/S Version: 10

Minimum macOS version: 10

You can skip this step if you already have a working Node.js 12.0 or greater installation. To check this, you can open a new Terminal/Windows Command Prompt (or another CLI of your choice), type the command below and press enter. For Windows users, Command Prompt can be found by pressing the Windows Start Button and searching for ‘Command Prompt’. For Mac users, the terminal can be found in Applications.
```
node -v
```
If you get a reported version (as per the screenshot further down), you already have Node.js installed, and can skip this section if it meets the minimum requirements. Otherwise if you get an error, it means you don’t have Node.js installed, and you should continue these steps to download and install it. If you do have a version of Node.js installed, but it’s less than 12, follow these instructions to upgrade it.

If you don’t have Node.js installed, download and install the latest version of the JavaScript runtime environment Node.js and package manager NPM. This step is required for both JavaScript and Python tracks of the bootcamp. Accept all default answers for questions.

Once you’ve completed the installation, open a new Terminal/Windows Command Prompt (or another CLI of your choice), type the command below to ensure your installation is successful. For windows users, Command Prompt can be found by pressing the Windows Start Button and searching for ‘Command Prompt’. For Mac users, the terminal can be found in Applications.
```
node -v
```

Once you’ve verified your Node.js installation, also verify your NPM installation by entering the following command:
```
npm -version
```

### GIT
Download and install the distributed revision control system Git. We will need this when installing some packages, and also to check your code into a repository when you’re finished. Accept all default values during installation. If you’re using macOS and you get prompted to install ‘command line developer tools’, accept and install them.

To test git once it’s installed, open a new Terminal/Windows Command Prompt (or another CLI of your choice), and type the command below:
```
git --version
```
### VISUAL STUDIO CODE
Using Visual Studio Code will make it easier when you're following along with the exercises, and the integrated terminal makes it easier to switch between editing files, and running commands. If you have your own editor that you’re comfortable with, you can skip this step.

Goto https://code.visualstudio.com/, download and install the latest version of Visual Studio Code for your operating system

Open up Visual Studio Code. In the top menu, choose Code (File if you’re using Windows) > Preferences > Extensions

Search for the word ‘solidity’, then select and install the Solidity extension. This will give you syntax highlighting when developing your smart contracts


Enable the terminal by selecting View -> Terminal from the top menu (or the keyboard shortcut Ctrl + `). Ensure you can run Node.js commands in your terminal window by running the following command:
```
node -v
```

If you’re using Windows and you get an error, ensure you’re using your CMD Terminal:

In VS Code, press CTRL + SHIFT + P

Search for ‘Terminal Select Default Profile’

Select the ‘Command Prompt’ selection

Restart VS Code and try running the command again in the terminal

### Install Hardhat
[Hardhat Guide here](https://hardhat.org/getting-started/)
