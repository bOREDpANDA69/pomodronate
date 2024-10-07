# Pomodronate - A Chrome Extension for Enhanced Productivity

Pomodronate is a Chrome extension that implements the Pomodoro technique with integrated task management features to help users boost their productivity. It combines the power of alarms, storage, and notifications to provide an efficient, seamless experience for managing work sessions and breaks.

## 📋 Motive
The goal of Pomodronate is to:
- **Increase productivity** by breaking work into manageable time blocks using the Pomodoro technique.
- **Organize tasks** efficiently by allowing users to add, edit, and manage tasks directly within the extension.
- **Keep users informed** through notifications when a Pomodoro session or break is complete, so they can focus on tasks without distraction.

## ⚙️ Technologies Used
- **HTML, CSS, JavaScript**: For building the user interface and managing extension functionality.
- **Chrome Extensions API**:
  - **Alarms API**: Manages the Pomodoro timer and break intervals, even when the popup is closed.
  - **Storage API**: Saves and loads task lists and user preferences, ensuring continuity across sessions.
  - **Notifications API**: Sends reminders when a session or break ends to keep users on track.

## 🚀 How It Works
1. **Setup**: Users install Pomodronate from the Chrome Web Store.
2. **Adding Tasks**: Users can add tasks within the extension, which are stored using Chrome's storage API.
3. **Starting a Session**: Users click the "Start" button to begin a Pomodoro session (default 25 minutes).
4. **Background Operation**: The timer continues running using the alarms API, even when the popup is closed.
5. **Notifications**: When a session or break ends, users receive a notification, allowing them to stay informed.

## 📦 Installation
1. Clone this repository or download it as a ZIP file.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" in the top-right corner.
4. Click "Load unpacked" and select the folder containing the extension files.
5. Pomodronate should now appear in your Chrome extensions bar!

## 📚 Usage
1. Click on the Pomodronate icon to open the extension popup.
2. Add tasks and manage them in the list.
3. Start a Pomodoro session to focus on your tasks.
4. Receive notifications when a session or break is complete.

## 💡 Future Enhancements
- Customizable session and break durations.
- Integration with third-party productivity tools (e.g., Google Calendar).
- Enhanced task management features with due dates and priorities.

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.

---

**Pomodronate** - Helping you stay productive, one Pomodoro at a time! ⏰
