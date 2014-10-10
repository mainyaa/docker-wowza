# docker-wowza
Wowza in docker

## Run

docker run mainyaa/wowza:4.1.0 XXXXX-XXXXX-XXXXX-XXXXX-XXXXX-XXXXX-XXXXXXXXXXXX

## Tags

- 3.6.3
- 4.1.0
- latest

## Troubleshoot

http://www.wowza.com/forums/content.php?277-How-to-troubleshoot-error-messages

```
ERROR server comment - error: java.lang.NullPointerException
ERROR: Cannot write to license key file:
  /usr/local/WowzaMediaServer/conf/Server.license
Please modify file permission to make this file writable by the server
ERROR server comment - ERROR: Cannot write to license key file:
```

**Cause:** This error is caused from using the wrong license key. For example, if you used a Wowza Media Server 2 license key with a Wowza Media Server 3 installer.
Check wowza versions in your order mail.

