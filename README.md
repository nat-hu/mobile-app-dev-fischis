# Fischis 🐠
**A Gamified Productivity App for Android**

This application was developed as the final project for the module **Mobile Application Development**.

---

## Academic Context
* **Course:** Mobile Application Development (119310a)
* **Institution:** HdM Stuttgart
* **Focus:** Native Android Development, Persistence, and Architecture Patterns.

---

## Project Overview
The goal of this app is to help users stay focused by gamifying the "Deep Work" process. The user sets a timer to study; during this time, a fish grows through various stages. If the focus session is completed successfully, the fish is permanently **collected in a virtual aquarium** as a reward. However, if the user leaves or closes the app before the timer ends, the session is interrupted and the progress is lost.

### Key Features
* **Customizable Focus Timer:** Set your desired focus duration. Includes future support for calendar/appointment integration.
* **Fish Evolution System:** Watch your fish grow through **3 distinct stages** as you complete your focus session.
* **In-App Economy:** Earn **Coins (Game Currency)** for every successful session.
* **Fish Store:** Spend your hard-earned coins to unlock new species of fish.
* **Collection Gallery:** An overview of all the fish species you have collected.
* **Reminders:** Customizable notifications in the settings to keep your study routine on track.
* **Start Animation:** A polished entry experience when launching the app.
* **Localization:** Built-in support for multiple languages.

---

## Technical Implementation

### Libraries & Dependencies
The project utilizes several industry-standard libraries to ensure a robust and scalable application:
* **Room:** Used for the local SQLite database to store user progress, coin balance, and collected fish.
* **Retrofit:** Implemented for network-related tasks and API communication.
* **Glide:** Handles efficient image loading and management for the fish assets.
* **AndroidX:** Ensures modern UI components and backward compatibility.

### Architecture
To keep the codebase clean and maintainable, the project implements:
* **Factory Pattern:** A `FishFactory` is used to instantiate different fish types dynamically, making the store system easily expandable.
* **Data Persistence:** All game states are managed via Room to ensure progress is saved across app restarts.

---

> **Note:** This project was created for educational purposes. 
