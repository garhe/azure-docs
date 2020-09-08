---
title: Language support - Speech service
titleSuffix: Azure Cognitive Services
description: The Speech service supports numerous languages for speech-to-text and text-to-speech conversion, along with speech translation. This article provides a comprehensive list of language support by service feature.
services: cognitive-services
author: trevorbye
manager: nitinme
ms.service: cognitive-services
ms.subservice: speech-service
ms.topic: conceptual
ms.date: 03/26/2020
ms.author: trbye
ms.custom: seodec18
---

# Language and voice support for the Speech service

Language support varies by Speech service functionality. The following tables summarize language support for [Speech-to-text](#speech-to-text), [Text-to-speech](#text-to-speech), and [Speech translation](#speech-translation) service offerings.

## Speech-to-text

Both the Microsoft Speech SDK and the REST API support the following languages (locales). 

To improve accuracy, customization is offered for a subset of the languages through uploading **Audio + Human-labeled Transcripts** or **Related Text: Sentences**. To learn more about customization, see [Get started with Custom Speech](how-to-custom-speech.md).

<!--
To get the AM and ML bits:
https://westus.cris.ai/swagger/ui/index#/Custom%20Speech%20models%3A/GetSupportedLocalesForModels

To get pronunciation bits:
https://cris.ai -> Click on Adaptation Data -> scroll down to section "Pronunciation Datasets" -> Click on Import -> Locale: the list of locales there correspond to the supported locales
-->

| Locale  | Language                          | Customizations                                    |
|---------|-----------------------------------|---------------------------------------------------|
| `ar-AE` | Arabic (UAE)                      | No                                                |
| `ar-BH` | Arabic (Bahrain), modern standard | Language model                                    |
| `ar-EG` | Arabic (Egypt)                    | Language model                                    |
| `ar-IL` | Arabic (Israel)                   | No                                                |
| `ar-JO` | Arabic (Jordan)                   | No                                                |
| `ar-KW` | Arabic (Kuwait)                   | No                                                |
| `ar-LB` | Arabic (Lebanon)                  | No                                                |
| `ar-PS` | Arabic (Palestine)                | No                                                |
| `ar-QA` | Arabic (Qatar)                    | No                                                |
| `ar-SA` | Arabic (Saudi Arabia)             | No                                                |
| `ar-SY` | Arabic (Syria)                    | Language model                                    |
| `ca-ES` | Catalan                           | Language model                                    |
| `cs-CZ` | Czech (Czech Republic)            | Language Model                                    | 
| `da-DK` | Danish (Denmark)                  | Language model                                    |
| `de-DE` | German (Germany)                  | Acoustic model<br>Language model<br>Pronunciation |
| `en-AU` | English (Australia)               | Acoustic model<br>Language model                  |
| `en-CA` | English (Canada)                  | Acoustic model<br>Language model                  |
| `en-GB` | English (United Kingdom)          | Acoustic model<br>Language model<br>Pronunciation |
| `en-HK` | English (Hong kong)               | Language Model                                    | 
| `en-IE` | English (Ireland)                 | Language Model                                    | 
| `en-IN` | English (India)                   | Acoustic model<br>Language model                  |
| `en-NZ` | English (New Zealand)             | Acoustic model<br>Language model                  |
| `en-PH` | English (Philippines)             | Language Model                                    | 
| `en-SG` | English (Singapore)               | Language Model                                    | 
| `en-US` | English (United States)           | Acoustic model<br>Language model<br>Pronunciation |
| `en-ZA` | English (South Africa)            | Language Model                                    | 
| `es-AR` | Spanish (Argentina)               | Language Model                                    | 
| `es-BO` | Spanish (Bolivia)                 | Language Model                                    | 
| `es-CL` | Spanish (Chile)                   | Language Model                                    | 
| `es-CO` | Spanish (Colombia)                | Language Model                                    | 
| `es-CR` | Spanish (Costa Rica)              | Language Model                                    | 
| `es-CU` | Spanish (Cuba)                    | Language Model                                    | 
| `es-DO` | Spanish (Dominican Republic)      | Language Model                                    | 
| `es-EC` | Spanish (Ecuador)                 | Language Model                                    | 
| `es-ES` | Spanish (Spain)                   | Acoustic model<br>Language model                  |
| `es-GT` | Spanish (Guatemala)               | Language Model                                    | 
| `es-HN` | Spanish (Honduras)                | Language Model                                    | 
| `es-MX` | Spanish (Mexico)                  | Acoustic model<br>Language model                  |
| `es-NI` | Spanish (Nicaragua)               | Language Model                                    | 
| `es-PA` | Spanish (Panama)                  | Language Model                                    | 
| `es-PE` | Spanish (Peru)                    | Language Model                                    | 
| `es-PR` | Spanish (Puerto Rico)             | Language Model                                    | 
| `es-PY` | Spanish (Paraguay)                | Language Model                                    | 
| `es-SV` | Spanish (El Salvador)             | Language Model                                    | 
| `es-US` | Spanish (USA)                     | Language Model                                    | 
| `es-UY` | Spanish (Uruguay)                 | Language Model                                    | 
| `es-VE` | Spanish (Venezuela)               | Language Model                                    | 
| `fi-FI` | Finnish (Finland)                 | Language model                                    |
| `fr-CA` | French (Canada)                   | Acoustic model<br>Language model                  |
| `fr-FR` | French (France)                   | Acoustic model<br>Language model<br>Pronunciation |
| `gu-IN` | Gujarati (Indian)                 | Language model                                    |
| `hi-IN` | Hindi (India)                     | Acoustic model<br>Language model                  |
| `hu-HU` | Hungarian (Hungary)               | Language Model                                    | 
| `it-IT` | Italian (Italy)                   | Acoustic model<br>Language model<br>Pronunciation |
| `ja-JP` | Japanese (Japan)                  | Language model                                    |
| `ko-KR` | Korean (Korea)                    | Language model                                    |
| `mr-IN` | Marathi (India)                   | Language model                                    |
| `nb-NO` | Norwegian (Bokmål) (Norway)       | Language model                                    |
| `nl-NL` | Dutch (Netherlands)               | Language model                                    |
| `pl-PL` | Polish (Poland)                   | Language model                                    |
| `pt-BR` | Portuguese (Brazil)               | Acoustic model<br>Language model<br>Pronunciation |
| `pt-PT` | Portuguese (Portugal)             | Language model                                    |
| `ru-RU` | Russian (Russia)                  | Acoustic model<br>Language model                  |
| `sv-SE` | Swedish (Sweden)                  | Language model                                    |
| `ta-IN` | Tamil (India)                     | Language model                                    |
| `te-IN` | Telugu (India)                    | Language model                                    |
| `th-TH` | Thai (Thailand)                   | No                                                |
| `tr-TR` | Turkish (Turkey)                  | Language model                                    |
| `zh-CN` | Chinese (Mandarin, Simplified)    | Acoustic model<br>Language model                  |
| `zh-HK` | Chinese (Cantonese, Traditional)  | Language model                                    |
| `zh-TW` | Chinese (Taiwanese Mandarin)      | Language model                                    |

## Text-to-speech

Both the Microsoft Speech SDK and REST APIs support these voices, each of which supports a specific language and dialect, identified by locale. You can also get a full list of languages and voices supported for each specific region/endpoint through the [voices/list API](rest-text-to-speech.md#get-a-list-of-voices). 

> [!IMPORTANT]
> Pricing varies for standard, custom and neural voices. Please visit the [Pricing](https://azure.microsoft.com/pricing/details/cognitive-services/speech-services/) page for additional information.

### Neural voices

Neural text-to-speech is a new type of speech synthesis powered by deep neural networks. When using a neural voice, synthesized speech is nearly indistinguishable from the human recordings.

Neural voices can be used to make interactions with chatbots and voice assistants more natural and engaging, convert digital texts such as e-books into audiobooks and enhance in-car navigation systems. With the human-like natural prosody and clear articulation of words, neural voices significantly reduce listening fatigue when users interact with AI systems.

For more information about regional availability, see [regions](regions.md#standard-and-neural-voices).

|Locale  | Language            | Gender | Voice name | Style support |
|--|--|--|--|--|
| `ar-EG` | Arabic  (Egypt) | Female | `ar-EG-SalmaNeural` | General |
| `ar-SA` | Arabic  (Saudi Arabia) | Female | `ar-SA-ZariyahNeural` | General |
| <sup>New</sup> `bg-BG` | Bulgarian (Bulgary) | Female | `bg-BG-KalinaNeural` | General |
| `ca-ES` | Catalan  (Spain) | Female | `ca-ES-AlbaNeural` | General |
| <sup>New</sup> `cs-CZ` | Czech (Czech) | Female | `cs-CZ-VlastaNeural` | General |
| `da-DK` | Danish  (Denmark) | Female | `da-DK-ChristelNeural` | General |
| <sup>New</sup> `de-AT` | German (Austria) | Female | `de-AT-IngridNeural` | General |
| <sup>New</sup> `de-CH` | German (Switzerland) | Female | `de-CH-LeniNeural` | General |
| <sup>New</sup> `de-DE` | German (Germany) | Male | `de-DE-ConradNeural` | General |
| `de-DE` | German  (Germany) | Female | `de-DE-KatjaNeural` | General |
| <sup>New</sup> `el-GR` | Greek (Greece) | Female | `el-GR-AthinaNeural` | General |
| <sup>New</sup> `en-AU` | Australian (Australia) | Male | `en-AU-WilliamNeural` | General |
| `en-AU` | English  (Australia) | Female | `en-AU-NatashaNeural` | General |
| `en-CA` | English  (Canada) | Female | `en-CA-ClaraNeural` | General |
| <sup>New</sup> `En-GB` | English (United Kingdom) | Male | `En-GB-RyanNeural` | General |
| `en-GB` | English  (United Kingdom) | Female | `en-GB-LibbyNeural` | General |
| `en-GB` | English  (United Kingdom) | Female | `en-GB-MiaNeural` | General |
| <sup>New</sup> `en-IE` | Irish English (Ireland) | Female | `en-IE-EmilyNeural` | General |
| `en-IN` | English  (India) | Female | `en-IN-NeerjaNeural` | General |
| <sup>New</sup> `en-US` | English  (United States) | Female | `en-US-JennyNeural` | General, multiple voice styles available |
| `en-US` | English  (United States) | Female | `en-US-AriaNeural` | General, multiple voice styles available |
| `en-US` | English  (United States) | Male | `en-US-GuyNeural` | General |
| <sup>New</sup> `es-ES` | Spainish  (Spain) | Male | `es-ES-AlvaroNeural` | General |
| `es-ES` | Spanish  (Spain) | Female | `es-ES-ElviraNeural` | General |
| <sup>New</sup> `es-MX` | Spanish (Mexico) | Male | `es-MX-JorgeNeural` | General |
| `es-MX` | Spanish  (Mexico) | Female | `es-MX-DaliaNeural` | General |
| `fi-FI` | Finnish  (Finland) | Female | `fi-FI-NooraNeural` | General |
| <sup>New</sup> `Fr-CA` | French (Canada) | Male | `fr-CA-JeanNeural` | General |
| `fr-CA` | French  (Canada) | Female | `fr-CA-SylvieNeural` | General |
| <sup>New</sup> `fr-CH` | French (Switzerland) | Female | `fr-CH-ArianeNeural` | General |
| <sup>New</sup> `Fr-FR` | French (France) | Male | `fr-FR-HenriNeural` | General |
| `fr-FR` | French  (France) | Female | `fr-FR-DeniseNeural` | General |
| <sup>New</sup> `he-IL` | Hebrew (Isareal) | Female | `he-IL-HilaNeural` | General |
| `hi-IN` | Hindi  (India) | Female | `hi-IN-SwaraNeural` | General |
| <sup>New</sup> `hr-HR` | Croatian (Croatia) | Female | `hr-HR-GabrijelaNeural` | General |
| <sup>New</sup> `hu-HU` | Hungarian (Hungary) | Female | `hu-HU-NoemiNeural` | General |
| <sup>New</sup> `id-ID` | Bahasa Indonesian (Indonesia) | Male | `id-ID-ArdiNeural` | General |
| <sup>New</sup> `id-ID` | Bahasa Indonesian (Indonesia) | Female | `id-ID-GadisNeural` | General |
| <sup>New</sup> `it-IT` | Italian (Italy) | Male | `it-IT-DiegoNeural` | General |
| <sup>New</sup> `it-IT` | Italian (Italy) | Female | `it-IT-IsabellaNeural` | General |
| `it-IT` | Italian  (Italy) | Female | `it-IT-ElsaNeural` | General |
| <sup>New</sup> `ja-JP` | Japanese (Japan) | Male | `ja-JP-KeitaNeural` | General |
| `ja-JP` | Japanese  (Japan) | Female | `ja-JP-NanamiNeural` | General |
| <sup>New</sup> `ko-KR` | Korean (Korea) | Male | `ko-KR-InJoonNeural` | General |
| `ko-KR` | Korean  (South Korea) | Female | `ko-KR-SunHiNeural` | General |
| <sup>New</sup> `ms-MY` | Malay (Malaysia) | Female | `ms-MY-YasminNeural` | General |
| `nb-NO` | Norwegian, Bokmål  (Norway) | Female | `nb-NO-IselinNeural` | General |
| `nl-NL` | Dutch  (Netherlands) | Female | `nl-NL-ColetteNeural` | General |
| `pl-PL` | Polish  (Poland) | Female | `pl-PL-ZofiaNeural` | General |
| <sup>New</sup> `pt-BR` | Brazilian Portugues (Brazil) | Male | `pt-BR-AntonioNeural` | General |
| `pt-BR` | Portuguese  (Brazil) | Female | `pt-BR-FranciscaNeural` | General, multiple voice styles available |
| `pt-PT` | Portuguese  (Portugal) | Female | `pt-PT-FernandaNeural` | General |
| <sup>New</sup> `ro-RO` | Romanian (Romania) | Female | `ro-RO-AlinaNeural` | General |
| `ru-RU` | Russian  (Russia) | Female | `ru-RU-DariyaNeural` | General |
| <sup>New</sup> `sk-SK` | Skovanian (Skovania) | Female | `sk-SK-ViktoriaNeural` | General |
| <sup>New</sup> `sl-SI` | Slovenian (Slovenia) | Female | `sl-SI-PetraNeural` | General |
| `sv-SE` | Swedish  (Sweden) | Female | `sv-SE-HilleviNeural` | General |
| <sup>New</sup> `th-TH` | Thai (Thailand) | Female | `th-TH-PremwadeeNeural` | General |
| `th-TH` | Thai  (Thailand) | Female | `th-TH-AcharaNeural` | General |
| `tr-TR` | Turkish  (Turkey) | Female | `tr-TR-EmelNeural` | General |
| <sup>New</sup> `vi-VN` | Vietnamese (Vietnam) | Female | `vi-VN-HoaiMyNeural` | General |
| `zh-CN` | Mandarin (Simplified Chinese, China) | Male | `zh-CN-YunyeNeural` | Optimized for story narrating |
| `zh-CN` | Mandarin (Simplified Chinese, China) | Male | `zh-CN-YunyangNeural` | Optimized for news reading, multiple voice styles available |
| `zh-CN` | Mandarin (Simplified Chinese, China) | Female | `zh-CN-XiaoyouNeural` | Kid voice, optimized for story narrating |
| `zh-CN` | Mandarin (Simplified Chinese, China) | Female | `zh-CN-XiaoxiaoNeural` | General, multiple voice styles available |
| `zh-HK` | Cantonese (Traditional Chinese, Hong Kong) | Female | `zh-HK-HiuGaaiNeural` | General |
| `zh-TW` | Mandarin (Traditional Chinese, Taiwan) | Female | `zh-TW-HsiaoYuNeural` | General |

> [!IMPORTANT]
> The `en-US-JessaNeural` voice has changed to `en-US-AriaNeural`. If you were using "Jessa" before, convert over to "Aria".

To learn how you can configure and adjust neural voices, see [Speech synthesis markup language](speech-synthesis-markup.md#adjust-speaking-styles).

> [!TIP]
> You can continue to use the full service name mapping like "Microsoft Server Speech Text to Speech Voice (en-US, AriaNeural)" in your speech synthesis requests.

### Standard voices

More than 75 standard voices are available in over 45 languages and locales, which allow you to convert text into synthesized speech. For more information about regional availability, see [regions](regions.md#standard-and-neural-voices).

| Locale | Language | Gender | Voice name |
|--|--|--|--|
| <sup>1</sup>`ar-EG` | Arabic (Arabic ) | Female | `ar-EG-Hoda` | General |
| `ar-SA` | Arabic (Saudi Arabia) | Male | `ar-SA-Naayf` | General |
| `bg-BG` | Bulgarian (Bulgaria) | Male | `bg-BG-Ivan` | General |
| `ca-ES` | Catalan (Spain) | Female | `ca-ES-HerenaRUS` | General |
| `cs-CZ` | Czech (Czech Republic) | Male | `cs-CZ-Jakub` | General |
| `da-DK` | Danish (Denmark) | Female | `da-DK-HelleRUS` | General |
| `de-AT` | German (Austria) | Male | `de-AT-Michael` | General |
| `de-CH` | German (Switzerland) | Male | `de-CH-Karsten` | General |
| `de-DE` | German (Germany) | Female | `de-DE-HeddaRUS` | General |
| `de-DE` | German (Germany) | Male | `de-DE-Stefan-Apollo` | General |
| `el-GR` | Greek (Greece) | Male | `el-GR-Stefanos` | General |
| `en-AU` | English (Australia) | Female | `en-AU-Catherine` | General |
| `en-AU` | English (Australia) | Female | `en-AU-HayleyRUS` | General |
| `en-CA` | English (Canada) | Female | `en-CA-HeatherRUS` | General |
| `en-CA` | English (Canada) | Female | `en-CA-Linda` | General |
| `en-GB` | English (United Kingdom) | Male | `en-GB-George-Apollo` | General |
| `en-GB` | English (United Kingdom) | Female | `en-GB-HazelRUS` | General |
| `en-GB` | English (United Kingdom) | Female | `en-GB-Susan-Apollo` | General |
| `en-IE` | English (Ireland) | Male | `en-IE-Sean` | General |
| `en-IN` | English (India) | Female | `en-IN-Heera-Apollo` | General |
| `en-IN` | English (India) | Female | `en-IN-PriyaRUS` | General |
| `en-IN` | English (India) | Male | `en-IN-Ravi-Apollo` | General |
| `en-US` | English (United States) | Male | `en-US-BenjaminRUS` | General |
| `en-US` | English (United States) | Male | `en-US-Guy24kRUS` | General |
| `en-US` | English (United States) | Female | `en-US-Jessa24kRUS` | General |
| `en-US` | English (United States) | Female | `en-US-ZiraRUS` | General |
| `es-ES` | Spanish (Spain) | Female | `es-ES-HelenaRUS` | General |
| `es-ES` | Spanish (Spain) | Female | `es-ES-Laura-Apollo` | General |
| `es-ES` | Spanish (Spain) | Male | `es-ES-Pablo-Apollo` | General |
| `es-MX` | Spanish (Mexico) | Female | `es-MX-HildaRUS` | General |
| `es-MX` | Spanish (Mexico) | Male | `es-MX-Raul-Apollo` | General |
| `fi-FI` | Finnish (Finland) | Female | `fi-FI-HeidiRUS` | General |
| `fr-CA` | French (Canada) | Female | `fr-CA-Caroline` | General |
| `fr-CA` | French (Canada) | Female | `fr-CA-HarmonieRUS` | General |
| `fr-CH` | French (Switzerland) | Male | `fr-CH-Guillaume` | General |
| `fr-FR` | French (France) | Female | `fr-FR-HortenseRUS` | General |
| `fr-FR` | French (France) | Female | `fr-FR-Julie-Apollo` | General |
| `fr-FR` | French (France) | Male | `fr-FR-Paul-Apollo` | General |
| `he-IL` | Hebrew (Israel) | Male | `he-IL-Asaf` | General |
| `hi-IN` | Hindi (India) | Male | `hi-IN-Hemant` | General |
| `hi-IN` | Hindi (India) | Female | `hi-IN-Kalpana` | General |
| `hr-HR` | Croatian (Croatia) | Male | `hr-HR-Matej` | General |
| `hu-HU` | Hungarian (Hungary) | Male | `hu-HU-Szabolcs` | General |
| `id-ID` | Indonesian (Indonesia) | Male | `id-ID-Andika` | General |
| `it-IT` | Italian (Italy) | Male | `it-IT-Cosimo-Apollo` | General |
| `it-IT` | Italian (Italy) | Female | `it-IT-LuciaRUS` | General |
| `ja-JP` | Japanese (Japan) | Female | `ja-JP-Ayumi-Apollo` | General |
| `ja-JP` | Japanese (Japan) | Female | `ja-JP-HarukaRUS` | General |
| `ja-JP` | Japanese (Japan) | Male | `ja-JP-Ichiro-Apollo` | General |
| `ko-KR` | Korean (South Korea) | Female | `ko-KR-HeamiRUS` | General |
| `ms-MY` | Malay (Malaysia) | Male | `ms-MY-Rizwan` | General |
| `nb-NO` | Norwegian, Bokmål (Norway) | Female | `nb-NO-HuldaRUS` | General |
| `nl-NL` | Dutch (Netherlands) | Female | `nl-NL-HannaRUS` | General |
| `pl-PL` | Polish (Poland) | Female | `pl-PL-PaulinaRUS` | General |
| `pt-BR` | Portuguese (Brazil) | Male | `pt-BR-Daniel-Apollo` | General |
| `pt-BR` | Portuguese (Brazil) | Female | `pt-BR-HeloisaRUS` | General |
| `pt-PT` | Portuguese (Portugal) | Female | `pt-PT-HeliaRUS` | General |
| `ro-RO` | Romanian (Romania) | Male | `ro-RO-Andrei` | General |
| `ru-RU` | Russian (Russia) | Female | `ru-RU-EkaterinaRUS` | General |
| `ru-RU` | Russian (Russia) | Female | `ru-RU-Irina-Apollo` | General |
| `ru-RU` | Russian (Russia) | Male | `ru-RU-Pavel-Apollo` | General |
| `sk-SK` | Slovak (Slovakia) | Male | `sk-SK-Filip` | General |
| `sl-SI` | Slovenian (Slovenia) | Male | `sl-SI-Lado` | General |
| `sv-SE` | Swedish (Sweden) | Female | `sv-SE-HedvigRUS` | General |
| `ta-IN` | Tamil (India) | Male | `ta-IN-Valluvar` | General |
| `te-IN` | Telugu (India) | Female | `te-IN-Chitra` | General |
| `th-TH` | Thai (Thailand) | Male | `th-TH-Pattara` | General |
| `tr-TR` | Turkish (Turkey) | Female | `tr-TR-SedaRUS` | General |
| `vi-VN` | Vietnamese (Vietnam) | Male | `vi-VN-An` | General |
| `zh-CN` | Mandarin (Simplified Chinese, China) | Female | `zh-CN-HuihuiRUS` | General |
| `zh-CN` | Mandarin (Simplified Chinese, China) | Male | `zh-CN-Kangkang-Apollo` | General |
| `zh-CN` | Mandarin (Simplified Chinese, China) | Female | `zh-CN-Yaoyao-Apollo` | General |
| `zh-HK` | Cantonese (Traditional Chinese, Hong Kong) | Male | `zh-HK-Danny-Apollo` | General |
| `zh-HK` | Cantonese (Traditional Chinese, Hong Kong) | Female | `zh-HK-TracyRUS` | General |
| `zh-TW` | Mandarin (Traditional Chinese, Taiwan) | Female | `zh-TW-HanHanRUS` | General |
| `zh-TW` | Mandarin (Traditional Chinese, Taiwan) | Female | `zh-TW-Yating-Apollo` | General |
| `zh-TW` | Mandarin (Traditional Chinese, Taiwan) | Male | `zh-TW-Zhiwei-Apollo` | General |

**1** *ar-EG supports Modern Standard Arabic (MSA).*

> [!IMPORTANT]
> The `en-US-Jessa` voice has changed to `en-US-Aria`. If you were using "Jessa" before, convert over to "Aria".

> [!TIP]
> You can continue to use the full service name mapping like "Microsoft Server Speech Text to Speech Voice (en-US, AriaRUS)" in your speech synthesis requests.

### Customization

Voice customization is available for `de-DE`, `en-GB`, `en-IN`, `en-US`, `es-MX`, `fr-FR`, `it-IT`, `pt-BR`, and `zh-CN`. Select the right locale that matches the training data you have to train a custom voice model. For example, if the recording data you have is spoken in English with a British accent, select `en-GB`.

> [!NOTE]
> We do not support bi-lingual model training in Custom Voice, except for the Chinese-English bi-lingual. Select "Chinese-English bilingual" if you want to train a Chinese voice that can speak English as well. Voice training in all locales starts with a data set of 2,000+ utterances, except for the `en-US` and `zh-CN` where you can start with any size of training data.

## Speech translation

The **Speech Translation** API supports different languages for speech-to-speech and speech-to-text translation. The source language must always be from the Speech-to-text language table. The available target languages depend on whether the translation target is speech or text. You may translate incoming speech into more than [60 languages](https://www.microsoft.com/translator/business/languages/). A subset of languages are available for [speech synthesis](language-support.md#text-languages).

### Text languages

| Text language           | Language code |
|:------------------------|:-------------:|
| Afrikaans               | `af`          |
| Arabic                  | `ar`          |
| Bangla                  | `bn`          |
| Bosnian (Latin)         | `bs`          |
| Bulgarian               | `bg`          |
| Cantonese (Traditional) | `yue`         |
| Catalan                 | `ca`          |
| Chinese Simplified      | `zh-Hans`     |
| Chinese Traditional     | `zh-Hant`     |
| Croatian                | `hr`          |
| Czech                   | `cs`          |
| Danish                  | `da`          |
| Dutch                   | `nl`          |
| English                 | `en`          |
| Estonian                | `et`          |
| Fijian                  | `fj`          |
| Filipino                | `fil`         |
| Finnish                 | `fi`          |
| French                  | `fr`          |
| German                  | `de`          |
| Greek                   | `el`          |
| Gujarati                | `gu`          |
| Haitian Creole          | `ht`          |
| Hebrew                  | `he`          |
| Hindi                   | `hi`          |
| Hmong Daw               | `mww`         |
| Hungarian               | `hu`          |
| Indonesian              | `id`          |
| Irish                   | `ga`          |
| Italian                 | `it`          |
| Japanese                | `ja`          |
| Kannada                 | `kn`          |
| Kiswahili               | `sw`          |
| Klingon                 | `tlh-Latn`    |
| Klingon (plqaD)         | `tlh-Piqd`    |
| Korean                  | `ko`          |
| Latvian                 | `lv`          |
| Lithuanian              | `lt`          |
| Malagasy                | `mg`          |
| Malay                   | `ms`          |
| Malayalam               | `ml`          |
| Maltese                 | `mt`          |
| Maori                   | `mi`          |
| Marathi                 | `mr`          |
| Norwegian               | `nb`          |
| Persian                 | `fa`          |
| Polish                  | `pl`          |
| Portuguese (Brazil)     | `pt-br`       |
| Portuguese (Portugal)   | `pt-pt`       |
| Punjabi                 | `pa`          |
| Queretaro Otomi         | `otq`         |
| Romanian                | `ro`          |
| Russian                 | `ru`          |
| Samoan                  | `sm`          |
| Serbian (Cyrillic)      | `sr-Cyrl`     |
| Serbian (Latin)         | `sr-Latn`     |
| Slovak                  | `sk`          |
| Slovenian               | `sl`          |
| Spanish                 | `es`          |
| Swedish                 | `sv`          |
| Tahitian                | `ty`          |
| Tamil                   | `ta`          |
| Telugu                  | `te`          |
| Thai                    | `th`          |
| Tongan                  | `to`          |
| Turkish                 | `tr`          |
| Ukrainian               | `uk`          |
| Urdu                    | `ur`          |
| Vietnamese              | `vi`          |
| Welsh                   | `cy`          |
| Yucatec Maya            | `yua`         |

## Speaker Recognition

See the following table for supported languages for the various Speaker Recognition APIs. See the [overview](speaker-recognition-overview.md) for additional information on Speaker Recognition.

| Locale | Language | Text-dependent verification | Text-independent verification | Text-independent identification |
|----|----|----|----|----|
| en-US | English (US) | yes | yes | yes |
|zh-CN    |Chinese (Mandarin, simplified)|    n/a|    yes|    yes|
|de-DE    |German (Germany)    |n/a    |yes    |yes|
|en-GB    |English (UK)    |n/a    |yes    |yes|
|fr-FR    |French (France)    |n/a    |yes    |yes|
|en-AU    |English (Australia)    |n/a    |yes    |yes|
|en-CA    |English (Canada)    |n/a|    yes|    yes|
|fr-CA    |French (Canada)    |n/a    |yes|    yes|
|it-IT    |Italian|    n/a    |yes|    yes|
|es-ES|    Spanish (Spain)    |n/a    |yes|    yes|
|es-MX    |Spanish (Mexico)    |n/a|    yes|    yes|
|ja-JP|    Japanese    |n/a    |yes    |yes|
|pt-BR|    Portuguese (Brazil)|    n/a|    yes|    yes|

## Next steps

* [Create a free Azure account](https://azure.microsoft.com/free/cognitive-services/)
* [See how to recognize speech in C#](~/articles/cognitive-services/Speech-Service/quickstarts/speech-to-text-from-microphone.md?pivots=programming-language-chsarp)
