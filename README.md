docker-megaraid_status
======================

Check status of MegaRAID controller<br />
Uses MegaCLI and check_megaraid plugin from NagiosExchange.

### Usage
```bash
docker run -privileged -i -t cpuguy83/megaraid_status
```

You must run this container with privileged mode for the status check to work.


== Notes
The included check is a simple bash script with no dependencies except MegaCLI.<br />
There are other, more comprehensive status check tools out there.<br />
Alternatively you could just run a specific MegaCLI command but this integrates well with Nagios.
