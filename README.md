# HTTPS SSL

Scripts and HAProxy configuration for the ALU HTTPS SSL project.

| File | Purpose |
| --- | --- |
| `https_ssl/0-world_wide_web` | Audit the www, lb-01, web-01 and web-02 DNS records of a domain. |
| `https_ssl/1-haproxy_ssl_termination` | HAProxy config terminating SSL for www on port 443. |
| `https_ssl/2-redirect_http_to_https` | Same config, plus a 301 redirect from HTTP to HTTPS. |
