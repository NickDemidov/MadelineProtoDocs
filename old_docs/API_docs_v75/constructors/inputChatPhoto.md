---
title: inputChatPhoto
description: inputChatPhoto attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputChatPhoto  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[MessageMedia, Message, Update or InputPhoto](../types/InputPhoto.md) | Optional|



### Type: [InputChatPhoto](../types/InputChatPhoto.md)


### Example:

```
$inputChatPhoto = ['_' => 'inputChatPhoto', 'id' => InputPhoto];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputChatPhoto", "id": InputPhoto}
```


Or, if you're into Lua:  


```
inputChatPhoto={_='inputChatPhoto', id=InputPhoto}

```

