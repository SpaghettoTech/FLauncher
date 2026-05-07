# FLauncher - Minimalist Terminal Launcher

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/b5f5fbae-a132-48c5-9563-24707325f1f5" alt="Screenshot 1"></td>
    <td><img src="https://github.com/user-attachments/assets/6984928c-688f-4556-a222-630a75cc9fe1" alt="Screenshot 2"></td>
    <td><img src="https://github.com/user-attachments/assets/08c51f22-b586-4da3-96a7-76ce582adbca" alt="Screenshot 3"></td>
    <td><img src="https://github.com/user-attachments/assets/0bc1ed04-8da6-408f-8539-365dc4e9275f" alt="Screenshot 4"></td>
    <td><img src="https://github.com/user-attachments/assets/4204630b-d686-4c2c-b58f-5bb01d7ec11c" alt="Screenshot 5"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/3533ca7d-ca34-4f53-917c-f4fb76d9a8e3" alt="Screenshot 6"></td>
    <td><img src="https://github.com/user-attachments/assets/0adb0c9a-366e-4c7d-bdf6-dcf5ece4d630" alt="Screenshot 7"></td>
    <td><img src="https://github.com/user-attachments/assets/e8b942eb-3f73-4327-a6b3-138df48185f2" alt="Screenshot 8"></td>
    <td><img src="https://github.com/user-attachments/assets/3b659430-edfa-4541-9dd9-7cfc4e95a539" alt="Screenshot 9"></td>
    <td><img src="https://github.com/user-attachments/assets/b0a41018-1265-4963-a17e-05057b5cb5b3" alt="Screenshot 10"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/9ec82297-c0ef-4a00-853a-f73d1e4922b6" alt="Screenshot 11"></td>
    <td><img src="https://github.com/user-attachments/assets/858fac8e-2715-4656-9630-47ee96713e5a" alt="Screenshot 12"></td>
    <td><img src="https://github.com/user-attachments/assets/8380c87c-2f28-47f4-ae18-69f84381223a" alt="Screenshot 13"></td>
    <td><img src="https://github.com/user-attachments/assets/d08bf83f-52d7-4e7c-9f31-d9f743c074e4" alt="Screenshot 14"></td>
    <td><img src="https://github.com/user-attachments/assets/20f8dd3f-17a7-4b97-a2bf-d69cba2b1b94" alt="Screenshot 15"></td>
  </tr>
</table>

FLauncher is a powerful, terminal-inspired Android launcher designed for speed, focus, and minimalism. It replaces your complex home screen with a high-performance command-line interface.

## Core Features

- **Split-Screen Layout**: A modern terminal interface on the left and a dynamic command sidebar on the right.
- **App Management**:
  - `apps`: Lists all installed applications. Shows recently installed apps (last 2 days) at the top.
  - `<app name>`: Instantly launch any app.
  - `remove <app>`: Quickly uninstall applications.
- **Smart Messaging & Terminal Chat**:
  - **Terminal Chat Session**: Clicking a messaging notification opens a dedicated chat session in the terminal, clearing previous output for focus.
  - **Direct App Launch**: Swiping left on a messaging notification (in the sidebar or history) opens the chat directly in the native app.
  - **Quick Reply**: Reply to messages directly from the terminal prompt during a chat session.
- **Advanced Notification Center**:
  - **Sidebar Notifications**: Real-time notifications displayed in the right sidebar with app-specific branding (orange labels).
  - **Notification History**: Access past notifications by clicking the history icon (⏱︎).
  - **Swipe Actions**:
    - **Swipe Right**: Dismiss notification (active) or remove from history.
    - **Swipe Left (Messaging)**: Open directly in the messaging app.
    - **Enhanced Sensitivity**: Optimized swipe detection for a fluid experience.
  - **Smart Click**: Non-messaging notifications open the respective app instantly with a single tap.
- **Navigation & Media**:
  - **Media Controls**: Integrated Play/Pause controls in the sidebar, synchronized with active music notifications.
  - **Dynamic Sidebar Clock**: Parrot OS style clock (`// HH:mm`) in the sidebar; tap to open the Clock/Alarm app.
  - `maps <location>`: Opens maps with the search query pre-filled.
  - **Browser Search**: Unrecognized commands are automatically searched in your default browser or in native launcher browser.
  - **Qr Reader**: integrated qr reader.
- **Productivity & System**:
  - Screen Time: Live tracking of daily device usage displayed at the top.
  - `download`: Shortcut to the Downloads folder.
  - `clear`: Clears the terminal output for a fresh start.
  - `delete`: Clears the notification history (when in history view).
- **Interactive Setup Dashboard**:
  - `help` command provides a real-time status of all permissions.
  - Tap permission statuses ([Notifications], [Screen Time], etc.) to open relevant system settings.
