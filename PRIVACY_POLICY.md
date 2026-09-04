---
title: Privacy Policy for Infinite Journeys
---

# Privacy Policy for Infinite Journeys

**Last updated:** September 3, 2026

This privacy policy applies to the Infinite Journeys Android app (package name `com.bcgames.infinitejourneys`). It does not apply to Infinite Bedtime Stories or any other app.

Infinite Journeys is a single-player AI adventure. You create a character, pick a narrator, and play a generated story. There is no account sign-up and no ads. Token packs are sold as in-app purchases through Google Play Billing.

If you have questions, contact: **jcrawford101381@gmail.com**

## 1. What this app does not collect

The app does not offer email or password sign-up. We do not ask for your name, email, phone number, or payment card in the app. Card payments are handled by Google Play, not by us. We do not send Google Play an `obfuscatedAccountId`. We do not include advertising SDKs, analytics SDKs, crash-reporting SDKs, or Firebase. We do not request microphone, camera, location, contacts, or advertising ID permissions.

## 2. Information stored on your device

The app stores, in the app’s private storage on your device:

- Character roster (up to 10), including name, age, gender, species, appearance details, and generated portrait images
- Your selected narrator voice
- Your first-run LaunchConsentCard acceptance and a separate 13+ age attestation (see section 7)
- An app-generated player ID (a random UUID in `player-id.txt`)
- A local copy of your token balance (`wallet-local.json`)

You can delete a saved character in the app. Uninstalling the app removes this local data from the device (a new player ID is created on a later install unless a device backup restores it).

If Android backup is enabled on your device, this local data may be included in your device backup (for example, a Google backup of the app).

## 3. Information sent off the device

Internet access is required to generate new chapters, portraits, live narration, and video, and to buy or refresh tokens. Bundled narrator samples can still play without a network connection.

**Player ID and wallet.** The app sends your player ID to our token/billing API as an `X-Player-Id` header. We store on our server, in a SQLite wallet database:

- `wallets`: player ID and token balance
- `purchases`: Google Play `purchase_token` (primary key), player ID, product ID, and token grant
- a `prepaid` table used for the wallet

**Generation.** Story, character, and portrait prompts are sent to our API, which **forwards** them to the generation providers in section 5. We do not store those prompts. Generated media may be written under `data/media/{player_id}/` on our server and is deleted after about one hour.

A forwarded generation request may include:

- Character details you entered (name, appearance, species, and age **only if it is a whole number 18 or greater** from the **Age (18+)** field). Blank and under-18 values are rejected and do **not** leave the device for Save, Begin, portrait, or story prompts
- Genre and story choices you pick
- Prior chapter text needed to continue the story
- Generated portrait or scene images used as references for later images or video
- Chapter text sent to a text-to-speech provider for narration

Providers, Google Play, and our API receive technical data such as IP address as part of HTTPS. We do not sell this information.

We do not claim that AI providers delete prompts immediately or that they never train on API data. Their own terms and privacy policies govern how they handle the content you send.

## 4. Purchases

Token packs are sold through Google Play Billing. Google processes payment under Google’s privacy policy: https://policies.google.com/privacy

After a purchase, the app calls our token/billing API so we can credit your player ID. We store the Play purchase token, product ID, player ID, and token amount in the `purchases` table so we can credit once and refund failed generations when the app requests it.

## 5. Third-party generation providers

Our API may call one or more of the following. Fallbacks are used if a primary provider fails.

- **OpenRouter** — story text, images, narration, and video fallbacks. Privacy: https://openrouter.ai/privacy
- **DeepSeek** — story text fallback. Privacy: https://www.deepseek.com/
- **Google (Gemini / Google AI)** — image and narration fallbacks. Privacy: https://policies.google.com/privacy
- **Fal** — images and scene video. Privacy: https://fal.ai/privacy
- **Cartesia** — narration. Privacy: https://cartesia.ai/privacy
- **OpenAI** — image and narration fallbacks. Privacy: https://openai.com/policies/privacy-policy

Google Play services on your device are subject to Google’s privacy policy: https://policies.google.com/privacy

## 6. Permissions

- **INTERNET** — required to call our API, Google Play, and generation providers.
- **ACCESS_NETWORK_STATE** — declared in the app manifest. The app does not request any other runtime permissions.

## 7. Children

Infinite Journeys is **not** directed at children under 13. The player audience is 13+. It is not a Google Play Families app.

Before you can use the app, you must complete a two-step first-run gate. Both confirmations are stored on the device.

1. **LaunchConsentCard on Home.** A consent card on the Home screen with the button **I am 13+ and I agree**. There is no Cancel control. **PRESS START** does nothing until you accept. Accepting covers that you are 13 or older; that characters and generated likenesses are 18+; that chapter requests go to the Infinite Journeys server and then to third-party AI; and that content is PG-13. The card links to this Privacy Policy and to the Terms of Service. In-app Privacy opens a Custom Tab to https://jcmlsquared.github.io/infinite-journeys-docs/. Terms stay in the app.

2. **13+ age attestation.** After you accept the consent card, a separate 13+ age attestation dialog is shown. You must confirm you are 13 or older. That attestation is stored on the device so it survives the Back button and process death (the app being killed and restarted).

The character age field is labeled **Age (18+)**. Only whole numbers 18 or greater leave the device for Save, Begin, portrait, and story prompts. Blank and under-18 values are rejected and are **not** sent to generation providers, including for portraits and scene images. Do not use the app to create or generate images of children.

If you believe a child under 13 has used the app, contact **jcrawford101381@gmail.com**.

## 8. Your choices

- Delete a character from the roster in the app.
- Manage or request refunds for Play purchases through Google Play.
- Uninstall the app to remove local data from that device.
- Email **jcrawford101381@gmail.com** to request deletion of the server wallet and purchase records for your player ID. We do not offer email sign-up, so there is no in-app account-deletion flow. Because prompts are not stored on our server, we cannot delete copies generation providers may retain.

## 9. Data safety summary (Google Play)

For Google Play’s Data safety form, this app:

- Does not collect your name, email, payment card, location, contacts, or advertising ID
- Offers in-app purchases (token packs) processed by Google Play
- Collects an app-generated player ID and in-app purchase records (Play purchase token, product ID, token grant) on our token/billing server, for app functionality
- Stores user-generated character content and a token balance on the device
- Forwards user-generated prompts to generation providers (we do not store the prompts; generated media on our server is kept about one hour)
- Does not sell data or use it for advertising
- Does not include ads

## 10. Changes

We may update this policy. The “Last updated” date at the top will change. The current version will be posted at https://jcmlsquared.github.io/infinite-journeys-docs/

## 11. Contact

Jeffrey Crawford  
Email: jcrawford101381@gmail.com
