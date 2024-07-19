---
title: "프로젝트 설계-구조"
date: 2024-07-17 16:00:00 +0900
tags: 
    - 프로젝트
comments: true
---

### 프로젝트 구조
```plaintext
messenger-front/
|-- public/
|-- src/
|   |-- components/
|   |   |-- Sidebar.jsx
|   |   |-- Header.jsx
|   |   |-- ChatList.jsx
|   |   |-- ChatListItem.jsx
|   |   |-- ChatWindow.jsx
|   |   |-- ChatHeader.jsx
|   |   |-- MessageList.jsx
|   |   |-- MessageItem.jsx
|   |   |-- MessageInput.jsx
|   |-- pages/
|   |   |-- LoginPage.jsx
|   |   |-- ChatPage.jsx
|   |   |-- FilesPage.jsx
|   |   |-- SettingsPage.jsx
|   |-- redux/
|   |   |-- actions/
|   |   |   |-- chatActions.js
|   |   |   |-- settingsActions.js
|   |   |-- reducers/
|   |   |   |-- chatReducer.js
|   |   |   |-- rootReducer.js
|   |   |   |-- settingsReducer.js
|   |   |-- store.js
|   |-- App.jsx
|   |-- main.jsx
|-- index.html
|-- package.json
|-- vite.config.js
```

```plaintext
messenger-server/
|-- src/
|   |-- main/
|       |-- java/
|           |-- com/example/messenger/
|               |-- controller/
|               |   |-- UserController.java
|               |   |-- ChatController.java
|               |   |-- FileController.java
|               |-- service/
|               |   |-- UserService.java
|               |   |-- ChatService.java
|               |   |-- FileService.java
|               |-- mapper/
|               |   |-- UserMapper.java
|               |   |-- ChatMapper.java
|               |   |-- FileMapper.java
|               |-- model/
|               |   |-- User.java
|               |   |-- Chat.java
|               |   |-- Message.java
|               |   |-- File.java
|               |-- MessengerApplication.java
|       |-- resources/
|           |-- mapper/
|               |-- UserMapper.xml
|               |-- ChatMapper.xml
|               |-- FileMapper.xml
|           |-- application.yml
|-- build.gradle
```