# GemBot AI - A Multi-Modal AI Assistant

GemBot AI is a versatile, multi-modal AI assistant developed in Flutter, leveraging Google’s Gemini AI model to support a range of interaction modes for enhanced user engagement and functionality. The app integrates both text and image capabilities, creating a seamless conversational experience.

---

## Table of Contents

- [Features](#features)
  - [Interaction Modes](#interaction-modes)
  - [Technical Features](#technical-features)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Features

### Interaction Modes

GemBot AI offers three distinct modes of interaction, each tailored for a unique user experience.

- **Text Only Mode**
  - Simple text-based conversations
  - Real-time response generation
  - Clean chat interface with scrollable history
  - Loading indicators for feedback during responses

- **Text & Image Mode**
  - Supports both text and image inputs
  - Capable of analyzing images and providing descriptions
  - File picker integration for easy image selection
  - Combines text and image prompts for more dynamic interactions

- **Text Chat Mode**
  - Maintains conversation context for a natural conversational flow
  - Chat-style interface with message history
  - Memory of previous exchanges for cohesive interactions

### Technical Features

- **Cross-Platform**: Built with Flutter, providing compatibility across both Android and iOS platforms
- **Google Gemini API**: Integrates the google_gemini and google_generative_ai packages for advanced AI interactions
- **Smooth Scrolling**: Uses ScrollablePositionedList to enable efficient scrolling through chat history
- **Material Design**: Custom widgets and Material Design principles ensure a modern, intuitive UI
- **Responsive Design**: Adapts layout to different device sizes for a consistent experience
- **Robust Error Handling**: Comprehensive error handling and loading states enhance user feedback

---

## Architecture

GemBot AI is designed with a clean separation of concerns to maintain clarity and organization within the codebase.

- **Dashboard**: The main container that houses a `TabController` to manage the three interaction modes.
- **State Management**: Consistent state management across components to handle various chat states effectively.
- **Reusable Components**: Custom widgets for chat bubbles and prompts create a cohesive and reusable UI.
- **Efficient History Management**: Supports smooth transitions and maintains conversation history across sessions.

---

## Getting Started

Follow these instructions to set up and run the GemBot AI on your local machine.

### Prerequisites

- **Flutter SDK**: Install Flutter and set up your development environment.
- **API Key**: Obtain an API key from Google’s Gemini AI platform.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/bishwathakur/GeminiChatbot.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd GeminiChatbot
    ```

3. **Install dependencies**:
    ```bash
    flutter pub get
    ```

4. **Configure the API key**:
   - Add your Google Gemini API key in the appropriate configuration file.

5. **Run the app**:
    ```bash
    flutter run
    ```

---

## Usage

Upon launching the app, users can navigate between the different interaction modes through a tab-based menu:

1. **Text Only Mode**: For basic conversations.
2. **Text & Image Mode**: Use the file picker to upload an image, or combine text and image inputs.
3. **Text Chat Mode**: Engage in a natural conversation with memory of previous exchanges.

Each mode provides unique capabilities that allow for a comprehensive user experience.

---

## Contributing

Contributions are welcome! To propose improvements or add new features, please fork the repository, create a branch, and submit a pull request. For major changes, please open an issue first to discuss the proposed updates.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

GemBot AI demonstrates the powerful possibilities of AI-driven mobile applications by combining text and image interactions in a single platform.
