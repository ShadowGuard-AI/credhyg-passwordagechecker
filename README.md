![Banner](banner.png)

# credhyg-PasswordAgeChecker
A command-line tool that checks the age of passwords stored in a specified file (e.g., a KeePass database export). It alerts the user if any password exceeds a configurable age threshold, encouraging password rotation. Alerts and error messages name the account, username, and row number only: a password value is never printed, including for malformed rows and rows with a bad date. - Focused on Tools for identifying and remediating credential leaks, insecure storage, and weak password policies. Checks for exposed API keys, default passwords, and password strength.

## Install
`git clone https://github.com/ShadowStrikeHQ/credhyg-passwordagechecker`

## Usage
`./credhyg-passwordagechecker [params]`

## Parameters
- `-h`: Show help message and exit
- `--max_age`: No description provided
- `--date_format`: No description provided
- `--log_level`: No description provided

## License
Copyright (c) ShadowStrikeHQ
