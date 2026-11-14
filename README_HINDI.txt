HINDI VOICE – OFFLINE (Android app source)

यह एक मुफ्त Android ऐप का source project है। इसमें इंटरनेट permission नहीं है।
ऐप Android के built-in Text-to-Speech engine का उपयोग करता है। इसलिए ऑफलाइन
आवाज़ तभी चलेगी जब आपके फोन में Hindi voice data पहले से डाउनलोड हो।

APK बनाने का तरीका (Android Studio की जरूरत नहीं):
1. GitHub पर मुफ्त अकाउंट बनाएं/लॉगिन करें।
2. नया Public या Private repository बनाएं।
3. इस ZIP को extract करके सभी फाइलें repository में upload करें।
4. ऊपर Actions टैब खोलें।
5. "Build Android APK" workflow चुनकर Run workflow दबाएं।
6. Build पूरा होने पर "Hindi-Voice-APK" artifact डाउनलोड करें।
7. ZIP खोलें और app-debug.apk को Android फोन में इंस्टॉल करें।
   पहली बार Android सेटिंग में "Install unknown apps" अनुमति देनी पड़ सकती है।

फोन में Hindi voice data डाउनलोड करने के लिए:
Settings > Languages & input (या General management) > Text-to-speech output
> Preferred engine (Google Speech Services) > Settings > Install voice data
> Hindi चुनें। फोन के अनुसार मेन्यू के नाम अलग हो सकते हैं।

नोट:
- यह ऐप स्वयं आवाज का मॉडल साथ में नहीं रखता; यह फोन के TTS engine पर निर्भर है।
- भारतीय पुरुष आवाज उपलब्ध होना फोन/Google TTS में उपलब्ध voice पर निर्भर करता है।
- पहली बार voice data डाउनलोड करने के लिए इंटरनेट लग सकता है; उसके बाद उपलब्ध
  ऑफलाइन Hindi voice से पढ़ा जा सकता है।
