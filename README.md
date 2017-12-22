# Sublime Text 3 Configuration

My Sublime Text 3 configuration settings.

## Installation

0. [Install Package Control](https://packagecontrol.io/installation) in Sublime Text 3 and exit Sublime

1. Clone this repository in Sublime's directory as `Packages/User'

    * OSX: 
    ```
    cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
    zip User_old.zip User
    rm -r User
    git clone https://github.com/johnpaton/sublime-config User
    ```

    * Windows:
    ```
    cd '~\AppData\Roaming\Sublime Text 3\Packages'
    mv User ..\User_old
    git clone https://github.com/johnpaton/sublime-config User
    ```

2. Install Python requirements

    ```
    cd User
    pip install -r requirements.txt
    ```

3. Open Sublime and wait for packages to download (may take several minutes)

4. Restart Sublime once all packages have downloaded
