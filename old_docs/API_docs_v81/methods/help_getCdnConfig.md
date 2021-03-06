---
title: help.getCdnConfig
description: Get CDN configuration
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: help.getCdnConfig  
[Back to methods index](index.md)


Get CDN configuration



### Return type: [CdnConfig](../types/CdnConfig.md)

### Can bots use this method: **YES**


### MadelineProto Example:


```
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$CdnConfig = $MadelineProto->help->getCdnConfig();
```

### [PWRTelegram HTTP API](https://pwrtelegram.xyz) example (NOT FOR MadelineProto):

### As a bot:

POST/GET to `https://api.pwrtelegram.xyz/botTOKEN/madeline`

Parameters:

* method - help.getCdnConfig
* params - `{}`



### As a user:

POST/GET to `https://api.pwrtelegram.xyz/userTOKEN/help.getCdnConfig`

Parameters:




Or, if you're into Lua:

```
CdnConfig = help.getCdnConfig({})
```

### Errors this method can return:

| Error    | Description   |
|----------|---------------|
|AUTH_KEY_PERM_EMPTY|The temporary auth key must be binded to the permanent auth key to use these methods.|
|Timeout|A timeout occurred while fetching data from the bot|


