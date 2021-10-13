# Request info dump

This is using httpbin server, to dump http request form client.

## Changes
1. add new view and logger in [core.py](httpbin/core.py#L1780).
2. add debug flag and logger format, example [docker-compose.yml](docker-compose.yml#L7)