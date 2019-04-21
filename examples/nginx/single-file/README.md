# Nginx Single-File Configuration Examples


| File                      | Description |
| :---                      | :---        |
| nginx_basic.conf          | The basic nginx configuration example.   Provides authentication for an app at https://dev.yourdomain.com |
| nginx_with_vouch.conf     | Builds on the basic example by adding a proxy (port 80) for vouch to a vouch instance on localhost.  |
| nginx-with_vouch_ssl.conf | Builds on the basic example by adding a proxy (port 443) for vouch using https to a vouch instance on localhost.  This configuration supports secure cookies. |