# Usage
```
usage: check_maxscale [-h] [--cli CLI] --expected-number-of-servers
                      EXPECTED_NUMBER_OF_SERVERS
                      [--expected-master EXPECTED_MASTER]
                      [--connections-threshold CONNECTIONS_THRESHOLD]
                      [--sessions-threshold SESSIONS_THRESHOLD] [--verbose]

Nagios check to monitor the MaxScale SQL proxy.

optional arguments:
  -h, --help            show this help message and exit
  --cli CLI, -i CLI     CLI command we should use (maxadmin/maxctrl) (default
                        maxadmin)
  --expected-number-of-servers EXPECTED_NUMBER_OF_SERVERS, -n EXPECTED_NUMBER_OF_SERVERS
                        Expected number of backend server
  --expected-master EXPECTED_MASTER, -m EXPECTED_MASTER
                        Expected backend master server
  --connections-threshold CONNECTIONS_THRESHOLD, -c CONNECTIONS_THRESHOLD
                        Alert if a server has more connections than this
                        threshold (default 500)
  --sessions-threshold SESSIONS_THRESHOLD, -s SESSIONS_THRESHOLD
                        Alert if there are more sessions than this threshold
                        (default 1000)
  --verbose, -v         Print detailed information
```
