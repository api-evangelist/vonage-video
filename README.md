# Vonage Video API (vonage-video)

Vonage Video API (formerly OpenTok / TokBox) is a programmable live video platform for building real-time interactive video, voice, and messaging into apps. Its REST API on the Vonage Video Cloud creates sessions and drives advanced server-side features - recording (archives), live streaming broadcasts, signaling, SIP interconnect, and the Experience Composer render service - authenticated with JWT Bearer tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vonage-video/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vonage-video/refs/heads/main/apis.yml)

> Note: The Vonage Video API was previously branded OpenTok / TokBox. Legacy endpoints remain documented under the `api.opentok.com` host; new development uses the `video.api.vonage.com` host and JWT-based application authentication.

## Tags

- Video
- WebRTC
- Live Streaming
- Real-Time Communications
- CPaaS

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Vonage Video Sessions API

Create video sessions, list and force-disconnect connections, mute streams and whole sessions, and migrate active sessions across media regions.

- **Human URL:** [https://developer.vonage.com/en/video/overview](https://developer.vonage.com/en/video/overview)
- **Base URL:** `https://video.api.vonage.com/v2`

#### Tags

- Sessions
- WebRTC
- Connections

#### Properties

- [Documentation](https://developer.vonage.com/en/video/guides/create-session/overview)
- [API Reference](https://developer.vonage.com/en/api/video)
- [OpenAPI](openapi/vonage-video-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vonage-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vonage-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vonage Video Streams & Signaling API

Inspect individual and all streams in a session, set stream classes and layout, and send server-side signals to a whole session or a single connection.

- **Human URL:** [https://developer.vonage.com/en/video/guides/signaling](https://developer.vonage.com/en/video/guides/signaling)
- **Base URL:** `https://video.api.vonage.com/v2`

#### Tags

- Streams
- Signaling
- Moderation

#### Properties

- [Documentation](https://developer.vonage.com/en/video/guides/signaling)
- [API Reference](https://developer.vonage.com/en/api/video)
- [OpenAPI](openapi/vonage-video-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vonage-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vonage-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vonage Video Archives API

Record sessions as composed or individual-stream archives - start, stop, list, retrieve, and delete archives, change archive layout, and select streams.

- **Human URL:** [https://developer.vonage.com/en/video/guides/archiving/overview](https://developer.vonage.com/en/video/guides/archiving/overview)
- **Base URL:** `https://video.api.vonage.com/v2`

#### Tags

- Archives
- Recording
- Storage

#### Properties

- [Documentation](https://developer.vonage.com/en/video/guides/archiving/overview)
- [API Reference](https://developer.vonage.com/en/api/video)
- [OpenAPI](openapi/vonage-video-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vonage-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vonage-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vonage Video Broadcasts API

Broadcast a session to HLS and RTMP destinations - start, stop, list, and retrieve broadcasts, change broadcast layout, and select streams to include.

- **Human URL:** [https://developer.vonage.com/en/video/guides/broadcast/live-streaming](https://developer.vonage.com/en/video/guides/broadcast/live-streaming)
- **Base URL:** `https://video.api.vonage.com/v2`

#### Tags

- Broadcasts
- Live Streaming
- HLS
- RTMP

#### Properties

- [Documentation](https://developer.vonage.com/en/video/guides/broadcast/live-streaming)
- [API Reference](https://developer.vonage.com/en/api/video)
- [OpenAPI](openapi/vonage-video-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vonage-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vonage-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vonage Video SIP & Render API

Dial PSTN/SIP endpoints into a session, play DTMF tones, start and stop live captions, and run the Experience Composer render service for custom layouts.

- **Human URL:** [https://developer.vonage.com/en/video/guides/sip](https://developer.vonage.com/en/video/guides/sip)
- **Base URL:** `https://video.api.vonage.com/v2`

#### Tags

- SIP
- Experience Composer
- Render
- Captions

#### Properties

- [Documentation](https://developer.vonage.com/en/video/guides/sip)
- [API Reference](https://developer.vonage.com/en/api/video)
- [OpenAPI](openapi/vonage-video-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vonage-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vonage-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vonage Video Webhooks API

Session monitoring, archive, broadcast, SIP, captions, and render callback events delivered to a registered URL, with secure (signed) callback verification.

- **Human URL:** [https://developer.vonage.com/en/video/guides/session-monitoring](https://developer.vonage.com/en/video/guides/session-monitoring)
- **Base URL:** `https://video.api.vonage.com/v2`

#### Tags

- Webhooks
- Callbacks
- Session Monitoring

#### Properties

- [Documentation](https://developer.vonage.com/en/video/guides/session-monitoring)
- [Documentation](https://developer.vonage.com/en/video/guides/secure-callbacks)
- [OpenAPI](openapi/vonage-video-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/Vonage)
- [LinkedIn](https://www.linkedin.com/company/vonage)
- [Website](https://www.vonage.com/communications-apis/video/)
- [Documentation](https://developer.vonage.com/en/video/overview)
- [Plans](plans/vonage-video-plans-pricing.yml)
- [Rate Limits](rate-limits/vonage-video-rate-limits.yml)
- [Fin Ops](finops/vonage-video-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
