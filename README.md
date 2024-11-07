
# Productivity Tracker Extension

A Chrome extension that helps you track the time spent on different websites. This extension provides insights on your browsing habits, shows stats for each website, and offers productivity suggestions. Users can monitor weekly stats and set daily time goals for specific websites.

## Features

- **Website Time Tracking**: Tracks the time spent on each website and displays it in a readable format.
- **Productivity Insights**: Highlights websites where time spent exceeds set goals, allowing users to adjust their browsing habits.
- **Weekly Reports**: (Future Feature) See weekly stats for better insight into your productivity.
- **Daily Time Goals**: (Future Feature) Set daily time goals for specific websites to manage time effectively.

## Getting Started

Follow these instructions to set up and run the extension in your Chrome browser.

### Prerequisites

- **Chrome Browser**: The extension is designed for the Chrome browser.
- **React**: Developed with React, so a basic understanding of React components may help if you want to modify the code.
- **Chrome Extensions API**: Uses Chrome's Storage API to save and retrieve time-tracking data.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/productivity-tracker-extension.git
   ```
   
2. **Navigate to the project directory**:
   ```bash
   cd productivity-tracker-extension
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Build the project**:
   ```bash
   npm run build
   ```

5. **Load the extension in Chrome**:
   - Open Chrome and navigate to `chrome://extensions/`.
   - Enable **Developer mode** (toggle in the top-right corner).
   - Click **Load unpacked** and select the `build` folder from your project.

6. **Pin and Open the Extension**:
   - Pin the extension to your Chrome toolbar for quick access.
   - Click on the extension icon to start tracking your browsing time!

### Usage

- **Dashboard**: The popup displays a list of websites visited along with the time spent on each.
- **Time Format**: Time is displayed in minutes for easy readability.
- **Stay Productive**: Monitor your stats and make adjustments to spend less time on distracting sites.

## Project Structure

```
├── public/                  # Public assets
├── src/                     # Source files
│   ├── components/          # React components
│   ├── background.js        # Background script for tracking
│   ├── App.js               # Main App component
│   └── index.css            # CSS styling
├── manifest.json            # Chrome extension manifest
└── README.md                # Project documentation
```

## Contributing

If you'd like to contribute to this project:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Open a pull request.

## Future Improvements

- **Weekly Stats Dashboard**: A detailed report page to visualize productivity patterns over a week.
- **Customizable Time Goals**: Set and track specific time goals for various websites.
- **Reminders and Alerts**: Optional notifications to remind users when they exceed time goals.

---

**Stay productive and make every minute count!**
