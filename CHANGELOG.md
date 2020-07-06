# Change Log

Kandy Link Android SDK change log.

- This project adheres to [Semantic Versioning](http://semver.org/).
- This change log follows [keepachangelog.com](http://keepachangelog.com/) recommendations.

## 5.8.0 - 2020-07-03

## 5.7.0 - 2020-06-12

## 5.6.0 - 2020-05-04

### Fixed
- After Session Complete notification the end call DELETE request must be sent. `KAE-669`

## 5.5.0 - 2020-03-30

## 5.4.0 - 2020-03-02

### Added
- Adding configuration property for control TCP keep alive `KAE-571`

## 5.3.0 - 2020-01-09

### Added
- Call forward feature `KAE-80`


## 5.2.0 - 2019-12-02

### Added
- WebRTC stack upgraded to version M78 `KAE-507`
- Custom Kandy Agent HTTP Header is implemented `KAE-524`

### Deprecated
- `CallService.createOutgoingCall(String, CallApplicationListener, OutgoingCallCreateInterface)`, `CallService.createOutgoingCall(String, String, CallApplicationListener, OutgoingCallCreateInterface)`, `CallService.createOutgoingCall(String, String, String, CallApplicationListener, OutgoingCallCreateInterface)` and `CallService.createThreeWayCall(String, String, CallApplicationListener, OutgoingCallCreateInterface)` methods are deprecated and will be removed in future releases, since `CallApplicationListener` can already be set to CallService via a setter method. Instead `CallService.createOutgoingCall(String, OutgoingCallCreationCallback)`, `CallService.createOutgoingCall(String, String, OutgoingCallCreationCallback)`, `CallService.createOutgoingCall(String, String, String, OutgoingCallCreateInterface)` and `CallService.createThreeWayCall(String, String, OutgoingCallCreateInterface)` should be used.


## 5.1.0 - 2019-11-04

### Fixed
- Default value for codec preferrence is set to reflect WebRTC default codec behavior `KAE-538`


## 5.0.0 - 2019-10-03

### Added
- Unified Plan Support `KAE-200`
- Mobile SDK Distribution on Maven `KAE-425`
- Support Custom SIP headers in Incoming Call `KAE-447`
- Callee Name api added to CallInterface `KAE-475`


## 4.6.2 - 2019-09-02

### Fixed
- Media problem when switching between two calls on Music-on-Hold is fixed `KAE-410`


## 4.6.1.1 - 2019-08-05


## 4.6.1 - 2019-07-05

### Added
- Bandwidth limitation feature implemented `KAE-63`

### Fixed
- A fix provided for race condition case during WebRTC audio module creation when a second call session is being initiated. `KAE-435`
- A fix provided for 3-way call fail when early notification is received. `KAE-455`


## 4.6.0 - 2019-06-01

### Added
- PushService for CPaaS push notifications support. `KAE-350`

### Changed
- EventService is renamed as PushService. Its method `receiveNotification` which passes push notifications to Mobile SDK is replaced with `injectPushMessage`. `KAE-350`

### Fixed
- HTTP 4xx and 5xx responses are coded with a new error code and reported with MobileError. `KAE-288`


## 4.5.9.1 - 2019-05-06

### Fixed
- Hardware support of "Acoustic Echo Canceler" and "Noise Suppressor" configuration is fixed `KAE-369`


## 4.5.9 - 2019-05-02

### Changed
- Package name for VideoView is changed to "com.genband.mobile.core.webrtc.view". `KAE-368`
