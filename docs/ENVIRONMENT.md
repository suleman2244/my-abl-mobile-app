# 🌐 MyABL Mobile App — Environment & Setup Notes

This file describes **the conceptual development and deployment environment** for MyABL Mobile App.

## 🔹 Development Environment

| Component | Recommendation |
|-----------|----------------|
| OS | Windows 10/11 (Android), macOS (iOS) |
| IDE | Visual Studio Code (React Native), Visual Studio (Backend), Xcode (iOS) |
| Node & NPM | Node.js v18+, NPM v9+ |
| React Native CLI | react-native-cli latest stable |
| Java / Kotlin | JDK 11+ for Android builds |
| iOS SDK | Xcode 14+ |
| Backend | .NET Framework 4.8+ / ASP.NET Web API |
| Database | SQL Server 2019+ |

## 🔹 Environment Variables & Config

> Example conceptual setup (no real secrets included):

```bash
API_BASE_URL=https://api.myabl.com
JWT_SECRET_KEY=<encrypted>
ENV=production
FIREBASE_API_KEY=<firebase_api_key>
