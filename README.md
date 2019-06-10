# NGINX Error Pages

Make your error pages look great! Usually self-contained.

## Installation

```
$ ./generate
```

Then within each of your server blocks / vhosts, add the following snippet:

```
include output/error_pages.conf;
```

## HTTP Status Codes

The `http-status-code.json` was downloaded from:

http://webconcepts.info/concepts/http-status-code.json
