# Privacy Policy for QuasarBot

**Last Updated: June 29, 2026**

## 1. Introduction

This Privacy Policy explains how QuasarBot ("the Bot", "we", "our") collects, uses, and protects information when you use our Discord bot. By using QuasarBot, you agree to the data practices described in this policy.

## 2. Information We Collect

### 2.1 Automatically Collected Data
When you interact with QuasarBot, we automatically collect:
- **Discord User ID** - Used to identify your account for alliance tracking
- **Discord Server (Guild) ID** - Used to store server-specific settings
- **Message IDs** - Used for advertisement tracking features
- **Command Usage** - Which commands you use and when

### 2.2 Data You Provide
- **Custom Prefixes** - Server administrators can set custom command prefixes
- **Auto Responder Triggers/Responses** - Configured by server administrators
- **Channel/Role IDs** - Configured by server administrators for bot functionality

## 3. How We Use Your Information

We use collected data for:
- **Bot Functionality** - Alliance management, auto responders, and server management
- **Server Configuration** - Storing your server's custom settings
- **Advertisement Tracking** - Tracking representative mentions in ad channels
- **Auto-Moderation** - J2L (Join-to-Leave) system for auto-banning

## 4. Data Storage

### 4.1 Database Storage
All data is stored in a secure PostgreSQL/SQLite database. Data includes:
- Server configurations
- Advertisement tracking records
- Auto responder configurations
- Command cooldowns (temporary)

### 4.2 Data Retention
- **Permanent Data**: Server configurations, auto responder settings
- **Temporary Data**: Command cooldowns - automatically cleaned after 7 days
- **Advertisement Mentions**: Stored until the user leaves the server

## 5. Data Sharing

We do NOT:
- Sell your data to third parties
- Share your data with advertisers
- Use your data for purposes outside bot functionality
- Export personal data without owner authorization

## 6. User Rights

You have the right to:
- **Delete** - Server admins can reset server data using `reset_guild` command
- **Opt-out** - Stop using the bot at any time
- **Data Export** - Bot owner can export database for backup purposes

## 7. Security

We implement security measures including:
- Database connection encryption
- Secure environment variables for sensitive tokens
- Input validation to prevent injection attacks
- Rate limiting to prevent abuse

## 8. Contact Information

If you have questions about this Privacy Policy, you can:
- Contact the bot owner through Discord
- Join our support server

---

**By using QuasarBot, you acknowledge that you have read and understood this Privacy Policy.**
