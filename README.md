# znc-logging

## File: znc_cron_log
* Install with crontab -e as your znc user (or root, doesn't matter). This script will remove files older than 30 days (based on modify time) and also automatically gzip files older than 7 days. This is set to run at 23:00 (11:00PM) every day.

## File: znc_logrotate
* A more hands off approach, just let logrotate handle it! Compresses + removes logs older than 30 days.
