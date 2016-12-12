# hipache-healthcheck-proxy

Tool to proxy Hipache healthchecks. When running on Amazon's ALB/ELB, sending
healthcheck to Hipache is hard. This tool allows users to bind to a different
port and proxy healthchecks to the Hipache instance.
