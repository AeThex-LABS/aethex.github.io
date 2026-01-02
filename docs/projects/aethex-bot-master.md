# AeThex Bot Master

## Overview

AeThex Bot Master is a comprehensive Discord bot designed to provide community management, moderation, and engagement features for Discord servers. This documentation provides detailed information about the bot's capabilities, setup, and usage.

## Features

### Moderation Tools
- Automated user moderation and infractions
- Message filtering and auto-moderation
- Role management and assignment
- Ban, kick, and mute capabilities
- Audit logging for all moderation actions

### Community Management
- Welcome messages and automated member onboarding
- Custom command creation and management
- Reaction roles and member sorting
- Announcement scheduling and broadcasting
- Community engagement tracking

### User Engagement
- Leveling and experience system
- Rewards and badge system
- Member statistics and profiles
- Leaderboards and rankings
- Fun and interactive commands

### Configuration
- Flexible permission system
- Server-specific settings and customization
- Channel-specific command restrictions
- Custom prefix support
- Role-based access control

## Installation

### Prerequisites
- A Discord Server (with administrator permissions to add the bot)
- Access to the AeThex Bot Master invite link

### Steps

1. **Invite the Bot**
   - Navigate to the official bot invite link
   - Select your server from the dropdown menu
   - Grant the required permissions
   - Complete the authorization process

2. **Initial Setup**
   - The bot will create necessary roles and channels
   - Configure your server settings using the setup wizard
   - Set your preferred prefix (default: `!`)

3. **Configure Permissions**
   - Assign appropriate roles for moderation team
   - Set up admin roles and moderator roles
   - Configure channel-specific permissions as needed

## Commands

### General Commands
- `!help` - Display all available commands
- `!ping` - Check bot latency
- `!info` - Get information about the bot
- `!serverinfo` - Display server information
- `!userinfo [user]` - Display user information

### Moderation Commands
- `!warn [user] [reason]` - Warn a user
- `!mute [user] [duration]` - Mute a user
- `!unmute [user]` - Unmute a user
- `!kick [user] [reason]` - Kick a user from the server
- `!ban [user] [reason]` - Ban a user from the server
- `!unban [user]` - Unban a user
- `!modlogs [user]` - View moderation history for a user

### Leveling Commands
- `!level` - Check your current level
- `!leaderboard` - View server leaderboard
- `!stats [user]` - View user statistics

### Utility Commands
- `!prefix [new_prefix]` - Change the command prefix
- `!settings` - View current server settings
- `!configure [setting] [value]` - Modify server settings

## Configuration

### Server Settings

Use the `!configure` command to customize your server experience:

```
!configure prefix !
!configure moderation_role @Moderator
!configure welcome_channel #welcome
!configure modlogs_channel #mod-logs
```

### Logging

Enable comprehensive logging for all server activities:
- Moderation actions
- Member joins and leaves
- Role changes
- Channel updates
- Message deletions

Configure logging channels using:
```
!configure modlogs_channel #channel_name
```

## Permissions

The bot requires the following Discord permissions:
- Manage Roles
- Manage Channels
- Manage Messages
- Ban Members
- Kick Members
- Mute Members
- Read Messages/View Channels
- Send Messages
- Embed Links
- Attach Files
- Use External Emojis

## Troubleshooting

### Bot Not Responding
- Verify the bot is online in your server member list
- Check that your prefix is correct
- Ensure the bot has proper channel permissions
- Try using a mention: `@AeThex Bot Master [command]`

### Missing Permissions
- Grant the bot the required roles and permissions
- Ensure the bot's role is positioned above user roles in the role hierarchy
- Check channel-specific permission overrides

### Commands Not Working
- Verify you're using the correct prefix
- Check that the command exists with `!help`
- Ensure you have the required permissions to use the command
- Confirm the bot has permission to perform the action

## Support

For issues, questions, or feature requests:
- Visit the AeThex Labs Discord server
- Contact the support team
- Check the official documentation
- Submit issues on the project repository

## Version Information

- **Bot Version**: 1.0.0
- **Last Updated**: January 2, 2026
- **Maintained By**: AETHEX-LABS Team

## License

AeThex Bot Master is proprietary software. All rights reserved.

## Changelog

### Version 1.0.0
- Initial release
- Core moderation features
- Leveling system
- Community management tools
- User engagement features
