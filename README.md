# About
PowerShell script to bypass the Cisco Packet Tracer login screen on Windows 10 & 11.

[This script](https://github.com/AlexTech0/Packet-Tracer-Login-Bypass/blob/main/bypass-pt.ps1) creates two Firewall rules (inbound and outbound) that block internet access for the Packet Tracer executable file (.exe).

## Usage
1. Make sure Execution Policy isn't set to restricted with `Get-ExecutionPolicy`.
2. Execute the script as Administrator.
3. Confirm actions.
4. If you no longer need to execute PowerShell scripts, it's recommended to set Execution Policy to 'Restricted' for better security: ```Set-ExecutionPolicy restricted```.

You can also remove this Firewall rules, to do so, execute it with `-r` or `--remove`. Notice that it'll remove the rules by their display name, if you renamed the rules, they won't be removed.

## NOTE
This script is intended for testing and educational purposes only.

I do not support any illegal use of this tool.

Use at your own risk.

## More
You can also bypass the login screen simply by disconnecting from the internet (before opening the program), after that you can connect back to the internet.
