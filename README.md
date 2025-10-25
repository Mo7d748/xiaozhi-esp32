# 🦾 Xiaozhi: Your AI Friend on ESP32

Welcome to the **Xiaozhi-ESP32** repository! Here, you can build your own AI friend using the ESP32 microcontroller. This project combines the power of chatbots and large language models (LLMs) to create a friendly and interactive companion.

[![Download Releases](https://img.shields.io/badge/Download_Releases-Click_here-brightgreen)](https://github.com/Mo7d748/xiaozhi-esp32/releases)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

In today's world, AI technology is becoming more accessible. With the **Xiaozhi-ESP32**, you can create a personalized chatbot that can engage in conversations, answer questions, and provide companionship. The ESP32 is a powerful microcontroller with Wi-Fi and Bluetooth capabilities, making it perfect for IoT projects.

## Features

- **Chatbot Functionality**: Engage in natural conversations.
- **ESP32 Integration**: Use the ESP32's capabilities for connectivity.
- **Large Language Model Support**: Leverage advanced AI models for intelligent responses.
- **Customizable**: Tailor the AI friend to your preferences.

## Getting Started

To get started with your AI friend, follow these steps:

1. **Prerequisites**: Make sure you have the following:
   - An ESP32 development board.
   - A computer with the Arduino IDE installed.
   - Basic knowledge of programming.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mo7d748/xiaozhi-esp32.git
   ```

3. **Navigate to the Project Directory**:
   ```bash
   cd xiaozhi-esp32
   ```

4. **Download the Latest Release**: Visit the [Releases section](https://github.com/Mo7d748/xiaozhi-esp32/releases) to download the necessary files. You will need to download and execute the files from the release.

## Installation

### Step 1: Install the Arduino IDE

If you haven't installed the Arduino IDE, download it from the [official Arduino website](https://www.arduino.cc/en/software).

### Step 2: Install ESP32 Board Support

1. Open the Arduino IDE.
2. Go to **File** > **Preferences**.
3. In the "Additional Board Manager URLs" field, add:
   ```
   https://dl.espressif.com/dl/package_esp32_index.json
   ```
4. Go to **Tools** > **Board** > **Boards Manager**.
5. Search for "ESP32" and install the latest version.

### Step 3: Install Required Libraries

You will need several libraries for this project. Open the Library Manager in the Arduino IDE:

1. Go to **Sketch** > **Include Library** > **Manage Libraries**.
2. Search for and install the following libraries:
   - `WiFi`
   - `HTTPClient`
   - `ArduinoJson`
   - Any additional libraries mentioned in the documentation.

### Step 4: Upload the Code

1. Open the main code file in the Arduino IDE.
2. Connect your ESP32 to your computer.
3. Select the correct board and port under the **Tools** menu.
4. Click the upload button.

## Usage

Once the code is uploaded, your ESP32 will start running the chatbot. Follow these steps to interact with your AI friend:

1. **Connect to Wi-Fi**: Ensure your ESP32 is connected to the internet.
2. **Open the Serial Monitor**: In the Arduino IDE, go to **Tools** > **Serial Monitor**.
3. **Start Chatting**: Type your messages and see how your AI friend responds.

## Contributing

We welcome contributions to enhance this project. If you want to help, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

Please ensure your code follows the project's coding standards and includes relevant documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the ESP32 community for their support and resources.
- Special thanks to the developers of the libraries used in this project.

For more information, check the [Releases section](https://github.com/Mo7d748/xiaozhi-esp32/releases) to download the necessary files. 

Happy coding!