

---

# Project Overview

In this project, we used **E5 Large Multilingual Embedding** with an FC layer of **1028 neurons**. This architecture resulted in a major improvement in the **Macro F1 score**, which is used as a benchmark on the leaderboard for [SemEval 2025 Task 11 Track A](https://github.com/emotion-analysis-project/SemEval2025-task11).

## Task Description

Given a target text snippet, the goal is to predict the perceived emotion(s) of the speaker. Specifically, for each text snippet, determine whether each of the following emotions applies:

- **Joy**
- **Sadness**
- **Fear**
- **Anger**
- **Surprise**
- **Disgust**

Each emotion is represented as a binary label:
- `1` indicates the presence of the emotion.
- `0` indicates the absence of the emotion.

> **Note:** For some languages (e.g., English), the set of perceived emotions includes only 5 emotions (joy, sadness, fear, anger, surprise) and does not include disgust.

## Dataset

The datasets provided by SemEval include the following splits:
- **Train**
- **Test**
- **Dev**

## Languages and Macro F1 Scores

In this repository, models were trained for the following languages along with their respective Macro F1 scores:

- Hindi
- English
- Russian
- German (deu)
- Amharic (amh)
- Arabic (ary)
- Marathi (mar)
- Chinese (chn)
- Ukrainian (ukr)
- Romanian (ron)
- Oromo (orm)
- Spanish (esp)
- Hausa (hau)

---

## Evaluation Scores

Below are the evaluation scores for each language track (Track A):

### Amharic (amh) Track A

- **Overall F1 Score:**
  - **Micro:** `0.7133`
  - **Macro:** `0.6847`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.6693`
  - Disgust: `0.7476`
  - Fear: `0.5192`
  - Joy: `0.7708`
  - Sadness: `0.7270`
  - Surprise: `0.6740`
  
- **Note:** Files format checked successfully.

---

### German (deu) Track A

- **Overall F1 Score:**
  - **Micro:** `0.7248`
  - **Macro:** `0.6651`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.8256`
  - Disgust: `0.7286`
  - Fear: `0.5486`
  - Joy: `0.7605`
  - Sadness: `0.6845`
  - Surprise: `0.4428`
  
- **Note:** Files format checked successfully.

---

### English (eng) Track A

- **Overall F1 Score:**
  - **Micro:** `0.7603`
  - **Macro:** `0.7340`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.6483`
  - Fear: `0.8235`
  - Joy: `0.7325`
  - Sadness: `0.7473`
  - Surprise: `0.7182`
  
- **Note:** Files format checked successfully.

---

### Spanish (esp) Track A

- **Overall F1 Score:**
  - **Micro:** `0.8059`
  - **Macro:** `0.8054`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.7263`
  - Disgust: `0.7984`
  - Fear: `0.8313`
  - Joy: `0.8768`
  - Sadness: `0.8316`
  - Surprise: `0.7677`
  
- **Note:** Files format checked successfully.

---

### Hindi (hin) Track A

- **Overall F1 Score:**
  - **Micro:** `0.8903`
  - **Macro:** `0.8901`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.8665`
  - Disgust: `0.8718`
  - Fear: `0.9072`
  - Joy: `0.8992`
  - Sadness: `0.8815`
  - Surprise: `0.9147`
  
- **Note:** Files format checked successfully.

---

### Marathi (mar) Track A

- **Overall F1 Score:**
  - **Micro:** `0.8599`
  - **Macro:** `0.8657`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.8317`
  - Disgust: `0.8984`
  - Fear: `0.8993`
  - Joy: `0.8293`
  - Sadness: `0.8429`
  - Surprise: `0.8923`
  
- **Note:** Files format checked successfully.

---

### Oromo (orm) Track A

- **Overall F1 Score:**
  - **Micro:** `0.6425`
  - **Macro:** `0.5628`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.5104`
  - Disgust: `0.5798`
  - Fear: `0.2921`
  - Joy: `0.8007`
  - Sadness: `0.4622`
  - Surprise: `0.7317`
  
- **Note:**
  - Could not find prediction file for Portuguese (Brazil) in the submission folder.
  - Files format checked successfully.

---

### Russian (rus) Track A

- **Overall F1 Score:**
  - **Micro:** `0.8833`
  - **Macro:** `0.8831`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.8741`
  - Disgust: `0.8631`
  - Fear: `0.9524`
  - Joy: `0.9191`
  - Sadness: `0.8550`
  - Surprise: `0.8347`
  
- **Note:**
  - Could not find prediction files for:
    - Somali
    - Sundanese
    - Tatar
    - Tigrinya
    - Arabic (Algerian)
  - Files format checked successfully.

---

### Arabic (ary) Track A

- **Overall F1 Score:**
  - **Micro:** `0.5847`
  - **Macro:** `0.5550`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.5699`
  - Disgust: `0.4746`
  - Fear: `0.5000`
  - Joy: `0.6897`
  - Sadness: `0.6848`
  - Surprise: `0.4110`
  
- **Note:** Files format checked successfully.

---

### Chinese (chn) Track A

- **Overall F1 Score:**
  - **Micro:** `0.7295`
  - **Macro:** `0.6119`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.8342`
  - Disgust: `0.4357`
  - Fear: `0.4496`
  - Joy: `0.8748`
  - Sadness: `0.6016`
  - Surprise: `0.4756`
  
- **Note:** Files format checked successfully.

---

### Hausa (hau) Track A

- **Overall F1 Score:**
  - **Micro:** `0.6845`
  - **Macro:** `0.6770`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.6078`
  - Disgust: `0.7726`
  - Fear: `0.7478`
  - Joy: `0.6733`
  - Sadness: `0.7317`
  - Surprise: `0.5288`
  
- **Note:**
  - Could not find prediction files for:
    - Kinyarwanda
    - Nigerian Pidgin
    - Portuguese (Mozambique)
    - Swahili
    - Swedish
  - Files format checked successfully.

---

### Ukrainian (ukr) Track A

- **Overall F1 Score:**
  - **Micro:** `0.6581`
  - **Macro:** `0.6012`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.3885`
  - Disgust: `0.5605`
  - Fear: `0.7692`
  - Joy: `0.7021`
  - Sadness: `0.7178`
  - Surprise: `0.4691`
  
- **Note:**
  - Could not find prediction files for:
    - Emakhuwa
    - Yoruba
    - Igbo
  - Files format checked successfully.

---

### Romanian (ron) Track A

- **Overall F1 Score:**
  - **Micro:** `0.7583`
  - **Macro:** `0.7403`
  
- **Emotion-level Macro F1 Scores:**
  - Anger: `0.6012`
  - Disgust: `0.7370`
  - Fear: `0.8649`
  - Joy: `0.9618`
  - Sadness: `0.7683`
  - Surprise: `0.5086`


