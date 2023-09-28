---
Title: My Retype Page
Layout: _layout.cshtml
---

# Discord Bot Commands

Here are the commands available for the Discord bot:

## /Confess

- **Description:** Submit anonymous confessions.
- **Usage:** `/Confess <your confession message>`
- **Example:** `/Confess I secretly love pizza.`

## /Stats

- **Description:** View detailed confession statistics.
- **Usage:** `/Stats`
- **Example:** `/Stats`

## /Report

- **Description:** Report inappropriate confessions.
- **Usage:** `/Report <confession ID>`
- **Example:** `/Report 1`

## /Admin

- **Description:** Admins configure confession channels.
- **Usage:** `/admin setup set_channels <confession_channel> <report_channel>`
- **Example:** `/admin setup set_channels #confession-channel #report-channel`

- **Description:** Admins configure confession role.
- **Usage:** `/admin setup set_role <required_role>:`
- **Example:** `/admin setup set_role @Confessor`

## /Ban User

- **Description:** Admins can ban users from confessing.
- **Usage:** `/admin moderation ban_user <user mention>`
- **Example:** `/admin moderation ban_user @baduser`

## /Unban User

- **Description:** Admins can lift confession bans.
- **Usage:** `/admin moderation unban_user <user mention>`
- **Example:** `/admin moderation unban_user @gooduser`
