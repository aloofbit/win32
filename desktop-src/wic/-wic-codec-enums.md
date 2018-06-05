---
Description: This section contains information about the Windows Imaging Component (WIC) constants, enumerations, and flags.
ms.assetid: a3f44919-bd55-48cf-9dc6-37de0059a639
title: Constants, Enumerations, and Flags
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Constants, Enumerations, and Flags

This section contains information about the Windows Imaging Component (WIC) constants, enumerations, and flags.

## In this section



| Topic                                                                                                              | Description                                                                                                                                                     |
|--------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [WIC GUIDs and CLSIDs](-wic-guids-clsids.md)<br/>                                                           |                                                                                                                                                                 |
| [Codec Error Codes](-wic-codec-error-codes.md)<br/>                                                         |                                                                                                                                                                 |
| [Native Pixel Formats](-wic-codec-native-pixel-formats.md)<br/>                                             | This topic introduces the pixel formats provided by the WIC<br/>                                                                                          |
| [**IWICDevelopRawNotificationCallback Constants**](-wic-codec-iwicdeveloprawnotification-constants.md)<br/> | Flags used to by [**IWICDevelopRawNotificationCallback**](/windows/desktop/api/Wincodec/nn-wincodec-iwicdeveloprawnotificationcallback) to indicate which members have changed.<br/> |
| [**IWICJpegFrameDecode Constants**](iwicjpegframedecode-constants.md)<br/>                                  | Flags used by the [**WICJpegScanHeader**](/windows/desktop/api/wincodec/ns-wincodec-wicjpegscanheader) and [**WICJpegFrameHeader**](/windows/desktop/api/wincodec/ns-wincodec-wicjpegframeheader).<br/>                               |
| [**WIC8BIMIptcDigestProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wic8bimiptcdigestproperties)<br/>                           | Specifies the identifiers of the metadata items in an 8BIM IPTC digest metadata block.<br/>                                                               |
| [**WIC8BIMIptcProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wic8bimiptcproperties)<br/>                                       | Specifies the identifiers of the metadata items in an 8BIM IPTC block.<br/>                                                                               |
| [**WIC8BIMResolutionInfoProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wic8bimresolutioninfoproperties)<br/>                   | Specifies the identifiers of the metadata items in an 8BIMResolutionInfo block.<br/>                                                                      |
| [**WICBitmapAlphaChannelOption**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmapalphachanneloption)<br/>                           | Specifies the desired alpha channel usage.<br/>                                                                                                           |
| [**WICBitmapCreateCacheOption**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmapcreatecacheoption)<br/>                             | Specifies the desired cache usage.<br/>                                                                                                                   |
| [**WICBitmapDecoderCapabilities**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmapdecodercapabilities)<br/>                         | Specifies the capabilities of the decoder.<br/>                                                                                                           |
| [**WICBitmapDitherType**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmapdithertype)<br/>                                           | Specifies the type of [dither](#term-dither) algorithm to apply when converting between image formats.<br/>                                               |
| [**WICBitmapEncoderCacheOption**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmapencodercacheoption)<br/>                           | Specifies the cache options available for an encoder.<br/>                                                                                                |
| [**WICBitmapInterpolationMode**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmapinterpolationmode)<br/>                             | Specifies the sampling or filtering mode to use when scaling an image.<br/>                                                                               |
| [**WICBitmapLockFlags**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmaplockflags)<br/>                                             | Specifies access to an [**IWICBitmap**](/windows/desktop/api/Wincodec/nn-wincodec-iwicbitmap).<br/>                                                                                  |
| [**WICBitmapPaletteType**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmappalettetype)<br/>                                         | Specifies the type of palette used for an indexed image format.<br/>                                                                                      |
| [**WICBitmapTransformOptions**](/windows/desktop/api/Wincodec/ne-wincodec-wicbitmaptransformoptions)<br/>                               | Specifies the flip and rotation transforms.<br/>                                                                                                          |
| [**WICColorContextType**](/windows/desktop/api/Wincodec/ne-wincodec-wiccolorcontexttype)<br/>                                           | Specifies the color context types.<br/>                                                                                                                   |
| [**WICComponentEnumerateOptions**](/windows/desktop/api/Wincodec/ne-wincodec-wiccomponentenumerateoptions)<br/>                         | Specifies component enumeration options.<br/>                                                                                                             |
| [**WICComponentSigning**](/windows/desktop/api/Wincodec/ne-wincodec-wiccomponentsigning)<br/>                                           | Specifies the component signing status.<br/>                                                                                                              |
| [**WICComponentType**](/windows/desktop/api/Wincodec/ne-wincodec-wiccomponenttype)<br/>                                                 | Specifies the type of WIC component.<br/>                                                                                                                 |
| [**WICDecodeOptions**](/windows/desktop/api/Wincodec/ne-wincodec-wicdecodeoptions)<br/>                                                 | Specifies decode options.<br/>                                                                                                                            |
| [**WICDdsDimension**](/windows/desktop/api/Wincodec/ne-wincodec-wicddsdimension)<br/>                                                              | Specifies the dimension type of the data contained in DDS image.<br/>                                                                                     |
| [**WICDdsAlphaMode**](/windows/desktop/api/Wincodec/ne-wincodec-wicddsalphamode)<br/>                                                              | Specifies the the meaning of pixel color component values contained in the DDS image.<br/>                                                                |
| [**WICGifApplicationExtensionProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicgifapplicationextensionproperties)<br/>         | Specifies the application extension metadata properties for a Graphics Interchange Format (GIF) image.<br/>                                               |
| [**WICGifCommentExtensionProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicgifcommentextensionproperties)<br/>                 | Specifies the comment extension metadata properties for a GIF image.<br/>                                                                                 |
| [**WICGifGraphicControlExtensionProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicgifgraphiccontrolextensionproperties)<br/>   | Specifies the graphic control extension metadata properties that define the transitions between each frame animation for GIF images.<br/>                 |
| [**WICGifImageDescriptorProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicgifimagedescriptorproperties)<br/>                   | Specifies the image descriptor metadata properties for GIF frames.<br/>                                                                                   |
| [**WICGifLogicalScreenDescriptorProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicgiflogicalscreendescriptorproperties)<br/>   | Specifies the logical screen descriptor properties for GIF metadata.<br/>                                                                                 |
| [**WICJpegCommentProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicjpegcommentproperties)<br/>                                 | Specifies the JPEG comment properties.<br/>                                                                                                               |
| [**WICJpegChrominanceProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicjpegchrominanceproperties)<br/>                         | Specifies the JPEG chrominance table property.<br/>                                                                                                       |
| [**WICJpegIndexingOptions**](/windows/desktop/api/wincodec/ne-wincodec-wicjpegindexingoptions)<br/>                                                | Specifies the options for indexing a JPEG image. <br/>                                                                                                    |
| [**WICJpegLuminanceProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicjpegluminanceproperties)<br/>                             | Specifies the JPEG luminance table property.<br/>                                                                                                         |
| [**WICJpegScanType**](/windows/desktop/api/wincodec/ne-wincodec-wicjpegscantype)<br/>                                                              | Specifies the memory layout of pixel data in a JPEG image scan. <br/>                                                                                     |
| [**WICJpegTransferMatrix**](/windows/desktop/api/wincodec/ne-wincodec-wicjpegtransfermatrix)<br/>                                                  | Specifies conversion matrix from Y'Cb'Cr' to R'G'B'. <br/>                                                                                                |
| [**WICJpegYCrCbSubsamplingOption**](/windows/desktop/api/Wincodec/ne-wincodec-wicjpegycrcbsubsamplingoption)<br/>                       | Specifies the JPEG YCrCB subsampling options. <br/>                                                                                                       |
| [**WICMetadataCreationOptions**](/windows/desktop/api/Wincodecsdk/ne-wincodecsdk-wicmetadatacreationoptions)<br/>                             | Specifies metadata creation options.<br/>                                                                                                                 |
| [**WICNamedWhitePoint**](/windows/desktop/api/Wincodec/ne-wincodec-wicnamedwhitepoint)<br/>                                             | Specifies named white balances for raw images.<br/>                                                                                                       |
| [**WICPersistOptions**](/windows/desktop/api/Wincodecsdk/ne-wincodecsdk-wicpersistoptions)<br/>                                               | Specifies WIC options that are used when initializing a component with a stream.<br/>                                                                     |
| [**WICPixelFormatNumericRepresentation**](/windows/desktop/api/Wincodec/ne-wincodec-wicpixelformatnumericrepresentation)<br/>           |                                                                                                                                                                 |
| [**WICPlanarOptions**](/windows/desktop/api/Wincodec/ne-wincodec-wicplanaroptions)<br/>                                                            | Specifies additional options to an [**IWICPlanarBitmapSourceTransform**](/windows/desktop/api/Wincodec/nn-wincodec-iwicplanarbitmapsourcetransform) implementation. <br/>                       |
| [**WICProgressOperation**](/windows/desktop/api/Wincodec/ne-wincodec-wicprogressoperation)<br/>                                         | Specifies the progress operations to receive notifications for.<br/>                                                                                      |
| [**WICPngBkgdProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpngbkgdproperties)<br/>                                         | Specifies the Portable Network Graphics (PNG) background (bKGD) chunk metadata properties.<br/>                                                           |
| [**WICPngChrmProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpngchrmproperties)<br/>                                         | Specifies the PNG cHRM chunk metadata properties for CIE XYZ chromaticity.<br/>                                                                           |
| [**WICPngFilterOption**](/windows/desktop/api/Wincodec/ne-wincodec-wicpngfilteroption)<br/>                                             | Specifies the PNG filters available for compression optimization.<br/>                                                                                    |
| [**WICPngGamaProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpnggamaproperties)<br/>                                         | Specifies the PNG gAMA chunk metadata properties.<br/>                                                                                                    |
| [**WICPngHistProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpnghistproperties)<br/>                                         | Specifies the PNG hIST chunk metadata properties.<br/>                                                                                                    |
| [**WICPngIccpProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpngiccpproperties)<br/>                                         | Specifies the PNG iCCP chunk metadata properties.<br/>                                                                                                    |
| [**WICPngItxtProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpngitxtproperties)<br/>                                         | Specifies the PNG iTXT chunk metadata properties.<br/>                                                                                                    |
| [**WICPngSrgbProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpngsrgbproperties)<br/>                                         | Specifies the PNG sRGB chunk metadata properties.<br/>                                                                                                    |
| [**WICPngTimeProperties**](/windows/desktop/api/Wincodec/ne-wincodec-wicpngtimeproperties)<br/>                                         | Specifies the PNG tIME chunk metadata properties.<br/>                                                                                                    |
| [**WICProgressNotification**](/windows/desktop/api/Wincodec/ne-wincodec-wicprogressnotification)<br/>                                   | Specifies when the progress notification callback should be called.<br/>                                                                                  |
| [Native WIC Codecs](native-wic-codecs.md)<br/>                                                              | This section contains information about the native imaging codecs available in WIC.<br/>                                                                  |
| [**WICRawCapabilities**](/windows/desktop/api/Wincodec/ne-wincodec-wicrawcapabilities)<br/>                                             | Specifies the capability support of a raw image.<br/>                                                                                                     |
| [**WICRawParameterSet**](/windows/desktop/api/Wincodec/ne-wincodec-wicrawparameterset)<br/>                                             | Specifies the parameter set used by a raw codec.<br/>                                                                                                     |
| [**WICRawRenderMode**](/windows/desktop/api/Wincodec/ne-wincodec-wicrawrendermode)<br/>                                                 | Specifies the render intent of the next [**CopyPixels**](/windows/desktop/api/Wincodec/nf-wincodec-iwicbitmapsource-copypixels) call. <br/>                                          |
| [**WICRawRotationCapabilities**](/windows/desktop/api/Wincodec/ne-wincodec-wicrawrotationcapabilities)<br/>                             | Specifies the rotation capabilities of the codec.<br/>                                                                                                    |
| [**WICSectionAccessLevel**](/windows/desktop/api/Wincodec/ne-wincodec-wicsectionaccesslevel)<br/>                                       | Specifies the access level of a Windows Graphics Device Interface (GDI) section.<br/>                                                                     |
| [**WICTiffCompressionOption**](/windows/desktop/api/Wincodec/ne-wincodec-wictiffcompressionoption)<br/>                                 | Specifies the Tagged Image File Format (TIFF) compression options.<br/>                                                                                   |



 

 

 



