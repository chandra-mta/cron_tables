# cron_tables
This repository stores the MTA machine cronjob tables for documentation purposes.

Note that the versions of cron tables documented in this repo might not reflect the most recent operating version of our cron job schedule allocations across MTA-used machines. Consult the cron tables on each machine directly. This is merely to store our tables external to the HEAD computer system.

## Links
- Full MTA Topology: https://docs.google.com/document/d/17Y_q7QCuko1_gyHzvrOIexY3pZfnz1zOrPnfDJBVQbk/edit?usp=sharing
- Configurable Cronjobs and Deprecation History: https://docs.google.com/spreadsheets/d/1deCRkkiAb6WL2tEobhm7fsw7wG4nKQTD6J_Zr5jmL_Y/edit?usp=sharing
- Scheduling Tool: https://crontab.guru/

## Commands

Prints all cron table entries without comments
```
crontab -l | grep '^[0-9*]' | sort -k 2g,1g
```
