---
title: Privacy Policy for Infinite Journeys
---

# Privacy Policy for Infinite Journeys

**Last updated:** September 2, 2026

This privacy policy applies to the Infinite Journeys Android app (package name `com.bcgames.infinitejourneys`). It does not apply to Infinite Bedtime Stories or any other app.

Infinite Journeys is a single-player AI adventure. You create a character, pick a narrator, and play a generated story. There is no account system and no ads. Token packs are sold as in-app purchases through Google Play Billing.

If you have questions, contact: **jcrawford101381@gmail.com**

## 1. What this app does not collect

We do not create user accounts. We do not ask for your name, email, phone number, or payment card in the app. We do not include advertising SDKs, analytics SDKs, crash-reporting SDKs, or Firebase in this app. We do not request microphone, camera, location, contacts, or advertising ID permissions.

Purchases of token packs are processed by Google Play Billing. You complete payment in Google Play, not by entering card details into Infinite Journeys.

## 2. Information stored on your device

The app stores, in the app's private storage on your device:

- Character roster (up to 10), including name, age, gender, species, appearance details, and generated portrait images
- Your selected narrator voice
- Your confirmation that you are 13 or older (see section 7)

You can delete a saved character in the app. Uninstalling the app removes this local data from the device.

If Android backup is enabled on your device, this local data may be included in your device backup (for example, a Google backup of the app).

## 3. Information sent off the device

Internet access is required to generate new chapters, portraits, live narration, and video, and to complete token pack purchases. Bundled narrator samples can still play without a network connection.

When you save a character, begin a journey, or continue a story, the app sends generation requests **from your device** to the providers listed below.

Depending on the feature, a request may include:

- Character details you entered (name, appearance, species, and age **only if it is a whole number 18 or greater**; under-18 or non-numeric age is not sent)
- Genre and story choices you pick
- Prior chapter text needed to continue the story
- Generated portrait or scene images used as references for later images or video
- Chapter text sent to a text-to-speech provider for narration

Those providers receive the request over HTTPS and, like any website, may also see technical data such as IP address as part of the connection. We do not sell this information. We use it only to generate the adventure you asked for.

We do not claim that providers delete prompts immediately or that they never train on API data. Their own terms and privacy policies govern how they handle the content you send.

When you buy a token pack, the app uses Google Play Billing. The app also calls a token/billing API over HTTPS. Like any HTTPS connection, the host of that API may see technical data such as IP address.

## 4. Purchases

Token packs are sold through Google Play Billing. Google processes those purchases under Google's privacy policy: https://policies.google.com/privacy

The app calls a token/billing API in connection with those purchases.

## 5. Third-party generation providers

The app may call one or more of the following to produce text, images, audio, or video. Fallbacks are used if a primary provider fails.

- **OpenRouter** — story text, images, narration, and video fallbacks. Privacy: https://openrouter.ai/privacy
- **DeepSeek** — story text fallback. Privacy: https://www.deepseek.com/
- **Google (Gemini / Google AI)** — image and narration fallbacks. Privacy: https://policies.google.com/privacy
- **Fal** — images and scene video. Privacy: https://fal.ai/privacy
- **Cartesia** — narration. Privacy: https://cartesia.ai/privacy
- **OpenAI** — image and narration fallbacks. Privacy: https://openai.com/policies/privacy-policy

Google Play services on your device are subject to Google's privacy policy: https://policies.google.com/privacy

## 6. Permissions

- **INTERNET** — required to call the generation providers above and the token/billing API.
- **ACCESS_NETWORK_STATE** — declared in the app manifest. The app does not request any other runtime permissions.

Google Play Billing is used for token pack purchases. That is not a runtime permission.

## 7. Children

Infinite Journeys is **not** directed at children under 13. It is not a Google Play Families app.

Before you can use the app, you must confirm you are 13 or older by checking a checkbox. That confirmation is stored on the device so it survives leaving the screen or restarting the app.

Character age sent to generation providers (models) must be a whole number 18 or greater. Values that are blank, under 18, or not a number of 18+ are **not** sent to any generation provider, including for portraits and scene images. Do not use the app to create or generate images of children.

If you believe a child under 13 has used the app, contact **jcrawford101381@gmail.com**.

## 8. Your choices

- Delete a character from the roster in the app.
- Uninstall the app to remove local data from that device.
- Stop using generation features (they require a network connection).
- Manage or request refunds for token pack purchases through Google Play.

Because generation requests go directly from your device to the providers in section 5, we cannot delete copies those providers may retain. You may also contact those providers under their policies. Email **jcrawford101381@gmail.com** and we will help where we can.

There is no in-app account to delete, because there is no account.

## 9. Data safety summary (Google Play)

For Google Play's Data safety form, this app:

- Does not collect account information, location, contacts, or advertising ID
- Does not ask for payment card details in the app; token pack purchases are processed by Google Play Billing
- Stores user-generated character and story content on the device
- Shares user-generated prompts, character details (with the 18+ age rule in section 3), and related media with the generation providers in section 5, for app functionality only
- Calls a token/billing API in connection with token pack purchases
- Does not sell data or use it for advertising
- Does not include ads
- Includes in-app purchases (token packs via Google Play Billing)

## 10. Changes

We may update this policy. The "Last updated" date at the top will change. The current version will be posted at https://jcmlsquared.github.io/infinite-journeys-docs/

## 11. Contact

Jeffrey Crawford  
Email: jcrawford101381@gmail.com
