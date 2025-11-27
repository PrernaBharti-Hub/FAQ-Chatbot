# FAQ-Chatbot
# FAQ Chatbot System 💬

A modern, fully-functional FAQ chatbot with local storage and analytics dashboard for customer support.

## 📋 Features

### Task 1: UI-Based FAQ Chatbot ✅
- **Modern Interface**: Clean, glassmorphism design with gradient backgrounds
- **Chat Window**: Smooth scrolling with animated message bubbles
- **15 Predefined FAQs**: Comprehensive responses covering:
  - Login & Account Management
  - Password Reset
  - App Crashes & Performance
  - Payment Issues
  - Profile Updates
  - Notifications
  - Data Synchronization
  - Feature Requests
  - Privacy & Security
  - Subscriptions
  - Referrals
  - And more!
- **Smart Matching**: Keyword-based response matching
- **Fallback Response**: Helpful suggestions when query isn't recognized
- **Quick Actions**: One-click common questions
- **Responsive Design**: Works on desktop, tablet, and mobile

### Task 2: Chat Storage (Local) ✅
- **localStorage Persistence**: All conversations saved automatically
- **Required Data Fields**:
  - User message
  - Bot reply
  - Timestamp (ISO format)
  - Issue category
- **Export Options**:
  - JSON format for data analysis
  - CSV format for spreadsheet tools
- **Session Continuity**: Previous chats loaded on page refresh

### Task 3: Issue Analysis & Dashboard ✅
- **Analytics Engine**: Comprehensive data analysis
- **Key Insights**:
  - Total conversations count
  - Common issues by category
  - Top complaints identification
  - Keyword frequency analysis
  - Time-based activity patterns
- **Visualizations**:
  - Bar chart for issue distribution
  - Doughnut chart for keyword frequency
  - Data table with recent conversations
- **Statistics Cards**: Quick overview metrics
- **Built with Chart.js**: Interactive, responsive charts

## 🚀 Setup & Usage

### Installation
1. Download all files to a folder
2. No build process or dependencies to install!
3. Just open `index.html` in a web browser

### Running the Application
```bash
# Navigate to the project folder
cd faq-chatbot

# Open in browser (choose one):
# Windows:
start index.html

# Mac:
open index.html

# Linux:
xdg-open index.html
```

Or simply double-click `index.html` in your file explorer.

## 🎯 How to Use

### Chatbot Interface
1. **Ask Questions**: Type your question in the input box or use quick action buttons
2. **Get Instant Answers**: Receive immediate FAQ responses
3. **Browse Suggestions**: Click common questions in the sidebar
4. **Review History**: Scroll up to see previous conversations

### Analytics Dashboard
1. **Switch to Dashboard**: Click the "Analytics" button in navigation
2. **View Statistics**: See total chats, top issues, and activity metrics
3. **Analyze Charts**: Interactive visualizations of chat patterns
4. **Review Table**: Detailed view of recent conversations

### Export Data
1. **Click "Export Data"**: Green button in navigation
2. **Choose Format**:
   - OK = JSON format
   - Cancel = CSV format
3. **File Downloaded**: `chat_history_YYYY-MM-DD.json/csv`

## 📁 Project Structure

```
faq-chatbot/
├── index.html          # Main application page
├── styles.css          # Modern UI styling
├── app.js              # Application controller
├── chatbot.js          # FAQ logic & responses
├── storage.js          # localStorage & export
├── analytics.js        # Data analysis engine
├── dashboard.js        # Chart.js visualizations
└── README.md           # This file
```

## 💡 FAQ Categories

The chatbot recognizes and categorizes the following issue types:
- 🔐 **Login**: Authentication and access issues
- 🔑 **Password**: Password reset and recovery
- 👤 **Account**: Account creation and management
- 🐛 **Crash**: App crashes and performance
- 💳 **Payment**: Billing and transaction issues
- 📝 **Profile**: Profile updates and customization
- 🔔 **Notification**: Notification settings and delivery
- 🔄 **Sync**: Data synchronization problems
- ✨ **Feature**: Feature requests and suggestions
- 🛟 **Support**: General support inquiries
- 📊 **General**: Other queries

## 🎨 Design Highlights

- **Glassmorphism**: Modern frosted glass effect
- **Gradient Backgrounds**: Vibrant color schemes
- **Smooth Animations**: CSS transitions and keyframes
- **Responsive Layout**: Mobile-first design
- **Dark Theme**: Eye-friendly color palette
- **Accessibility**: Semantic HTML and ARIA labels

## 📊 Analytics Features

### Statistics Cards
- Total conversation count
- Most common issue type
- Number of unique categories
- Last activity timestamp

### Charts
1. **Issue Distribution**: Bar chart showing category breakdown
2. **Keyword Frequency**: Doughnut chart of top keywords

### Data Table
- Recent conversations (last 20)
- Timestamp, messages, and categories
- Sortable and scrollable view

## 🗄️ Data Storage

### localStorage
- Automatic save after each conversation
- Persists across browser sessions
- No server required

### Export Formats

**JSON Example:**
```json
[
  {
    "userMessage": "How do I reset my password?",
    "botReply": "To reset your password...",
    "timestamp": "2025-11-27T02:16:38.000Z",
    "issueCategory": "password"
  }
]
```

**CSV Example:**
```csv
Timestamp,User Message,Bot Reply,Issue Category
11/27/2025 7:46 AM,"How do I reset my password?","To reset your password...",password
```

## 🔧 Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js 4.4.0 (CDN)
- **Storage**: Browser localStorage API
- **No Backend Required**: Fully client-side
- **No Build Tools**: Runs directly in browser

## 📸 Screenshots

See the application in action:
- Chatbot UI with example conversations
- Analytics dashboard with charts
- Exported data files

## 🤝 Support

For issues or questions:
- Check the FAQ responses in the chatbot
- Review the analytics dashboard
- Export and analyze your chat data

## 📝 License

This project is created for educational and demonstration purposes.

---

**Built with ❤️ for seamless customer support**
