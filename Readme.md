# QA Tech Week - First Edition
Welcome to the repository of **QA Tech Week - First Edition**!  Here you will find the instructions to set up the environment, start the necessary services, and run the automated tests with Playwright.
## 📌 Prerequisites
Before you begin, make sure you have the following software installed on your system:
- [Git for Windows](https://gitforwindows.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js (LTS version)] (https://nodejs.org/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
## 🐋 Docker Installation Guide
- [Windows](https://dev.to/papitofernando/instalando-o-docker-no-windows-10-home-ou-professional-com-wsl-2-26m3)
- [MacOS](https://docs.docker.com/desktop/setup/install/mac-install/)
- [Linux Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
## 🚀  Environment Setup
1. Fork the project
2. Clone this repository:
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
git clone git@github.com:your-username/qatw-first-edition.git
cd qatw-first-edition
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
## 🐳 Setting Up the Environment with Docker Compose
The project uses Docker Compose to manage the services needed for testing.
1. Make sure Docker Desktop is running.
2. In the terminal, execute the command below to start the services:
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
docker-compose up -d
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
3. To check if the containers are running:
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
docker ps
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
4. To stop the services:
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
docker-compose down
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
## 🧪 Running Tests with Playwright
1. Install the Playwright dependencies:
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
npx playwright install
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
2. To run the tests locally:
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
npx playwright test
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
3. To view the test report after execution:
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
npx playwright show-report
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
4. To run the tests in UI mode (visualizing the execution):
It seems like you haven't provided any text to translate. Please provide the text you want to be translated, and I'll be happy to help!
npx playwright test --ui
It seems like you haven't provided any text to translate. Please provide the text you'd like to have translated, and I'll be happy to help!
## 📄 License
This project is under the MIT license.