# hipache-healthcheck-proxy

Tool to proxy Hipache healthchecks. When running on Amazon's ALB/ELB, sending
healthcheck to Hipache is hard. This tool allows users to bind to a different
port and proxy healthchecks to the Hipache instance.

## Usage

In order to use it, just set the environment variable ``HIPACHE_ADDRESS`` and
start it:

```
% export HIPACHE_ADDRESS=http://localhost:8080
% ./hipache-healthcheck-proxy
2016/12/12 14:02:50 starting on :9000...
```
