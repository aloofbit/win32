---
title: GetFcpPersistentBinding\_IN structure
description: The GetFcpPersistentBinding\_IN structure is used to pass input parameter data to the GetFcpPersistentBinding WMI method
ms.assetid: b08354c8-ef4e-4330-8a3b-dcfe3a722a5d
keywords:
- GetFcpPersistentBinding_IN structure Storage Devices
- PGetFcpPersistentBinding_IN structure pointer Storage Devices
topic_type:
- apiref
api_name:
- GetFcpPersistentBinding_IN
api_location:
- hbapiwmi.h
api_type:
- HeaderDef
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: structure
ms.date: 05/31/2018
---

# GetFcpPersistentBinding\_IN structure

The GetFcpPersistentBinding\_IN structure is used to pass input parameter data to the [**GetFcpPersistentBinding**](https://msdn.microsoft.com/library/windows/hardware/ff553966) WMI method

## Syntax


```C++
typedef struct _GetFcpPersistentBinding_IN {
  ULONG InEntryCount;
} GetFcpPersistentBinding_IN, *PGetFcpPersistentBinding_IN;
```



## Members

<dl> <dt>

**InEntryCount**
</dt> <dd>

Indicates the number of binding entries that will fit in the buffer that the WMI client provides when it calls the [**GetFcpPersistentBinding**](https://msdn.microsoft.com/library/windows/hardware/ff553966) WMI method.

</dd> </dl>

## Remarks

The WMI tool suite generates a declaration of the GetFcpPersistentBinding\_IN structure in *Hbapiwmi.h* when it compiles the [MSFC\_HBAFCPInfo WMI Class](https://msdn.microsoft.com/library/windows/hardware/ff562509).

## Requirements



|                   |                                                                                                            |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Hbapiwmi.h (include Hbapiwmi.h)</dt> </dl> |



## See also

<dl> <dt>

[**GetFcpPersistentBinding**](https://msdn.microsoft.com/library/windows/hardware/ff553966)
</dt> <dt>

[MSFC\_HBAFCPInfo WMI Class](https://msdn.microsoft.com/library/windows/hardware/ff562509)
</dt> </dl>

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bstorage\storage%5D:%20GetFcpPersistentBinding_IN%20structure%20%20RELEASE:%20%283/29/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")





