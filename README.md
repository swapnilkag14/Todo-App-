# 📋 Flutter To-Do App

## Overview

This is a simple To-Do application built with Flutter, leveraging the Riverpod library for state management. The app interacts seamlessly with the NStack API, a free API service for managing to-do items. It supports essential operations such as adding, editing, and deleting tasks while following best practices for Flutter development.

## 📸 Screenshots

![Home Screen](https://raw.githubusercontent.com/swapnilkag14/Todo-App-/refs/heads/main/Todo-App-master/Screenshot%202024-09-18%20211611.png)
![Add Task Screen](https://raw.githubusercontent.com/swapnilkag14/Todo-App-/refs/heads/main/Todo-App-master/Screenshot%202024-09-18%211622.png)
![Edit Task Screen](https://raw.githubusercontent.com/swapnilkag14/Todo-App-/refs/heads/main/Todo-App-master/Screenshot%202024-09-18%211353.png)

## 🚀 Features

- ✅ **Add New Tasks**: Easily create new to-do items with a simple and intuitive form.
- ✏️ **Edit Existing Tasks**: Modify your tasks to keep them up to date, with a dedicated edit screen.
- 🗑️ **Delete Tasks**: Remove tasks that are no longer needed with a single tap.
- 📱 **Responsive Design**: Works beautifully on both mobile and web platforms, adapting to various screen sizes.
- ⚡ **Efficient State Management**: Utilizes Riverpod for a smooth user experience, ensuring efficient updates and minimal boilerplate code.
- 🔍 **Search Functionality**: Quickly find tasks by searching through your to-do list.
- 🌙 **Dark Mode Support**: Switch between light and dark themes for a personalized experience.

## 🛠️ Installation

To run this project, ensure you have Flutter installed on your machine. Follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/swapnilkag14/Todo-App.git
   cd Todo-App
   ```

2. **Install dependencies**: Run the following command to install the required packages:
   ```bash
   flutter pub get
   ```

3. **Run the app**: Launch the application on your preferred device or emulator:
   ```bash
   flutter run
   ```

## 🔧 Configuration

Before using the NStack API, you'll need to set up your API keys. Follow these steps:

1. **Sign up for an NStack account** at [NStack](https://nstack.com).
2. **Create a new project** and configure the to-do items API.
3. **Add your API key** to the project. You can do this by editing the `lib/config.dart` file and updating the `API_KEY` variable:

   ```dart
   // lib/config.dart
   const String API_KEY = 'your_api_key_here';
   ```

## 🌟 Best Practices

- **State Management**: Utilize Riverpod to manage your application's state effectively. This helps in maintaining a clear architecture and easy testing.
- **Responsive UI**: Use Flutter's layout widgets to ensure your app looks great on all devices.
- **Error Handling**: Implement error handling for API requests to improve user experience and provide feedback for potential issues.
- **Testing**: Write unit and widget tests to ensure that your app behaves as expected.

 

 

## 🙏 Acknowledgments

- [Flutter](https://flutter.dev) for the amazing cross-platform framework
- [Riverpod](https://riverpod.dev) for efficient state management
- [NStack](https://nstack.com) for providing a free API for to-do management

## 📞 Contact

Swapnil Kag - [@swapnilkag14](https://twitter.com/swapnilkag14) - swapnilkag14@gmail.com

Project Link: [https://github.com/swapnilkag14/Todo-App](https://github.com/swapnilkag14/Todo-App)
