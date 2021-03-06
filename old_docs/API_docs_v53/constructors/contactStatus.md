---
title: contactStatus
description: contactStatus attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: contactStatus  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[int](../types/int.md) | Yes|
|status|[UserStatus](../types/UserStatus.md) | Optional|



### Type: [ContactStatus](../types/ContactStatus.md)


### Example:

```
$contactStatus = ['_' => 'contactStatus', 'user_id' => int, 'status' => UserStatus];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "contactStatus", "user_id": int, "status": UserStatus}
```


Or, if you're into Lua:  


```
contactStatus={_='contactStatus', user_id=int, status=UserStatus}

```


