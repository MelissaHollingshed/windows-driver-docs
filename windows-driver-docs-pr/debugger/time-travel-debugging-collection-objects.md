---
title: TTD Collection Objects
description: This section describes the range model objects associated with time travel debugging.
ms.author: windowsdriverdev
ms.date: 09/25/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
ms.localizationpriority: medium
---

> [!NOTE]
> The information in this topic is preliminary. Updated information will be provided in a later release of the documentation. 
>

# TTD Collection Objects
## Description
*TBD.

## Children

TODO 

| Object | Description |
| --- | --- |
| MinPosition | A [position object](time-travel-debugging-position-objects.md) that describes the earliest position relevant to the range. |




### TTD Collection Object Methods

- ToDo - Move to table?

**Contains(OtherString)** -Method which returns whether the string contains a given sub string.

**EndsWith(OtherString)** -Method which returns whether the string ends with a given string.

**IndexOf(OtherString)** -Method which returns the index of the first occurrence of a substring in the given string.  If no such occurrence exists, -1 is returned.

**LastIndexOf(OtherString)** -Method which returns the index of the last occurrence of a substring in the given string.  If no such occurrence exists, -1 is returned.

**Length** - Property which returns the length of the string.

**PadLeft(TotalWidth)** - Method which right aligns the string to the specified width by inserting spaces at the left of the string.

**PadRight(TotalWidth)** - Method which left aligns the string to the specified width by inserting spaces at the right of the string.

**Remove(StartPos, [Length])** - Method which removes all characters beginning at the specified position from the string.  If an optional length is supplied, only that many characters after the starting position are removed.

**Replace(SearchString, ReplaceString)** - Method which replaces every occurrence of a specified search string with a replacement string.

**StartsWith(OtherString)** - Method which returns whether the string starts with a given string.

**Substring(StartPos, [Length])** - Method which retrieves a substring from the given string.  The substring starts at a specified character position and continues to the end of the string or for the optionally specified length.

**ToLower()** - Returns a copy of this string converted to lowercase.

**ToUpper()** - Returns a copy of this string converted to uppercase.

## Example Usage

*Information pending*



## See Also

[Time Travel Debugging - Introduction to Time Travel Debugging objects](time-travel-debugging-object-model.md)

[Time Travel Debugging - Overview](time-travel-debugging-overview.md)

---


