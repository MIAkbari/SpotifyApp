#  Spotify Aoo

## Architecture
 - Clean Architecture + MVVM
 - Enterprise/FAANG
 - 
## Project Structure
App/
├── Modules/
│   ├── Authentication 
│   ├── Home
│   ├── Player 
│   └── Search 
Core/
│   ├── Networking (API Client)
│   ├── Database (CoreData/Realm)
│   ├── AudioEngine
│   └── Analytics
Shared/
│   ├── UIComponents 
│   └── Utils (Extensions, Helpers
Resources/
    ├── Fonts
    ├── Localization
    └── Assets
# Tech.Tools
## ** State Management **
- SwiftUI + Combine
- Repository Pattern
- Redux/SwiftUI’s EnvironmentObject:

## **Dependency Injection**

- Swinject or Factory

## **Networking**

- SURLSession
- Rest

## **Storage**

- User Defult
- Keychain

## **Audio Streaming**

- AVFoundation or AudioKit

##  **Caching**

- NSCache - Kingfisher - Custom Disk Cache( for big data)

##  **Full Test**
 
- UI. Unit. SwiftUI-SnapshotTesting 

##  **Security**

- Keychain
- Certificate Pinning: MITM Attacks.
- SQLCipher

##  **Performance**

- Instruments: Memory Leaks
- GCD/Swift Concurrency: Thread . async/await.
- SQLCipher 

##  **Maintainability**

- SwiftLint
- Documentation

## ** CI/CD / Desops **

- Fastlane: Build, Test, Deploy
- GitHub Actions/GitLab CI: Run Pipelines
- Firebase Crashlytics: Crash traking

## ** Spotify-Like **
### - Background Audio
 - Enable Audio, AirPlay, and Picture in Picture in Capabilities
 - AVAudioSession for look mangment
 - 
### - Sync 
 - WebSocket , Firebase Realtime Database
### - Recommendations
 - ML + AI
