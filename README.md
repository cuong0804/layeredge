# Layer Edge Auto Ping Node

![banner](./img/image.png)
- website : https://dashboard.layeredge.io/

## Features

- **Auto Run Node**
- **Auto Create Accounts**
- **Auto Referrall**
- **Support Proxy usage**
- **Auto Claim Points every hour**

## Prerequisites

- Node.js installed on your machine


## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/cuong0804/layeredge.git
    cd layeredge
    ```

2. Install the required dependencies:
    ```sh
    curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
    sudo apt install -y nodejs
    ```
    ```sh
    npm install
    ```
3. paste proxy in `proxy.txt`:
-  format `http://username:password@ip:port` or `socks5://username:password@ip:port`
    ```sh
    nano proxy.txt
    ```
4. Auto Referral / create new wallets
    ```sh
    npm run autoref
    ```
4. Run the script:
    ```sh
    npm run start
    ```


## Các wallet đã tạo được lưu trong file  `wallets.json`


## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).