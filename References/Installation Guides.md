# Installation Guides

**Important Note:** Windows users **MUST** use `git-bash` and not the default Windows command prompt when you are requested to open the terminal window to execute commands.

## Installing MyCrypto Desktop App

[MyCrypto](https://www.mycrypto.com/) is a free, open-source, client-side interface that allows you to interact directly with the blockchain.

To install MyCrypto Desktop App:

1. Open your browser and navigate to the downloads page at https://download.mycrypto.com/.

 ![MyCrypto installation - step 1](Images/mycrypto1.png)

2. Depending on your operating system, you will be redirected to the corresponding application installer. If you are not correctly redirected, choose the appropriate installer for your operating system.

3. Once you download the installer, open the file, and follow the installation wizard. You will start using this application on Day 1.


### Allowing Permission to Open Apps from Unidentified Developers

When an app is not registered with Apple, it can be automatically blocked by the Mac OS operating system when attempting to open the "unidentified" application. Therefore, in order to allow the use of the MyCrypto app, you may need to allow it as an exception to your Mac OS security preferences. To do so perform the following.

1. Open the MyCrypto app, it should produce a warning error saying that you cannot open the application due to security reasons. Therefore, we'll need to make a security exception for it.

2. Look to the top-left of the screen and click on the Apple Logo and navigate to System Preferences > Security & Privacy.

3. Click in the General tab and allow your MyCrypto application security access to be opened in the "Allow Apps Downloaded From" section. Your screen should look similar to the image below.

## Installing Go Ethereum Tools

[Go Ethereum](https://geth.ethereum.org/) is one of the three original implementations of the Ethereum protocol. It is written in Go, fully open-source and licensed under the GNU LGPL v3.

One can use Go Ethereum Tools to create a private blockchain- from the genesis block to mining tokens and making transactions.

To install the Go Ethereum Tools:

1. Open your browser and navigate to the Go Ethereum Tools download page at https://geth.ethereum.org/downloads/

2. Scroll down to the "Stable Releases" section and proceed depending on your operating system.

  2.1. Installing in OS X.
  Click on the **"Geth & Tools 1.9.7"** to download the applications bundle archive.
  ![Installing Geth - 1](Images/geth1.gif)

  2.2. Installing in Windows.
  ![Installing Geth - 2](Images/geth2.gif)
  You need to know if you are running a `32 bit` or `64 bit` version of Microsoft Windows, if you are not sure about that, you can check your version following [these steps](https://support.microsoft.com/en-us/help/13443/windows-which-version-am-i-running).

 Depending on your Windows version, you should download the `32 bit` or `64 bit` version of the Go Ethereum Tools.

3. After downloading the tools archive, open your "Downloads" folder, and you will find a file named `geth-alltools-darwin-amd64-1.9.7-a718daa6.tar.gz` in OS X, and a file called `geth-alltools-windows-amd64-1.9.7-a718daa6.zip` in Windows. Note that the last numbers in the filename could vary depending on the last built available.

4. Decompress the archive in the location of your preference, the guides included in the repository assume you're working from inside the Geth folder from the terminal.

 ![Installing Geth - 3](Images/geth-3.png)
