---
title: venue
description: Describes venue
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: venue  
[Back to constructors index](index.md)



Describes venue

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|location|[location](../constructors/location.md) | Yes|Venue location as defined by sender|
|title|[string](../types/string.md) | Yes|Venue name as defined by sender|
|address|[string](../types/string.md) | Yes|Venue address as defined by sender|
|provider|[string](../types/string.md) | Yes|Provider of venue database as defined by sender. Only "foursquare" need to be supported currently|
|id|[string](../types/string.md) | Yes|Identifier of the venue in provider database as defined by sender|



### Type: [Venue](../types/Venue.md)


