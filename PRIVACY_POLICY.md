---
title: Privacy Policy for Infinite Journeys
---

# Privacy Policy for Infinite Journeys

**Last updated:** August 31, 2026

This privacy policy applies to the Infinite Journeys Android app (package name `com.bcgames.infinitejourneys`). It does not apply to Infinite Bedtime Stories or any other app.

Infinite Journeys is a single-player AI adventure. You create a character, pick a narrator, and play a generated story. There is no account system, no ads, and no in-app purchases.

If you have questions, contact: **jcrawford101381@gmail.com**

## 1. What this app does not collect

We do not create user accounts. We do not ask for your name, email, phone number, or payment card in the app. We do not include advertising SDKs, analytics SDKs, crash-reporting SDKs, or Firebase in this app. We do not use Google Play Billing. We do not request microphone, camera, location, contacts, or advertising ID permissions.

## 2. Information stored on your device

The app stores, in the app's private storage on your device:

- Character roster (up to 10), including name, age, gender, species, appearance details, and generated portrait images
- Your selected narrator voice

You can delete a saved character in the app. Uninstalling the app removes this local data from the device.

If Android backup is enabled on your device, this local data may be included in your device backup (for example, a Google backup of the app). We do not operate a separate cloud account that stores your roster or stories.

## 3. Information sent off the device

Internet access is required to generate new chapters, portraits, live narration, and video. Bundled narrator samples can still play without a network connection.

When you save a character, begin a journey, or continue a story, the app sends generation requests **from your device** to the providers listed below. We do not operate our own backend that stores your prompts, stories, portraits, or audio.

Depending on the feature, a request may include:

- Character details you entered (name, appearance, species, and age **only if it is a whole number 13 or greater**; under-13 or non-numeric age is not sent)
- Genre and story choices you pick
- Prior chapter text needed to continue the story
- Generated portrait or scene images used as references for later images or video
- Chapter text sent to a text-to-speech provider for narration

Those providers receive the request over HTTPS and, like any website, may also see technical data such as IP address as part of the connection. We do not sell this information. We use it only to generate the adventure you asked for.

We do not claim that providers delete prompts immediately or that they never train on API data. Their own terms and privacy policies govern how they handle the content you send.

## 4. Third-party generation providers

The app may call one or more of the following to produce text, images, audio, or video. Fallbacks are used if a primary provider fails.

- **OpenRouter** — story text, images, narration, and video fallbacks. Privacy: https://openrouter.ai/privacy
- **DeepSeek** — story text fallback. Privacy: https://www.deepseek.com/
- **Google (Gemini / Google AI)** — image and narration fallbacks. Privacy: https://policies.google.com/privacy
- **Fal** — images and scene video. Privacy: https://fal.ai/privacy
- **Cartesia** — narration. Privacy: https://cartesia.ai/privacy
- **OpenAI** — image and narration fallbacks. Privacy: https://openai.com/policies/privacy-policy

Google Play services on your device are subject to Google's privacy policy: https://policies.google.com/privacy

## 5. Permissions

- **INTERNET** — required to call the generation providers above.
- **ACCESS_NETWORK_STATE** — declared in the app manifest. The app does not request any other runtime permissions.

## 6. Children

Infinite Journeys is **not** directed at children under 13. It is not a Google Play Families app.

Before you can use the app, you must confirm you are 13 or older. That confirmation is stored on the device so it survives leaving the screen or restarting the app.

Character age is a whole number with a minimum of 13. Values that are blank, under 13, or not a number of 13+ are rejected and are **not** sent to any generation provider, including for portraits and scene images. Do not use the app to create or generate images of children.

If you believe a child under 13 has used the app, contact **jcrawford101381@gmail.com**.

## 7. Your choices

- Delete a character from the roster in the app.
- Uninstall the app to remove local data from that device.
- Stop using generation features (they require a network connection).

Because generation requests go directly from your device to the providers in section 4, we cannot delete copies those providers may retain. You may also contact those providers under their policies. Email **jcrawford101381@gmail.com** and we will help where we can.

There is no in-app account to delete, because there is no account.

## 8. Data safety summary (Google Play)

For Google Play's Data safety form, this app:

- Does not collect account information, payment info, location, contacts, or advertising ID
- Stores user-generated character and story content on the device
- Shares user-generated prompts, character details (with the age rule in section 3), and related media with the generation providers in section 4, for app functionality only
- Does not sell data or use it for advertising
- Does not include ads or in-app purchases

## 9. Changes

We may update this policy. The "Last updated" date at the top will change. The current version will be posted at https://jcmlsquared.github.io/infinite-journeys-docs/

## 10. Contact

Jeffrey Crawford  
Email: jcrawford101381@gmail.com
