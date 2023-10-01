# ChatsApp - Cross Platform Flutter Chat Application

![ChatsApp](https://github.com/shivam-kumar-shah/chats_app_flutter/assets/134827809/8783c019-7392-4e76-a545-72f33b7b2a1c)

## Description

ChatsApp is a versatile cross-platform chat application built with Flutter. It offers both global and private chat functionalities, enabling users to communicate seamlessly. The app is backed by Cloud Firestore, ensuring real-time updates. User authentication is handled securely using Firebase's email and password authentication. State management is efficiently managed using the Provider library.

## Features

- **Global and Private Chats**: Engage in both public group discussions and private one-on-one conversations with other users.

- **Real-time Updates**: Cloud Firestore ensures that messages and chats are updated in real-time, providing a seamless chatting experience.

- **Firebase Authentication**: Users can create accounts and log in securely using Firebase's email and password authentication system.

- **Cross-platform**: The app is built using Flutter, making it compatible with both Android and iOS platforms.

- **Efficient State Management**: Provider library is used for efficient state management, ensuring smooth performance.

## Getting Started

To run ChatsApp on your local environment, follow these steps:

1. Clone the repository:

```bash
  git clone https://github.com/shivam-kumar-shah/chats_app_flutter && cd chats_app_flutter
```

3. Install the required dependencies using:

```bash
   flutter pub get
```

3. Start the app on your preferred emulator or connected device using:

```bash
  flutter run
```

## Building the Application

To build the chatsApp, follow these instructions:

1. Open a terminal or command prompt.

2. Navigate to the project directory:

```bash
  cd /path/to/chats_app_flutter
```
3. To build a smaller bundle size optimized for specific device architectures, use the following command:

```bash
   flutter build --split-per-abi
```

> This command will generate separate APK files for different device architectures (arm64-v8a, armeabi-v7a, etc.). This is recommended for reducing the app size.

4. If you prefer a larger bundle that is architecture-independent, use the following command:

```bash
  flutter build
```

> This command will generate a single APK file that can run on various device architectures. Keep in mind that this option may result in a larger app size.

5. After the build process is complete, you can find the generated APK files in the `build/app/outputs/flutter-apk` directory.

## Usage

ChatsApp provides an intuitive and user-friendly interface for seamless communication. Users can create accounts, join global chats, and initiate private conversations with others. Real-time updates ensure that messages are delivered instantly.

## Technologies Used

- Flutter
- Firebase (Firestore, Authentication)
- Provider (State Management)

## Screenshots

<div style = "display:grid; grid-template-columns:repeat(3,1fr); gap:50px;">
<img src = "https://user-images.githubusercontent.com/105339885/227755997-700137d6-9f1d-4a05-a787-08a454249617.jpg" width="30%"/>
<img src = "https://user-images.githubusercontent.com/105339885/227756005-5755c1e9-fdd2-41e8-95f0-fed212d6ec61.jpg" width="30%"/>
<img src = "https://user-images.githubusercontent.com/105339885/227756015-365388a4-238e-4585-b2fd-4f48a6ad96dc.jpg" width="30%"/>
<img src = "https://user-images.githubusercontent.com/105339885/227756027-e99a3766-5467-4fed-bec5-ecfaef3a62d8.jpg"  width="30%"/>
<img src = "https://user-images.githubusercontent.com/105339885/227756036-c3e73359-582c-44d6-8963-0507369e74b1.jpg" width="30%"/>
</div>

## Contributing

Contributions are welcome! If you have any ideas, bug fixes, or improvements, please open an issue or submit a pull request.

## Contact

For any inquiries or feedback, feel free to contact us at [shivam-kumar-shah@outlook.com](mailto:shivam-kumar-shah@outlook.com).

---

*Happy Coding!* 🚀
