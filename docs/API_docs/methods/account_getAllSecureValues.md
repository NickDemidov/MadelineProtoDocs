---
title: account.getAllSecureValues
description: Get all secure telegram passport values
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: account.getAllSecureValues  
[Back to methods index](index.md)


Get all secure telegram passport values



### Return type: [Vector\_of\_SecureValue](../types/SecureValue.md)

### Can bots use this method: **YES**


### MadelineProto Example:


```
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Vector_of_SecureValue = $MadelineProto->account->getAllSecureValues();
```

### [PWRTelegram HTTP API](https://pwrtelegram.xyz) example (NOT FOR MadelineProto):

### As a bot:

POST/GET to `https://api.pwrtelegram.xyz/botTOKEN/madeline`

Parameters:

* method - account.getAllSecureValues
* params - `{}`



### As a user:

POST/GET to `https://api.pwrtelegram.xyz/userTOKEN/account.getAllSecureValues`

Parameters:




Or, if you're into Lua:

```
Vector_of_SecureValue = account.getAllSecureValues({})
```

