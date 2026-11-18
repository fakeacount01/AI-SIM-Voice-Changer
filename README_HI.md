# AI SIM Voice Changer

Android (Kotlin + Jetpack Compose). Min Android 8.0 (API 26).

## APK बनाने का तरीका (बिना कोड/Git सीखे)
1. github.com पर free account बनाइए, "New repository" दबाइए, नाम रखिए (जैसे ai-sim-voice-changer), Create दबाइए।
2. "uploading an existing file" लिंक दबाइए।
3. इस ZIP को अपने फोन/PC में extract कीजिए, उसके अंदर की सारी फाइलें और फोल्डर (".github" फोल्डर सहित) drag करके upload कीजिए, "Commit changes" दबाइए।
4. ऊपर "Actions" टैब खोलिए। "Build APK" चलना शुरू हो जाएगा (3-6 मिनट)।
5. Run हरा होने पर उस पर क्लिक करके नीचे "Artifacts" से AI-SIM-Voice-Changer-APK download कीजिए, ZIP खोलकर .apk install कीजिए।
(.github फोल्डर hidden होता है। PC पर "show hidden files" चालू रखें, या Actions में "set up a workflow yourself" से build-apk.yml की सामग्री paste करें।)

## Status
- Working: live voice effects, preview, waveform, contacts, call history, settings
- Hardware-dependent: असली SIM call में बदली आवाज़ (दूसरा फोन + cable, या external audio hardware)
- Unsupported: app द्वारा सीधे SIM uplink बदलना, Custom AI Voice (कोई model नहीं)
