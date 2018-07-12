---
title: pageBlockSubheader
description: pageBlockSubheader attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: pageBlockSubheader  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|text|[RichText](../types/RichText.md) | Yes|



### Type: [PageBlock](../types/PageBlock.md)


### Example:

```
$pageBlockSubheader = ['_' => 'pageBlockSubheader', 'text' => RichText];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "pageBlockSubheader", "text": RichText}
```


Or, if you're into Lua:  


```
pageBlockSubheader={_='pageBlockSubheader', text=RichText}

```

