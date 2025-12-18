# 🤖 Quiz Poll Bot

A powerful Telegram bot that automatically sends quiz polls to multiple groups with advanced management features, MongoDB support, and sudo user system.

## 🌟 Features

### 🎯 Core Functionality
- **Auto Quiz Sending**: Automatically sends random quiz polls to all groups at configurable intervals
- **Manual Quiz Sending**: Group admins can use `/rquiz` for immediate quizzes
- **Quiz Mode Support**: Only accepts Telegram's QUIZ MODE polls with correct answers
- **Anti-Repeat System**: Advanced algorithm to avoid sending the same quizzes repeatedly
- **Non-Anonymous Voting**: Always sends quizzes as non-anonymous (voters visible)

### 👑 Admin & Sudo System
- **Admin Dashboard**: Full control panel with inline keyboard
- **Sudo Users**: Multiple privileged users with same rights as admin (except sudo management)
- **Secure Access**: Only bot owner can add/remove sudo users

### 📊 Management & Analytics
- **Real-time Statistics**: Detailed analytics on quizzes, groups, and engagement
- **Group Management**: Auto-registration and manual group control
- **Data Export**: Export quizzes, groups, and stats to CSV/JSON
- **Broadcast System**: Send announcements to all groups

### 💾 Database & Storage
- **MongoDB Support**: Persistent storage with MongoDB
- **In-Memory Fallback**: Works without database connection
- **Data Persistence**: All data survives bot restarts

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- MongoDB (optional, but recommended)
- Telegram Bot Token from [@BotFather](https://t.me/BotFather)

### Installation

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd quiz-poll-bot
