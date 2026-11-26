DAYSTACK

Plan your day. Organize your work. Make every moment count.

DAYSTACK is an offline-first productivity workspace designed to help you organize your daily tasks, manage notes, and keep projects structured in one place.

Built with a modern web technology stack and designed to support Android through Capacitor, DAYSTACK brings a focused productivity experience to your devices.

---

✨ Features

- Daily Task Management — Organize and manage your daily tasks.
- Notes Workspace — Keep important notes and information organized.
- Project Organization — Manage your projects in one workspace.
- Offline-First Experience — Work with locally stored data without depending on a constant internet connection.
- Local Data Storage — Uses IndexedDB through Dexie.
- Optional Cloud Integration — Supabase integration for cloud-based workspace capabilities.
- Android Support — Package the web application as an Android app using Capacitor.

---

🛠️ Technology Stack

Technology| Purpose
React 19| User interface
TypeScript| Type-safe development
Vite| Development and build tooling
Tailwind CSS 4| Styling
Dexie| IndexedDB database management
Supabase| Optional cloud backend
Capacitor 7| Android application integration

---

📱 Platform Support

Platform| Support
Web| Primary platform
Android| Capacitor-based application
Desktop| Accessible through supported web browsers

---

🚀 Getting Started

Prerequisites

Install the following:

- Node.js 20 or newer
- npm
- Git

1. Clone the repository

git clone https://github.com/YOUR_USERNAME/daystack-android.git

2. Enter the project directory

Extract the original project ZIP if necessary, then navigate into the application directory.

cd daystack

3. Install dependencies

npm ci

4. Start the development server

npm run dev

5. Build for production

npm run build

The production build is generated inside the "dist" directory.

---

🤖 Android APK Build

DAYSTACK uses Capacitor to package its web application for Android.

The repository includes a GitHub Actions workflow for automated APK builds.

Build process

1. Open the repository's Actions tab.
2. Select the DAYSTACK APK build workflow.
3. Run the workflow.
4. Wait for the build to complete.
5. Download the generated APK artifact.

Install on Android

1. Download the APK.
2. Open it on your Android device.
3. Follow Android's installation instructions.

Note: Debug APKs are intended for testing. A properly signed release build should be prepared before production distribution.

---

☁️ Cloud Integration

DAYSTACK supports optional Supabase integration.

Cloud functionality requires:

- A configured Supabase project.
- The required environment variables.
- The project's database SQL migration.
- Proper backend configuration.

Local offline functionality and cloud functionality have different setup requirements.

---

🔒 Data & Privacy

DAYSTACK is designed around local-first data storage.

The application uses IndexedDB through Dexie for local persistence. Optional cloud functionality requires separate Supabase configuration.

Review the application's implementation and deployment configuration before relying on it for sensitive information.

---

🗺️ Project Vision

The goal of DAYSTACK is to create a unified productivity workspace that makes daily organization simpler and more accessible.

The project is being developed with a web-first approach, while maintaining a path toward Android distribution.

---

📦 Releases

Download available Android builds from the repository's Releases section.

Each release should include its version number, release notes, and corresponding APK.

---

👨‍💻 Development

Contributions, suggestions, and feedback are welcome.

Before submitting changes:

1. Keep the code organized.
2. Test your changes.
3. Run the production build.
4. Document significant changes.

---

📄 License

Add your chosen open-source or proprietary license before distributing the project.

---

<p align="center">DAYSTACK

Build better days, one task at a time.

</p>
