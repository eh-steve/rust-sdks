---
webrtc-sys: patch
libwebrtc: patch
livekit: patch
livekit-ffi: patch
---

Add TrackPublishOptions.svc_layer_bitrates to override per-spatial-layer SVC bitrates (VP9/AV1). Requires a libwebrtc build with RtpEncodingParameters::svc_layer_bitrates support; silently ignored on older builds.
