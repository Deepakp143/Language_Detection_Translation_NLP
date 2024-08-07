# Language Translation using Machine Learning and NLP

## Project Overview

Language translation is the process of converting text or speech from one language to another while preserving its meaning and context. This project leverages modern machine learning techniques to detect languages and translate text efficiently. 

## Features

1. **Language Detection**: This feature identifies the language of the input text using the `langdetect` library, which supports over 55 languages.
2. **Language Translation**: The app translates the detected language text into a user-specified target language using the `googletrans` library.

## Problem Statement

The project addresses two key problems:

### 1. Language Detection

To determine the language of a given text, we utilize the `langdetect` package. This package is capable of detecting the following languages:
- af (Afrikaans)
- ar (Arabic)
- bg (Bulgarian)
- bn (Bengali)
- ca (Catalan)
- cs (Czech)
- cy (Welsh)
- da (Danish)
- de (German)
- el (Greek)
- en (English)
- es (Spanish)
- et (Estonian)
- fa (Persian)
- fi (Finnish)
- fr (French)
- gu (Gujarati)
- he (Hebrew)
- hi (Hindi)
- hr (Croatian)
- hu (Hungarian)
- id (Indonesian)
- it (Italian)
- ja (Japanese)
- kn (Kannada)
- ko (Korean)
- lt (Lithuanian)
- lv (Latvian)
- mk (Macedonian)
- ml (Malayalam)
- mr (Marathi)
- ne (Nepali)
- nl (Dutch)
- no (Norwegian)
- pa (Punjabi)
- pl (Polish)
- pt (Portuguese)
- ro (Romanian)
- ru (Russian)
- sk (Slovak)
- sl (Slovenian)
- so (Somali)
- sq (Albanian)
- sv (Swedish)
- sw (Swahili)
- ta (Tamil)
- te (Telugu)
- th (Thai)
- tl (Tagalog)
- tr (Turkish)
- uk (Ukrainian)
- ur (Urdu)
- vi (Vietnamese)
- zh-cn (Chinese Simplified)
- zh-tw (Chinese Traditional)

### Installation

Install the required packages using pip:

```bash
pip install langdetect
pip install googletrans==4.0.0-rc1
