# Pinorama Privacy Policy

**Effective date: July 17, 2026**

> **Pinorama was previously known as NomadMap during early beta — same app,
> same operator (NomadZach Studios).**

## Who we are

Pinorama is a mobile travel app for iOS and Android that lets you save
places from social media posts to your own personal travel map. It is made
by NomadZach Studios (currently operating as a sole proprietorship while a
company entity is being formalized). If you have any question about this
policy or your data, email us at **admin@nomadzachstudios.com** — a real
person reads it.

Pinorama is in **beta**. You can use the whole app **without an account**,
in which case your data stays on your device and we hold almost none of it.
If you **create an account** (optional), your saved places and profile are
stored in our cloud database so they survive a lost phone and sync between
your devices. This policy explains both cases, plus what will change as
further planned features launch. We will update this policy — and tell you —
before any of the "planned" items below go live.

## What we collect

### Without an account (local-only — the default)

**If you don't sign in, everything you put into Pinorama stays on your
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
  code** to your email instead of using passwords — Pinorama has no password
  to store.
- **Your profile** from onboarding: display name, avatar emoji, home base,
  traveler types, interests, and your Pinorama passport number.
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
- **Game nights you post (venue promo — PUBLIC)** — if you tell us your venue
  will air a sports fixture (the "log a game night" card in the Work hub), we
  store the venue name, the sport and fixture, the showing time you type, a
  free-entry flag, and **a map location for the venue**. The location comes
  from your device **only if you tick "pin at my current location"**, which
  asks for your device's location permission and reads it once; if you don't,
  the game night stays on your phone and is not uploaded. A game night with a
  location is **public promo content**: it appears on the map for **everyone
  using the app, including people without accounts**. The app shows the venue
  name with it, not your name or handle, but it is stored with your account.
  Game nights **expire off the map automatically after 7 days**, you can
  remove your own at any time in the Work hub (it disappears for everyone
  immediately), and deleting your account erases them entirely.
- **Events you create (PUBLIC ones)** — the "create" button on the map lets you
  post an event (a meet-up, game night, drinks night, or club night): we store
  the kind, a title, the place name, **its map location**, and the date/time you
  set. You choose **public** or **private** for each event. A **private** event
  **never leaves your phone** — it is not uploaded; you invite people yourself
  through your phone's normal share sheet. A **public** event is **public promo/
  social content**: it appears on the map for **everyone using the app,
  including people without accounts**, so nearby travelers can find and join it.
  Public events show the event title and place, are stored with your account,
  **expire off the map automatically** (after the event's time, or after 7 days
  if you set no time), can be removed by you at any time, and are erased when you
  delete your account. Whether an event is public or private, when you **share an
  invite** the message is created on your device and sent by you through your own
  apps — we don't send it or see who you send it to.

Your device stays the primary copy; the cloud copy is a synced backup. Syncing
happens when you sign in and when you open the app. If you sign out, your local
data is left untouched. Your saved places, profile, and points stay private to
your account. **Posts, likes, and game nights are the exceptions:** a text post
you publish is visible to other signed-in users whenever your profile is public
— and during beta, accounts are public by default. Likes are visible too: every
post shows its like count, and the fact that your account liked a post can be
seen by other signed-in users. **Game nights go further: they're shown on the
map to everyone using the app, even people without accounts** (they're venue
promo content — that's their whole point). You can delete any of your own posts
or game nights at any time, and deleting your account removes your posts, likes,
and game nights along with everything else.

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
- **Location services** — strictly opt-in and off by default; the app works
  without it. **One use is live today:** when you log a game night you can
  tick "pin at my current location," which asks your device's permission and
  reads your location **once** to place your venue's pin — it is never read
  in the background. (The map's "game night near you" card uses the area of
  the map you're looking at, not your device's location.) Broader uses —
  localizing your feed, nearby alerts via push — remain planned and opt-in.
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
| Google Places API | Provides real place details — star ratings, review counts, price level, opening hours, photos, and review snippets — via our server | The place's name and coordinates only, sent from our server. Your identity, account, and precise device location are never sent to Google |
| TikTok / Instagram / X oEmbed | Fetches a shared post's public caption | The post link, requested from your device |
| Anthropic (Claude API) | Extracts place names from captions, via our server | Caption text only, no identity attached |
| Supabase (AWS, Sydney) | Hosts our accounts database and cloud sync (region ap-southeast-2, Australia) | Your email, profile, saved places, points activity, and any posts, likes, and game nights you create — only when you're signed in |
| Apple / Google / Expo | Standard app distribution and app infrastructure | Standard app-store and crash-level technical data per their own policies |

Each of these services has its own privacy policy that governs its side of
the exchange.

**About Google place content:** ratings, review counts, price levels, hours,
photos, and review snippets shown on place pages are supplied by Google and
displayed with "Powered by Google" attribution; review snippets link back to
Google Maps. Our server caches this place content briefly (up to 7 days per
place) to avoid repeated lookups — the cache holds place facts only, never
anything about you. Google's own terms and privacy policy govern that content.

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
  your Pinorama data — it's the only place it exists. If you have an account,
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

## Dating & travel-buddy discovery (optional)

Pinorama includes an optional dating / travel-buddy feature. It is **off
until you opt in** (create a discovery profile and turn discovery on), and
it requires an account and being 18 or older.

If you opt in, we store: your short bio, your interest tags, an optional
display name, your gender and who you want to meet (both optional — used
to decide who appears in whose deck), up to **5 photos you choose to
upload** (stored on our servers and deleted with your account; each photo
lives at an unguessable address), your city, your search radius, and —
only when you tap the share-location button — an **approximate position**
from a single opt-in device-location read, saved rounded to roughly a city
block (~110 m). We never store your exact GPS coordinates for discovery
and never read your location in the background.

What other travelers can see: signed-in users searching nearby see your
display name, bio, interests, photos, gender (if you set one), city, and a
distance rounded to whole kilometers,
computed from a further-blurred (~1 km grid) position — never your legal
name, email, exact location, or coordinates. **Who you want to meet is
never shown to anyone** — it is only a filter. Who liked you is not shown
to anyone; likes are stored server-side only to detect a mutual match. A
match is created only when two people like each other, and each match is
visible only to the two people in it.

Blocking is two-way and immediate: blocks are stored on your device and on
the server, and a blocked traveler no longer appears to you nor you to
them. Reports are currently noted on your device while the full review
pipeline is built — blocking is the instant protection.

You can turn discovery off at any time (your profile stops being served to
others), and deleting your account permanently deletes your discovery
profile, likes, matches, and blocks.

## City chat rooms

Pinorama has **city chat rooms** — one public room per city, open to signed-in
travelers. Joining a room is **always your explicit choice**: the app may
suggest a room based on places you've already saved or the base city on your
profile (never from background location tracking), but you are never added to
a room without tapping join, and dismissing a suggestion means that city
won't be suggested again.

If you send a message, we store the message text, the room's city, your
account id, and the time — and every signed-in traveler in that room can see
the message with your display name. An anti-spam limit caps how fast anyone
can post. You can delete your own messages at any time (they disappear from
the room), block other travelers (their messages stop appearing for you, on
your device, immediately), and report messages — reports are noted on your
device while the full review pipeline is built. Deleting your account
permanently deletes your chat messages.

## Children

Pinorama is not directed at anyone under 18, and you must be 18 or older
to use it (the optional dating / travel-buddy feature is strictly 18+). We do not
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
maps, and meetups remain planned. **The app was also renamed from NomadMap to
Pinorama** — same app, same operator (NomadZach Studios), same data handling;
only the name changed.

**Changelog — July 16, 2026:** added **game nights** — signed-in venue
partners can post that their venue will air a sports fixture (venue name,
sport/fixture, showing time, free-entry flag, and a venue map location taken
once from your device only if you tick "pin at my current location"). Game
nights are **public promo content shown on the map to everyone, including
people without accounts**; they display the venue name (not your name or
handle), expire off the map automatically after 7 days, can be removed by you
at any time, and are erased with your account. This is also the first live
use of device location — a single opt-in read to pin your own venue, never in
the background; the "game night near you" card is based on the map area
you're viewing, not your device's location. Also added **map events**: you can
create meet-ups / game / drinks / club nights and choose public or private per
event — a public event is shown on the map to everyone (title + place, expires
automatically, removable, erased with your account); a private event never
leaves your phone and is shared only by an invite you send yourself. Sharing an
invite happens on your device through your own apps; we don't send it or see the
recipients. **Map events** work the same way:
a public event you create is shown on the map to everyone (private events never
leave your phone), and the optional "use my current location" when creating one
is a single opt-in read to pin your event — the "happening near you" card uses
the map area you're viewing, not your device's location.

**Changelog — July 17, 2026:** place pages now show details supplied by
**Google** — ratings, review counts, price levels, opening hours, photos and
review snippets, with "Powered by Google" attribution (see Third-party
services). Also switched on **dating & travel-buddy discovery** (optional,
18+): the new section above describes exactly what an opt-in discovery
profile stores and what other travelers can and cannot see — approximate
distance only, never your exact location, name, or email. Later the same
day, discovery profiles gained an optional **display name**, optional
**gender and who-you-want-to-meet** (a private filter, never shown), and
up to **5 self-uploaded photos** (stored by us, deleted with your account)
— the section above describes all of it. Also switched on **city chat
rooms** (new section above): public per-city rooms for signed-in travelers,
joined only by your explicit tap — suggestions come from your saved places
or base city, never background location; messages are deletable by you and
erased with your account.

## Contact

**NomadZach Studios**
admin@nomadzachstudios.com
