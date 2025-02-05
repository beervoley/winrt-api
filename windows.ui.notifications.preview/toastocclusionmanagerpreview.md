---
-api-id: T:Windows.UI.Notifications.Preview.ToastOcclusionManagerPreview
-api-type: winrt class
---

# Windows.UI.Notifications.Preview.ToastOcclusionManagerPreview

<!--
public static class ToastOcclusionManagerPreview
-->


## -description

Provides a preview API for requesting that the OS apply a vertical offset when displaying app notifications, to avoid obscuring the UI of the calling app.

> [!IMPORTANT]
> **Limited Access API**: This API is a limited access feature. To use this API, please contact [taskbarsecondarytile@microsoft.com](mailto:toastocclusionapi@microsoft.com?Subject=Limited%20Access%20permission%20to%20use%toast%20occlusion%20on%20APIs).

## -remarks

This API is being released as a preview to enable testing of the feature by enterprise customers. This API is likely to be removed and/or modified in a future release. Before using the API, apps should call [LimitedAccessFeatures.TryUnlockFeature](/uwp/api/windows.applicationmodel.limitedaccessfeatures.tryunlockfeature), passing in the feature ID and app token provided by Microsoft, to verify that the app is authorized to use the API. Calls by unauthorized apps will have no effect.

## -see-also

[LimitedAccessFeatures](/uwp/api/windows.applicationmodel.limitedaccessfeatures)

## -examples


