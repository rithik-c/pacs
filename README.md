# 📦 PACS

> "P.A.C.S" - Packaging Automated Centralized System

Love online shopping, but tired of the deliveries arriving when you're not home? Or perhaps how you're continuously checking when you're package arrives, only to delay your plans out of worry? 

Lovers of Online shopping and E-commerce. We present to you, **Pacs**. A unique storage solution with plans to open multiple facilities that have lockers of all shapes and sizes. Kind of like a community mailbox. As a shopper, you won’t have to put in your address. With our app, you’ll be able to see all your purchases from different stores chosen to ship using pacs in one convenient place where you can find your respective locker number and key code for pickup.

###### This project was made with love for HackThe6ix 2022 ❤️

## ⬇️ Table of Contents

* [App Preview](#--app-preview)
* [Set-Up](#-set-up)
* [Resources](#-resources)
* [License Info](#-license)

## 💻  App Preview

<img src="readme_resources/pacs-demo.png" alt="Screenshot of Pacs" title="Screenshot of Pacs" width="600"/>

## 🔨 Set-Up

0. Prequisite Installs
    1. The latest LTS version of Node.js and npm
    2. Preferably an install of create-react-app
1. Clone this git repository
2. Create a .env file in the backend directory that contains "PORT=8080"
3. Navigate install all packages
    ```sh
    cd app_node
    npm i
    cd ../app_react
    npm i
    ```
4. Run the back-end server
    ```sh
    cd app_node
    nodemon start
    ```
5. While the back-end server is running, run the front-end server
    ```bash
    cd app_react
    npm start
    ```
6. Open your browser at http://localhost:3000/
    1. http://localhost:3000/ & http://localhost:3000/dashboard navigates to the homepage
    2. http://localhost:3000/cart navigates to simulated business-side checkout
    3. http://localhost:3000/portal navigates to the gateway from a business screen to our service, allowing the user to choose a locker before returning to the calling business' site

## 📚 Resources

Resources may not be available after HackThis6ix 2022 judging (08/21/2022)
* [GitHub](https://github.com/rithik-c/pacs) 
* [DevPost](https://devpost.com/software/project-pacs) 
* [Youtube](https://youtu.be/6NveoM4sxoo) 
* [Figma](https://www.figma.com/file/rbBWEaPeFodavsq87He1kv/Pacs?node-id=0%3A1)
* [Figjam](https://www.figma.com/file/53VWmI5ujlbq622F0f6M6w/Pacs?node-id=0%3A1)

## 📄 License

Pacs is freely available under the MIT license.
