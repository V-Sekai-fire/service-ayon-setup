# service-ayon-setup

A task schedule, kept as SQLite databases, for standing up a production-tracking server and connecting artist workstations to it.

## What it is for

`docs/schedule.db` lists the setup steps in priority order, from the server through project
configuration to the workstation launcher and the 3D application integrations, with estimated
and elapsed hours for each. The archived and completed databases hold steps once they are set
aside or done.

## Use

```sh
sqlite3 docs/schedule.db 'select * from schedule'
```

## Licence

This repository does not state a licence.
