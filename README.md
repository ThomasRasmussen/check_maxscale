# Usage
```
usage: check_maxscale [-h] --expected-number-of-servers
                      EXPECTED_NUMBER_OF_SERVERS
                      [--connections-threshold CONNECTIONS_THRESHOLD]
                      [--sessions-threshold SESSIONS_THRESHOLD] [--verbose]

Nagios check to monitor the MaxScale SQL proxy.

optional arguments:
  -h, --help            show this help message and exit
  --expected-number-of-servers EXPECTED_NUMBER_OF_SERVERS, -n EXPECTED_NUMBER_OF_SERVERS
                        Expected number of backend server
  --connections-threshold CONNECTIONS_THRESHOLD
                        Alert if a server has more connections than this
                        threshold (default 500)
  --sessions-threshold SESSIONS_THRESHOLD
                        Alert if there are more sessions than this threshold
                        (default 1000)
  --verbose, -v         Print detailed information
```
