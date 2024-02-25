# 2024_Solution Chanllenge
This is 2024 GDSC Solution Challenge CLIP Repository

## ℹ Introduction
CLIP is an app that performs quests to help improve the environment.

### 🚩 UN SDGs Goals
<img width="160" height="158" alt="goal12" src="https://github.com/CLIP-CLImate-Protection/.github/assets/118418288/2bc13e2c-6ece-4bbf-b76b-02cc383d84b1">
<img width="160" height="158" alt="goal13" src="https://github.com/CLIP-CLImate-Protection/.github/assets/118418288/43d92c94-cc2d-40ec-9ec9-c21389544544">

## 🕰 Development period
* 24.01.07 - 24.02.23

### 🧑‍🤝‍🧑 Member
 - Doyeon Koo : AI
 - Sojeong Lee : Backend
 - Minji Kwon : Frontend
 - Miso Kim : Frontend

## 🖥 Build With
* Flutter
* Firebase
* Fast API

## 📍 How to use?

### CLIP Repository
1. Clone CLIP Repository
2. Get dependency
```
    flutter pub get
```
3. Set the file
* lib/firebase_options.dart
* ios/Runner/GoogleService-Info.plist
* ios/firebase_app_id_file.json
* macos/Runner/GoogleService-Info.plist
* macos/firebase_app_id_file.json
* android/app/google-services.json.DS_Store
* android/app/src/main/AndroidManifest.xml
* ios/Runner/AppDelegate.swift
  
 **We can't provide the above files due to API key security issue, so you need to set them up individually.**
 
4. Execute
```
flutter run
```
### CLIP_AI Repository

1. Clone CLIP_AI Repository
2. Install
   
```
    pip install uvicorn
    pip install python-multipart
    pip install ultralytics
```

3. Execute
```
    uvicorn predict:app —reload
```
