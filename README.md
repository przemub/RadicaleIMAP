# ⛔️ DEPRECATED

RadicaleIMAP has been integrated into Radicale as of version 3.4.1.

This fork was created to support UTF-8 in IMAP authentication, and
the commit for that was merged to Radicale 3.5.0.

So this repo here is of use to you only if you need Radicale version
3.4.0 or less. It will conflict with Radicale 3.4.1.

# Radicale IMAP

IMAP authentication plugin for [Radicale](http://radicale.org/).

## Installation

```shell
$ python3 -m pip install --upgrade https://github.com/Unrud/RadicaleIMAP/archive/master.tar.gz
```

## Configuration

```ini
[auth]
type = radicale_imap

# IMAP server hostname
# Syntax: address
# Syntax: address:port
# Syntax: [address]:port
# For example: imap.server.tld
#imap_host =

# Secure the IMAP connection
# Value: tls | starttls | none
#imap_security = tls
```

## License

[GPL-3.0](https://github.com/Unrud/RadicaleIMAP/blob/master/COPYING)
