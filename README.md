# Speech to text app : basic version using free Web Speech API

Web Speech API (browser-based)

https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API


The current page uses the built-in Web Speech API (SpeechRecognition/webkitSpeechRecognition) provided by Chrome/Edge. This API is free but undocumented; Google/Microsoft don’t publish firm quotas.

In practice sessions are rate-limited: Chrome often auto-stops after ~60 seconds of continuous speech, and can hit daily usage caps (roughly a few minutes of audio per browser). When limits trigger you’ll see network/service not allowed errors and the recognizer just stops. ====> this limitation seems not true anymore.


There’s no way to reserve more hours or see an official allowance; for longer or production workloads you need a managed service.
