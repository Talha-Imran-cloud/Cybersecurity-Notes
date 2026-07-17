# Active Directory Attacks

## Common AD Attacks

### Brute Force

Multiple login attempts against accounts.

### Password Spraying

One password against many accounts.

### Privilege Escalation

User becomes Administrator.

### Persistence

Attacker creates a backup account.

## Investigation Example

User created:
backup_admin

Added to:
Domain Admins

This activity should be investigated immediately.

## Important Event IDs

4720 - User Created

4728 - Added To Group

4624 - Successful Login
