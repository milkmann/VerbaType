# VerbaType Keyboard

VerbaType is an easy-to-use Android IME keyboard for transcribing and dictating speech. It supports extremely accurate results for many different languages, with custom multimodal transcription endpoints (e.g. Google Gemini 3 Flash / 2.5 Flash), punctuation formatting, and background AI rewording.

This project is a fork of [Dictate by DevEmperor](https://github.com/DevEmperor/Dictate) under the terms of the Apache 2.0 License.

## Key Changes in VerbaType
- **Custom Multimodal Support:** Send raw audio directly to OpenRouter's `/chat/completions` endpoint for multimodal models like Google Gemini Flash, performing both transcription and stylistic corrections in a single request.
- **Bypass Rewording:** Toggle to disable secondary post-processing/rewording requests when using a multimodal model, saving API costs and reducing response latency.
- **Enhanced Error Propagation:** Directly displays actual HTTP error responses on the keyboard instead of a generic connection error page.
- **Increased Custom Prompts Limit:** Expanded characters limit from 800 to 5000 in the custom system prompt input fields.

## License
VerbaType is licensed under the [Apache 2.0 License](LICENSE). 

---
*Based on the original work [Dictate](https://github.com/DevEmperor/Dictate) (c) 2024 DevEmperor.*
