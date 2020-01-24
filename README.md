# checkmk-notify-teams

This is a modified version of the Slack plugin for Check_MK previously modified by RileyMichael.
Forked with intent of making the notifications more information rich in a way I needed it.

## setup

- clone / copy teams.py & put in `/omd/sites/{your_site}/local/share/check_mk/notifications`
- ensure it's executable (`chmod +x teams.py`)
- setup notification method = 'Microsoft Teams' and add your MS Teams webhook to the parameters.

## Credits

checkmk team -- this is a modified version of their slack webhook plugin
RileyMichael -- for the original modified version of the plugin
