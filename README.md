# SSH-login-Telegram-notification
Receive notification on Telegram IM when login by SSH.

Just place the SSHRC file in /etc/ssh directory and fill in you telegram credentials.

There is a whitelist option so you can add IP addresses which are nog being reported when logged in.
The whitelist file is called whitelist.ssh and would also be placed in the sam directory.

Requirements;
- Curl
- jq

Tested on;
- Ubuntu
- Debian

But will run on many distributions.

Thing to do;

1.  Put telegram credentials in seperate file
2.  When jq is not installed, do not display error messages.
    Detailed info will be skipped in message
3.  Probably something more...
