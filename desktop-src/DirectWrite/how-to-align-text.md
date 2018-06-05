---
title: How to Align Text
description: You can align DirectWrite text by using the SetTextAlignment method of the IDWriteTextFormat interface.
ms.assetid: 7f79dcff-11f6-4e74-b5bd-98bfebe6e393
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# How to Align Text

You can align [DirectWrite](direct-write-portal.md) text by using the [**SetTextAlignment**](/windows/desktop/api/dwrite/) method of the [**IDWriteTextFormat**](/windows/desktop/api/dwrite/) interface, as shown in the following code that centers the text.


```C++
if (SUCCEEDED(hr))
{
    hr = pTextFormat_->SetTextAlignment(DWRITE_TEXT_ALIGNMENT_CENTER);
}
```



The text can be aligned to the leading or trailing edge of the layout box, or it can be centered. The following illustration shows text with the alignment set to [**DWRITE\_TEXT\_ALIGNMENT\_LEADING**](/windows/desktop/api/dwrite/ne-dwrite-dwrite_text_alignment), [**DWRITE\_TEXT\_ALIGNMENT\_CENTER**](/windows/desktop/api/dwrite/ne-dwrite-dwrite_text_alignment), and [**DWRITE\_TEXT\_ALIGNMENT\_TRAILING**](/windows/desktop/api/dwrite/ne-dwrite-dwrite_text_alignment), respectively.

![illustration of text paragraphs with leading, centered, and trailing alignment](images/textalignment.png)

> [!Note]  
> The alignment is dependent on reading direction, the above is for left-to-right reading direction. For right-to-left reading direction it would be the opposite.

 

An [**IDWriteTextLayout**](/windows/desktop/api/dwrite/) object will use the alignment that has been designated for the [**IDWriteTextFormat**](/windows/desktop/api/dwrite/) provided by you when creating the layout. To change the text alignment, use [**IDWriteTextLayout::SetTextAlignment**](/windows/desktop/api/dwrite/).

 

 



