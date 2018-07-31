---
Description: The following interfaces are declared in vspixengine.h.
MS-HAID: vspixengine.vspixengine\_interfaces
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/desktop
title: Direct3D Diagnostics Capture Interfaces
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# <span id="vspixengine.vspixengine_interfaces"></span>Direct3D Diagnostics Capture Interfaces

The following interfaces are declared in vspixengine.h.

## <span id="in_this_section"></span>In this section

<table><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup><thead><tr class="header"><th>Topic</th><th>Description</th></tr></thead><tbody><tr class="odd"><td><p>[<strong>INewFramesCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422690)</p></td><td><p>Callback from engine indicating that it is done parsing any new frames added to the log.</p></td></tr><tr class="even"><td><p>[<strong>IPixCancelableRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432734)</p></td><td><p>Base of any request that can be canceled. Canceled requests can only be canceled if they are still in the queue, so a cancelation may be ignored.</p></td></tr><tr class="odd"><td><p>[<strong>IPixErrorCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432784)</p></td><td><p>Callback from engine to handle errors.</p></td></tr><tr class="even"><td><p>[<strong>IPixProgressCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432788)</p></td><td><p>Callback from engine to return progress.</p></td></tr><tr class="odd"><td><p>[<strong>IPixelHistoryCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432735)</p></td><td><p>Not used. Formerly a callback to return all pixel history results at once.</p></td></tr><tr class="even"><td><p>[<strong>IPixelHistoryRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432740)</p></td><td><p>Not used. Formerly a request for pixel history primitives and intersections together.</p></td></tr><tr class="odd"><td><p>[<strong>IPixelHistoryCallback2</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432736)</p></td><td><p>Callback to return pixel history intersections (draw call level) and primitives (triangle level) in two different results.</p></td></tr><tr class="even"><td><p>[<strong>IPixelHistoryRequest2</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432741)</p></td><td><p>Request for pixel history intersections and primitives separately.</p></td></tr><tr class="odd"><td><p>[<strong>IFrameBufferCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422668)</p></td><td><p>Callback to return a render target. The format of the returned render target is R8G8B8A8_UNORM regardless of the format of the in-engine rendertarget.</p></td></tr><tr class="even"><td><p>[<strong>IFrameBufferRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422670)</p></td><td><p>Callback to request a render target.</p></td></tr><tr class="odd"><td><p>[<strong>IDebugShaderRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422660)</p></td><td><p>Not used. Formerly a request to start debugging a shader.</p></td></tr><tr class="even"><td><p>[<strong>IDebugShaderCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422656)</p></td><td><p>Callback to return the instructions generated from creating a shader trace.</p></td></tr><tr class="odd"><td><p>[<strong>IDebugShaderRequest2</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422661)</p></td><td><p>Request to start debugging a shader. This request contains two parts: generate a trace, and debug a trace.</p></td></tr><tr class="even"><td><p>[<strong>IDebugShaderCancel</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422658)</p></td><td><p>Request to cancel generating a shader trace.</p></td></tr><tr class="odd"><td><p>[<strong>IDebugLiveShaderRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422654)</p></td><td><p>Reserved. Request to live debug a shader.</p></td></tr><tr class="even"><td><p>[<strong>IGenericBufferDataCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422682)</p></td><td><p>Callback to return the contents of an object in XML form.</p></td></tr><tr class="odd"><td><p>[<strong>IGenericBufferDataRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422684)</p></td><td><p>Request for the contents of an object in XML form.</p></td></tr><tr class="even"><td><p>[<strong>IBufferObjectDataCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422646)</p></td><td><p>Callback to return the contents of an object in buffer form for those that support it (buffers, textures).</p></td></tr><tr class="odd"><td><p>[<strong>IBufferObjectDataRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422648)</p></td><td><p>Request for the contents of an object in buffer form for those that support it.</p></td></tr><tr class="even"><td><p>[<strong>ITextureCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432815)</p></td><td><p>Callback to write a texture as a DDS file.</p></td></tr><tr class="odd"><td><p>[<strong>ITextureRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432817)</p></td><td><p>Request for a texture to be written as a DDS file.</p></td></tr><tr class="even"><td><p>[<strong>ITileRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432819)</p></td><td><p>Request for a tiled texture to be written as a DDS file.</p></td></tr><tr class="odd"><td><p>[<strong>IPipeLineStagesCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432716)</p></td><td><p>Not used. Formerly a callback for pipeline stages data.</p></td></tr><tr class="even"><td><p>[<strong>IPipeLineStagesCallback2</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432717)</p></td><td><p>Not used. Formerly a callback for pipeline stages data.</p></td></tr><tr class="odd"><td><p>[<strong>IPipeLineStagesCallback3</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432720)</p></td><td><p>Callback for pipeline stages data.</p></td></tr><tr class="even"><td><p>[<strong>IPipeLineStagesRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432726)</p></td><td><p>Not used. Formerly a request for pipeline stages data.</p></td></tr><tr class="odd"><td><p>[<strong>IPipeLineStagesRequest2</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432727)</p></td><td><p>Not used. Formerly a request for pipeline stages data.</p></td></tr><tr class="even"><td><p>[<strong>IPipeLineStagesRequest3</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432730)</p></td><td><p>Request for pipeline stages data.</p></td></tr><tr class="odd"><td><p>[<strong>ICallStackCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422650)</p></td><td><p>Callback to return callstack data.</p></td></tr><tr class="even"><td><p>[<strong>ICallStackRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422652)</p></td><td><p>Request for callstack data.</p></td></tr><tr class="odd"><td><p>[<strong>ISymbolSettings</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432813)</p></td><td><p>Passes symbol server information to the desktop capture engine.</p></td></tr><tr class="even"><td><p>[<strong>ISourceFileInfoCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432802)</p></td><td><p>Callback to return source file info from a callstack.</p></td></tr><tr class="odd"><td><p>[<strong>ISourceFileInfoRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432804)</p></td><td><p>Request for source file info from a callstack.</p></td></tr><tr class="even"><td><p>[<strong>IRunExperimentCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432794)</p></td><td><p>Callback to return errors from the engine during capture.</p></td></tr><tr class="odd"><td><p>[<strong>IRunActionCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432790)</p></td><td><p>Not used. Formerly a callback to respond to &quot;capture frame&quot; event.</p></td></tr><tr class="even"><td><p>[<strong>IRunActionRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432792)</p></td><td><p>Not used. Formerly a request for things like &quot;capture frame&quot; event.</p></td></tr><tr class="odd"><td><p>[<strong>IFrameListCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422678)</p></td><td><p>Callback to return the list of frames with their event id and frame number.</p></td></tr><tr class="even"><td><p>[<strong>IFrameListRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422680)</p></td><td><p>Request for the list of frames with their event id and frame number.</p></td></tr><tr class="odd"><td><p>[<strong>ISummaryCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432809)</p></td><td><p>Callback to return summary information (displayed in the properties window).</p></td></tr><tr class="even"><td><p>[<strong>ISummaryRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432811)</p></td><td><p>Request for summary information.</p></td></tr><tr class="odd"><td><p>[<strong>IMeshCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422686)</p></td><td><p>Callback to return a buffer containing the mesh of a pipeline stage.</p></td></tr><tr class="even"><td><p>[<strong>IMeshRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422688)</p></td><td><p>Request for a buffer containing the mesh of a pipeline stage.</p></td></tr><tr class="odd"><td><p>[<strong>IFrameEventsCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422672)</p></td><td><p>Callback to return the list of events in a frame.</p></td></tr><tr class="even"><td><p>[<strong>ISingleEventRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432799)</p></td><td><p>Not used.</p></td></tr><tr class="odd"><td><p>[<strong>IFrameEventsRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422675)</p></td><td><p>Request for returning the list of events in a frame.</p></td></tr><tr class="even"><td><p>[<strong>IObjectTableCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422696)</p></td><td><p>Callback to return object table data.</p></td></tr><tr class="odd"><td><p>[<strong>IObjectTableRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422699)</p></td><td><p>Request for object table data.</p></td></tr><tr class="even"><td><p>[<strong>IFileIOCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt422665)</p></td><td><p>Callback to save or end the experiment. Indicates file save is done.</p></td></tr><tr class="odd"><td><p>[<strong>IPixEngine2</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432746)</p></td><td><p>Extensions to the original IPixEngine interface.</p></td></tr><tr class="even"><td><p>[<strong>IPixEngine</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432745)</p></td><td><p>Original interface for communicating data about a vsglog .</p></td></tr><tr class="odd"><td><p>[<strong>IPeerToPeerEngine</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432712)</p></td><td><p>Interface for remote communicating data about a vsglog.</p></td></tr><tr class="even"><td><p>[<strong>IServerConnectionCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432796)</p></td><td><p>Not used.</p></td></tr><tr class="odd"><td><p>[<strong>IPixEngine3</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432751)</p></td><td><p>Extensions to the IPixEngine2 interface.</p></td></tr><tr class="even"><td><p>[<strong>IPixEngine4</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432753)</p></td><td><p>Extensions to the IPIxEngine3 interface.</p></td></tr><tr class="odd"><td><p>[<strong>IUpdateObjectCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432823)</p></td><td><p>Callback to update the contents of an object.</p></td></tr><tr class="even"><td><p>[<strong>IUpdateObject</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432822)</p></td><td><p>Request for updating the contents of an object.</p></td></tr><tr class="odd"><td><p>[<strong>IPixEngine5Callbacks</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432756)</p></td><td><p>Callbacks used for viewing textures.</p></td></tr><tr class="even"><td><p>[<strong>IPixEngine5</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432755)</p></td><td><p>Extensions to the IPixEngine4 interface containing additions for viewing textures.</p></td></tr><tr class="odd"><td><p>[<strong>IPixEngine6</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432771)</p></td><td><p>Extensions to the IPixEngine5 interface containing additions for determining remote engine version.</p></td></tr><tr class="even"><td><p>[<strong>IVersionCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432826)</p></td><td><p>Callback to return the versions of all the interfaces supported. This allows the consumer to be out of sync with the capture engine.</p></td></tr><tr class="odd"><td><p>[<strong>IPixEngine7</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432773)</p></td><td><p>Extensions to the IPixEngine6 interface containing additions around versioning.</p></td></tr><tr class="even"><td><p>[<strong>IOfflineAnalysisCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432706)</p></td><td><p>Callback to returns offline analysis data.</p></td></tr><tr class="odd"><td><p>[<strong>IOfflineAnalysisRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432709)</p></td><td><p>Request for offline analysis data.</p></td></tr><tr class="even"><td><p>[<strong>IOfflineAnalysisCacheCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432702)</p></td><td><p>Callback to return information on whether an offline request is cached or not.</p></td></tr><tr class="odd"><td><p>[<strong>IOfflineAnalysisCacheRequest</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432704)</p></td><td><p>Requests for information on whether an offline request is cached or not.</p></td></tr><tr class="even"><td><p>[<strong>IStatusCallback</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432807)</p></td><td><p>Not used.</p></td></tr><tr class="odd"><td><p>[<strong>IPixEngineSingleton</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432776)</p></td><td><p>Determines if the engine supports a singleton instance or not.</p></td></tr><tr class="even"><td><p>[<strong>IPixEngineWin10</strong>](https://msdn.microsoft.com/library/windows/desktop/mt432778)</p></td><td><p>Determines if the engine is from Windows 10.</p></td></tr></tbody></table>

 

## <span id="related_topics"></span>Related topics

[Direct3D Diagnostics Capture Interface Reference](vspixengine-reference.md)

 

 


