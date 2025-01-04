This script automates various tasks for the Animix miniapp telegram.

## Features

- **Auto Join/Claim Missions**
- **Auto Gatcha New Pets**
- **Auto Complete Quests**
- **Auto Merge Pets**
- **Auto Claim Rewards**
- **Support Multi accounts**

## Prerequisites

- Node.js installed on your machine
- `users.txt` file containing user data follow instruction below to get:
- Open Animix miniapp telegram [https://t.me/animix_game_bot](https://t.me/animix_game_bot?startapp=A2veN3aAUJqc)
- inspect or just F12 find application
- in session storage find `tgWebAppData` and copy all value. `user=....`
![usersData](img/image-1.png)

## Installation

Install Git:
    ```sh
    pkg install git
    ```
Install nodejs:
    ```sh
    pkg install nodejs
    ```
Install nodejs-lts
    ```sh
    pkg install nodejs-lts
    ```
Clone the repository:
    ```sh
    git clone https://github.com/ronsuru/ANMBAnimix.git
    cd anmbanimix
    ```
Change Directory:
    ```sh
    cd anmbanimix
    ```
Install the required dependencies:
    ```sh
    npm install
    ```
Input your user data in `users.txt` file, one user per line;
    ```sh
    nano users.txt
    ```
Run the script:
    ```sh
    npm run start
    ```

## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).
