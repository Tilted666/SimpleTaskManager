# SimpleTaskManager
A modern, dark-themed desktop task manager built with C# and WPF. This project strictly follows the **MVVM** (Model-View-ViewModel) architecture and uses local JSON storage for data persistence.
## ✨ Features

- **Task Management:** Add, complete, and delete tasks.
- **Auto-save:** All changes are instantly saved to a local JSON file.
- **Modern UI:** Custom dark theme with rounded corners, hover effects, and custom controls (no default Windows 7 styling).
- **MVVM Architecture:** Clean separation of UI (XAML) and business logic (C#) using `CommunityToolkit.Mvvm`.
- **Data Persistence:** Uses `System.Text.Json` to store data safely in the user's local application folder.

## 🛠️ Tech Stack

- **Framework:** .NET 10 (Windows)
- **Language:** C# 13
- **UI:** WPF (Windows Presentation Foundation)
- **Pattern:** MVVM
- **Libraries:** 
  - `CommunityToolkit.Mvvm` (for Observables and Commands)
  - `System.Text.Json` (for data serialization)

## 🚀 How to Run

1. Clone the repository:
   ```bash
