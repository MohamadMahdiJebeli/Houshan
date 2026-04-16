<img width="150" alt="Houshan" src="https://github.com/user-attachments/assets/8a874265-6e65-4edb-a247-022532d899e3" />

**🤖 [Houshan - All-in-One AI Assistant](https://houshan.ai)** : The Houshan App is a Flutter-based application designed to give users the fastest and most cost-effective access to leading AI models and tools in a single, unified platform.

> **Note:** This repository is for demonstration and portfolio purposes only. The source code is proprietary and closed-source.

🚀 Features:

- Access a wide range of AI models in one unified space
- Build and customize your own personalized AI assistants
- Share custom assistants with others and monetize them easily

## 🛠️ Tech Stack & Libraries
This project relies on a robust and scalable architecture using modern Flutter development practices.

* **State Management:** BLoC / Cubit
* **Networking:** Dio
* **Backend & Push Notifications:** Firebase
* **Local Storage:** Shared Preferences
* **Monetization (Ads):** Tapsell, Adivery
* **Routing:** Custom Route Generator

## 📂 Architecture Overview (Folder Structure)
The application follows a clean, feature-based architecture divided into three main layers:

```text
lib/
├── core/               # Core configuration and services
│   ├── services/       # Network (Dio), Firebase, File Managers, Ad Services
│   ├── utils/          # Formatting and utility functions
│   └── routes/         # Custom route generation logic
├── data/               # Data layer
│   ├── model/          # Data models (Auth, AI, Media, Forum, etc.)
│   └── repository/     # API integration and data fetching
└── ui/                 # Presentation layer
    ├── screens/        # Feature modules (Chat, GMedia, Assistant, Auth)
    ├── widgets/        # Highly modular and reusable UI components
    └── theme/          # Custom responsive theming and styling

```
## 🌐[Houshan Official Website](https://houshan.ai):
For more information and to experience the platform, check out our website:

https://houshan.ai
