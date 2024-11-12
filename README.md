# Financy App

Financy App is a Flutter-based personal finance management tool that helps users track expenses, set budgets, and achieve their financial goals. The app provides insightful analytics and an intuitive interface to simplify financial tracking and decision-making.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Expense Tracking**: Track daily expenses with category tagging.
- **Budget Management**: Set monthly budgets and receive alerts when nearing limits.
- **Financial Goals**: Define and track savings or investment goals.
- **Analytics & Reports**: View spending trends and visualizations.
- **Multi-Currency Support**: Manage finances in different currencies.
- **Dark Mode**: Toggle between light and dark themes for user comfort.

## Getting Started

These instructions will help you set up and run the Financy App on your local machine for development and testing purposes.

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Android Studio or Xcode (for Android/iOS emulators)
- Visual Studio Code or any preferred IDE with Flutter support

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/financy-app.git
   cd financy-app
   ```

2. **Install Dependencies**

    ```flutter pub get```

3. **Run the App**

    ```flutter run```

### Folder Structure
```
financy-app/
├── lib/
│   ├── main.dart            # App entry point
│   ├── models/              # Data models
│   ├── screens/             # UI screens
│   ├── widgets/             # Reusable widgets
│   ├── providers/           # State management files
│   ├── services/            # API and database services
│   └── utils/               # Utility functions and constants
├── assets/                  # Static assets (images, icons)
├── test/                    # Unit and widget tests
├── pubspec.yaml             # Project dependencies
└── README.md                # Project README
```

### Usage

- Sign Up / Log In: Create an account or log in with your existing account.
- Add Expense: Go to the "Add Expense" section, select a category, and input the expense amount.
- Set Budget: Navigate to "Budget" to set monthly spending limits per category.
- Track Goals: Define financial goals and monitor progress from the "Goals" section.
- View Reports: Check spending analytics from the "Reports" section.

### Technologies Used

- Flutter - UI development
- Dart - Programming language
- SQLite - Local database for offline data persistence
- Provider / Riverpod - State management
- Flutter Charts - For graphical data representation

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
