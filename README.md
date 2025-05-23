# ChatGPT Flutter Chatbot

A modern Flutter application that integrates with OpenAI's ChatGPT API to create an interactive chatbot with both text and image generation capabilities.

## Features

- 💬 Real-time chat interface with ChatGPT
- 🎨 AI Image generation support
- 🌓 Dark mode support
- 🎯 Material Design 3 implementation
- ⚡ Fast and responsive UI using VelocityX

## Prerequisites

- Flutter SDK (>=2.18.6 <3.0.0)
- OpenAI API Key
- Android Studio/VS Code with Flutter extension

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ChatGPT-Flutter-Chatbot.git
   cd ChatGPT-Flutter-Chatbot
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Create a `secrets.dart` file in `lib/auth/` directory and add your OpenAI API key:
   ```dart
   const String mySecretKey = 'your-openai-api-key';
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Dependencies

- [chat_gpt_sdk](https://pub.dev/packages/chat_gpt_sdk): ^1.0.2+3
- [velocity_x](https://pub.dev/packages/velocity_x): ^3.6.0
- [cupertino_icons](https://pub.dev/packages/cupertino_icons): ^1.0.2

## Usage

1. Launch the app
2. Type your message in the text input field
3. Toggle between text and image generation modes using the camera icon
4. Send your message and wait for the AI response

## Project Structure

- `lib/main.dart` - Application entry point and theme configuration
- `lib/chat_screen.dart` - Main chat interface and ChatGPT integration
- `lib/chat_message.dart` - Chat message widget implementation
- `lib/three_dots_widget.dart` - Loading animation widget

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to OpenAI for providing the ChatGPT API
- Built with Flutter and Material Design 3
