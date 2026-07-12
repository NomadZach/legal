# NomadMap Privacy Policy

**Effective date: July 12, 2026**

## Who we are

NomadMap is a mobile travel app for iOS and Android that lets you save
places from social media posts to your own personal travel map. It is made
by NomadZach Studios (currently operating as a sole proprietorship while a
company entity is being formalized). If you have any question about this
policy or your data, email us at **admin@nomadzachstudios.com** — a real
person reads it.

NomadMap is in **beta**. You can use the whole app **without an account**,
in which case your data stays on your device and we hold almost none of it.
If you **create an account** (optional), your saved places and profile are
stored in our cloud database so they survive a lost phone and sync between
your devices. This policy explains both cases, plus what will change as
further planned features launch. We will update this policy — and tell you —
before any of the "planned" items below go live.

## What we collect

### Without an account (local-only — the default)

**If you don't sign in, everything you put into NomadMap stays on your
device.** There is no server-side copy of your personal data. Data the app
handles locally includes:

- Places you save (name, coordinates, category, and the caption/notes)
- Links to social media posts you share or paste in, and their captions
- Your answers to the onboarding questions (travel style, preferences)
- App settings and progress (e.g. which tips you've seen)

We can't see any of this, and we don't have it.

### With an account (optional cloud sync)

**Creating an account is optional** — the app is fully usable signed out. If
you do sign in, we store a copy of some of your data on our cloud database
(Supabase — see the table below) so it survives a lost phone and syncs
between your devices. When you're signed in we hold:

- **Your email address**, used to sign you in. We send a **6-digit one-time
  code** to your email instead of using passwords — NomadMap has no password
  to store.
- **Your profile** from onboarding: display name, avatar emoji, home base,
  traveler types, interests, and your NomadMap passport number.
- **Your saved places**, including their names, **coordinates**, categories,
  the original post links, and their **captions/notes**.
- **Points activity** — a log of in-app points you earn (e.g. save
  milestones). Points are in-app only and are not money (see the Terms).
- **Posts and likes** — text posts you choose to publish in the app. A post
  contains the text you write (a caption), an optional place name with its
  coordinates, and timestamps. Your posts, and a record of which posts you've
  liked, are stored with your account.
- **Social handles and self-reported follower counts** — the @handles you type
  in for platforms you link (Instagram, TikTok, X, Facebook, YouTube) and any
  follower counts you enter for them, stored with your account and shown to you
  in the app as an aggregated "reach" on your profile. Today only you can see
  them; when public creator profiles launch they'll appear there, and we'll
  update this policy first. These are **self-reported and NOT
  verified with the platforms** — we don't connect to your social accounts or
  read anything from them to produce these numbers. You can change or remove them
  anytime by unlinking the platform, which deletes them from your account.

Your device stays the primary copy; the cloud copy is a synced backup. Syncing
happens when you sign in and when you open the app. If you sign out, your local
data is left untouched. Your saved places, profile, and points stay private to
your account. **Posts and likes are the exception:** a text post you publish is
visible to other signed-in users whenever your profile is public — and during
beta, accounts are public by default. Likes are visible too: every post shows
its like count, and the fact that your account liked a post can be seen by other
signed-in users. You can delete any of your own posts at any time, and deleting
your account removes your posts and likes along with everything else.

**One thing leaves your device either way: figuring out where a place is.**
When you save a post, the app needs to turn text into a map pin:

- The **place text** (e.g. "Bánh Mì Phượng, Hội An") is sent to
  OpenStreetMap's Nominatim geocoding service to look up coordinates. Only
  the place text is sent.
- If you share a **TikTok, Instagram, or X (Twitter) link**, the app fetches
  that post's public caption from the platform's official oEmbed endpoint (a
  public lookup service those platforms provide; it only works for public
  posts). The platform sees the request came from your device, the same as
  if you opened the link in a browser.
- If the place still isn't clear, the **caption text** is sent to Anthropic's
  Claude API, through our server, so an AI model can extract the place name
  and city from it. Only the caption text is sent — we don't attach your
  account or profile to it.

### Planned (not live yet — we'll update this policy first)

- **More social features** — following other users, shared/creator maps, and
  meetups. These aren't built yet (text posts, described above, are the one
  social feature live today). Anything you choose to make public will be
  visible to other users.
- **Location services** — strictly opt-in, used to localize your feed and
  send nearby alerts. Off by default; the app works without it.
- **Push notifications** — opt-in via your device's normal permission
  prompt.
- **Phone or WhatsApp number** — optional, only for account recovery if you
  get locked out.
- **Payments for bookings** — handled by established payment processors
  (e.g. Stripe). We would never see or store your full card number.

## How we use your data

To make the app work, place pins on your map, and — if you have an account —
sync your saved places and profile across your devices and back them up.
That's the whole list.

We do **not** sell personal data. We do **not** track you across other
apps or websites. There is **no analytics or advertising tracking** in the
beta. If we ever add analytics, it will be a privacy-respecting option
(anonymized/aggregated) and disclosed here first.

## Third-party services

| Service | What it does | What it receives |
|---|---|---|
| OpenStreetMap Nominatim | Turns place text into map coordinates | The place text only |
| TikTok / Instagram / X oEmbed | Fetches a shared post's public caption | The post link, requested from your device |
| Anthropic (Claude API) | Extracts place names from captions, via our server | Caption text only, no identity attached |
| Supabase (AWS, Sydney) | Hosts our accounts database and cloud sync (region ap-southeast-2, Australia) | Your email, profile, saved places, points activity, and any posts and likes you create — only when you're signed in |
| Apple / Google / Expo | Standard app distribution and app infrastructure | Standard app-store and crash-level technical data per their own policies |

Each of these services has its own privacy policy that governs its side of
the exchange.

## Storage and security

If you don't have an account, your data lives only in your phone's local app
storage, protected by your device's own security (passcode, encryption).
There's no server copy to leak — but it also means **we can't recover your
data if you delete the app or lose your phone**.

If you have an account, a copy is also stored on Supabase, protected by
industry-standard encryption in transit and at rest, with database access
rules that keep your places and profile readable only by you. That copy is
what lets us restore your map on a new phone.

## Your rights and choices

- **Access:** everything we hold is visible to you inside the app — your
  places, your profile, and your points. If you have an account and want an
  exported copy, email us.
- **Deletion:** if you don't have an account, deleting the app deletes all
  your NomadMap data — it's the only place it exists. If you have an account,
  use the **"delete my account" button in the Profile screen** — it
  permanently erases your cloud account and everything stored for it
  (including your posts and likes) immediately. You can also delete any
  individual post yourself inside the app, or **email
  admin@nomadzachstudios.com** and we'll action the deletion for you
  promptly. Deleting your account does not touch the data saved on your own
  phone.
- If you're in the EU/EEA/UK, the GDPR gives you rights to access, correct,
  delete, and port your data. If you're a California resident, the CCPA
  gives you similar rights, including the right to know we don't sell your
  data (we don't). You can exercise these rights by using or deleting the app
  (local data) or by emailing us (account data), and we'll help either way.

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

**Changelog — July 12, 2026:** added optional accounts with email
one-time-code sign-in and cloud sync of your saved places and profile to
Supabase (Sydney, Australia); documented the in-app points activity log and
the email-based account-deletion path; and clarified that the TikTok/X
caption lookup and AI place extraction happen today rather than "upcoming."
Also went live today: **social posts** — signed-in users can publish text
posts (with an optional place and coordinates) that are visible to other
signed-in users when your profile is public (public by default in beta),
along with likes, which are likewise visible to signed-in users; you can delete
your own posts, and account deletion removes them. Also added: you can **link
your social handles** (Instagram, TikTok, X, Facebook, YouTube) by typing them
in, along with **self-reported follower counts** that stack into an aggregated
"reach" shown on your own profile screen (visible only to you for now) — these are self-reported and NOT verified
with the platforms, and unlinking a platform deletes them. Following, shared
maps, and meetups remain planned.

## Contact

**NomadZach Studios**
admin@nomadzachstudios.com
