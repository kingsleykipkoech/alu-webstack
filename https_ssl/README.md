# HTTPS SSL

This project covers SSL/TLS encryption, setting up subdomains, SSL termination on HAProxy, and enforcing HTTPS redirection.

## Tasks

- **0-world_wide_web**: Bash script that audits DNS records for subdomains using dig and awk.
- **1-haproxy_ssl_termination**: HAProxy configuration terminating SSL on port 443.
- **2-redirect_http_to_https**: HAProxy configuration enforcing HTTP to HTTPS 301 redirection.
