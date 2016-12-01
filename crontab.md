# Crontab

Tutorial Link[http://www.unixgeeks.org/security/newbie/unix/cron-1.html]

## Commands

crontab -e # to edit your current crontab

crontab -l # to list your current crontab

crontab -r # will remove (i.e. delete) your current crontab.

crontab -u [file_name] # and then following it with either the name of a file to replace the existing user's crontab, or one of the -e, -l or -r options.

## File paths

/etc/crontab # shouldn't be edited directly

/var/spool/cron/crontabs/[user] (Unix/Slackware/*BSD)

/var/spool/cron/[user] (RedHat)

/var/cron/tabs/[user] (SuSE)