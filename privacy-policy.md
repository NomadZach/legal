# NomadMap Privacy Policy

**Effective date: July 12, 2026**

## Who we are

NomadMap is a mobile travel app for iOS and Android that lets you save
places from social media posts to your own personal travel map. It is made
by NomadZach Studios (currently operating as a sole proprietorship while a
company entity is being formalized). If you have any question about this
policy or your data, email us at **admin@nomadzachstudios.com** — a real
person reads it.

NomadMap is in **beta**. That matters for privacy, because right now the
app is built so that we hold almost none of your data at all. This policy
explains what happens today, and what will change as planned features
launch. We will update this policy — and tell you — before any of the
"planned" items below go live.

## What we collect

### Right now (beta)

**Everything you put into NomadMap stays on your device.** There are no
user accounts and no server-side storage of your personal data. Data the
app handles locally includes:

- Places you save (name, coordinates, category)
- Links to social media posts you share or paste in, and their captions
- Your answers to the onboarding questions (travel style, preferences)
- App settings and progress (e.g. which tips you've seen)

None of this is uploaded to us. We can't see it, and we don't have it.

**One thing leaves your device: figuring out where a place is.** When you
save a post, the app needs to turn text into a map pin:

- The **place text** (e.g. "Bánh Mì Phượng, Hội An") is sent to
  OpenStreetMap's Nominatim geocoding service to look up coordinates. Only
  the place text is sent — not your identity, since you don't have one in
  the app.
- If you share a **TikTok or X (Twitter) link**, the app fetches that
  post's public caption from the platform's official oEmbed endpoint (a
  public lookup service those platforms provide). The platform sees the
  request came from your device, the same as if you opened the link in a
  browser.
- In an **upcoming version**, caption text will also be sent to Anthropic's
  Claude API via our server so an AI model can extract the place name and
  city from it. The caption text goes through — no account identity or
  personal details are attached, because there are no accounts yet.

### Planned (not live yet — we'll update this policy first)

- **User accounts and cloud sync** — email/password or similar sign-in, and
  your saved maps synced to the cloud so they survive a lost phone. We plan
  to use Supabase, hosted in the Australia/Singapore region.
- **Social features** — public profiles, shared maps, posts, meetups.
  Anything you choose to make public will be visible to other users.
- **Location services** — strictly opt-in, used to localize your feed and
  send nearby alerts. Off by default; the app works without it.
- **Push notifications** — opt-in via your device's normal permission
  prompt.
- **Phone or WhatsApp number** — optional, only for account recovery if you
  get locked out.
- **Payments for bookings** — handled by established payment processors
  (e.g. Stripe). We would never see or store your full card number.

## How we use your data

Today: to make the app work on your device and to place pins on your map.
That's the whole list.

We do **not** sell personal data. We do **not** track you across other
apps or websites. There is **no analytics or advertising tracking** in the
beta. If we ever add analytics, it will be a privacy-respecting option
(anonymized/aggregated) and disclosed here first.

## Third-party services

| Service | What it does | What it receives |
|---|---|---|
| OpenStreetMap Nominatim | Turns place text into map coordinates | The place text only |
| TikTok / X oEmbed | Fetches a shared post's public caption | The post link, requested from your device |
| Anthropic (Claude API) — upcoming | Extracts place names from captions, via our server | Caption text only, no identity attached |
| Apple / Google / Expo | Standard app distribution and app infrastructure | Standard app-store and crash-level technical data per their own policies |
| Supabase — planned | Account and cloud-sync hosting (Australia/Singapore region) | Account details and synced data, once accounts exist |

Each of these services has its own privacy policy that governs its side of
the exchange.

## Storage and security

In the beta, your data lives in your phone's local app storage, protected
by your device's own security (passcode, encryption). Because there's no
server copy, there's also nothing for us to leak — but it also means **we
can't recover your data if you delete the app or lose your phone**.
Cloud sync, when it arrives, will fix that trade-off, with account data
protected by industry-standard encryption in transit and at rest.

## Your rights and choices

- **Access:** in the beta, everything we "have" is already in front of you
  inside the app.
- **Deletion:** in the beta, deleting the app deletes all your NomadMap
  data — it goes with the app, because that's the only place it exists.
  Once accounts launch, you'll be able to delete your account and data
  in-app, or by emailing admin@nomadzachstudios.com.
- If you're in the EU/EEA/UK, the GDPR gives you rights to access, correct,
  delete, and port your data. If you're a California resident, the CCPA
  gives you similar rights, including the right to know we don't sell your
  data (we don't). Given the beta's local-only design, most of these rights
  are exercised by simply using or deleting the app — but you can always
  email us and we'll help.

## Children

NomadMap is not directed at anyone under 18, and you must be 18 or older
to use it (social and dating-style features are planned). We do not
knowingly collect data from minors; if you believe a minor is using the
app, contact us.

## Changes to this policy

When planned features launch or anything else changes, we'll update this
policy, change the effective date at the top, and flag meaningful changes
in the app. The current version always lives with the app and in our
project repository.

## Contact

**NomadZach Studios**
admin@nomadzachstudios.com
