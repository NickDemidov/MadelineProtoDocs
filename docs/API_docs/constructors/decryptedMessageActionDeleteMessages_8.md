---
title: decryptedMessageActionDeleteMessages
description: decryptedMessageActionDeleteMessages attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: decryptedMessageActionDeleteMessages\_8  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|random\_ids|Array of [long](../types/long.md) | Yes|



### Type: [DecryptedMessageAction](../types/DecryptedMessageAction.md)


### Example:

```
$decryptedMessageActionDeleteMessages_8 = ['_' => 'decryptedMessageActionDeleteMessages', 'random_ids' => [long, long]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "decryptedMessageActionDeleteMessages", "random_ids": [long]}
```


Or, if you're into Lua:  


```
decryptedMessageActionDeleteMessages_8={_='decryptedMessageActionDeleteMessages', random_ids={long}}

```


