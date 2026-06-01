
# Staff Management Bot Setup

## Requirements
- Node.js 18+
- MongoDB Atlas account
- Discord Bot

## Setup

### 1. Install Node.js
Download:
https://nodejs.org/

### 2. Create a Discord Bot
Go to:
https://discord.com/developers/applications

- Create application
- Go to Bot tab
- Reset token
- Enable:
  - Message Content Intent
  - Server Members Intent

### 3. Invite Bot
OAuth2 → URL Generator:
- bot
- applications.commands

Permissions:
- Administrator

### 4. Setup MongoDB
Create free MongoDB Atlas cluster.

Copy connection URI.

### 5. Configure .env
Rename:
.env.example → .env

Fill values.

### 6. Install Dependencies
Open terminal in project folder:

npm install

### 7. Start Bot

npm start

## Features
- Tracks staff messages
- 5 second anti-spam cooldown
- Daily activity tracking
- Promotion eligibility
- Auto promotion tickets
- Activity leaderboard

## Commands
/activity
/leaderboard
/requestpromotion
