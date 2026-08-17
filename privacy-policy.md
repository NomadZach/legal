# Pinorama Privacy Policy

**Effective date: August 17, 2026**

> **Pinorama was previously known as NomadMap — same app,
> same operator (NomadZach Studios).**

## Who we are

Pinorama is a mobile travel app for iOS and Android that lets you save
places from social media posts to your own personal travel map. It is made
by NomadZach Studios (currently operating as a sole proprietorship while a
company entity is being formalized). If you have any question about this
policy or your data, email us at **admin@nomadzachstudios.com** — a real
person reads it.

You can use the whole app **without an account**,
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
- **Who invited you (referrals).** If you first open Pinorama through another
  traveler's personal invite link (a `pinorama.app/get?ref=…` link or QR code),
  we record on your profile **which account invited you and when**, so we can
  credit the person who invited you under our rewards program. That link
  between the two accounts **expires 6 months after you join**, is recorded
  **once** (the first invite link wins; it never changes afterwards), and is
  erased with your account. We never see who you *send* an invite to — a
  referral is recorded only if the person you invited actually joins.
- **Your saved places**, including their names, **coordinates**, categories,
  the original post links, and their **captions/notes**.
- **Buddy-trip drafts.** The trips you draft on the travel-buddy board are
  stored with your account so they come back on a new phone. No other traveler
  can ever see them — a draft is private to you, and the day real buddy
  matching ships it will ask you before anything is shared. Deleting a draft
  removes it from our servers, and deleting your account erases them all.
- **Your buddy-profile draft.** The profile you draft for the travel-buddy
  feature (display name, age, home base, bio, interests, what you're looking
  for, relationship status, and whether your info is verified) is stored with
  your account so it comes back on a new phone. No other traveler can read it —
  it is a restore copy for you alone. Whether you are discoverable is NEVER
  restored automatically: that stays off until you turn it on yourself on the
  device. Deleting your account erases it.
- **Points activity** — a log of in-app points you earn (e.g. save
  milestones). Points are in-app only and are not money (see the Terms).
- **Posts and likes** — text posts you choose to publish in the app. A post
  contains the text you write (a caption), an optional place name with its
  coordinates, and timestamps. Your posts, and a record of which posts you've
  liked, are stored with your account.
- **Which posts you've seen** — so the feed can stop showing you the same
  things and, later, rank what you see. We store one row per post per day
  (your account saw this post, on this date), never a moment-by-moment
  record, and no other user can ever see it. Deleting your account erases
  this history with everything else.
- **Comments on posts** — the comment text you write on a feed post (up to 300
  characters), stored with your account and shown publicly on that post to
  other signed-in users, alongside your display name and avatar. Comments run
  through the same profanity filter as city chat before they're stored, are
  rate-limited against flooding, and follow the post they're on: if a post is
  deleted or its author's profile isn't public, its comments disappear with
  it. You can delete any of your own comments at any time, other users can
  report a comment or block you (a block hides everything you write from that
  person), and deleting your account erases all your comments.
- **Partner applications** — if you apply to work with Pinorama (as a driver,
  restaurant, influencer or host), we store which role you applied for and
  when, against your account. The application reuses details you've already
  given us — it collects no new personal information beyond that choice — and
  no other user can see it. Deleting your account erases it.
- **Merchant menus** — if you run a restaurant and publish your menu in the
  app, we store what you publish: the restaurant's name, the dishes with
  their prices and currency, and when you last updated it. A published menu
  is business content and is shown to other signed-in users, like posts you
  publish. If you use the photo scan to fill a menu in, the photo is sent
  through our server to Anthropic's Claude API so an AI model can read the
  dishes off it — the photo itself is not stored, and only the dish list you
  confirm is saved. Deleting your account erases your menus.
- **Follows (who you follow)** — tapping "follow" on another traveler's
  profile stores a follow record (your account → theirs). **Who you follow,
  and who follows you, is visible only to the two people in each pair** —
  other users see only **numbers** (a follower and following count on
  profiles), never the lists themselves. Unfollowing deletes the record
  immediately, and deleting your account erases every follow record in both
  directions.
- **Profile views (counts only)** — when the profile-views feature is on and
  you view another traveler's profile signed in, we store a view record (your
  account → theirs, once per day). **Only the profile's owner ever sees
  anything, and only numbers** — "how many travelers viewed you this week /
  all-time." Who viewed is **never shown to anyone**, including the owner;
  no client can read the raw records. Deleting your account erases every
  view record in both directions.
- **The traveler directory** — signed-in travelers can see a directory of
  travelers who have a public profile and at least one published post. It
  shows only what your public profile already shows: display name, avatar
  emoji, @username, and how many posts you've shared — never your email,
  location, saved places, or linked handles. Accounts are
  public by default (same as posts, above), so publishing a post can list
  you here; deleting your posts or your account removes you.
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
  set. The map location comes from the place you type or search for, **or from
  your device if you tap "use my current location"** in the composer (see
  "Device location" below). You choose **public** or **private** for each event. A **private** event
  **never leaves your phone** — it is not uploaded; you invite people yourself
  through your phone's normal share sheet. A **public** event is **public promo/
  social content**: it appears on the map for **everyone using the app,
  including people without accounts**, so nearby travelers can find and join it.
  Public events show the event title and place, are stored with your account,
  **expire off the map automatically** (after the event's time, or after 7 days
  if you set no time), can be removed by you at any time, and are erased when you
  delete your account. Whether an event is public or private, when you **share an
  invite** the message is created on your device and sent by you through your own
  apps — we don't send it or see who you send it to. (This is about event
  invites. Personal *referral* invite links work differently: if someone joins
  Pinorama through yours, that is recorded — see **"Who invited you"** above.)
- **Maps you publish (PUBLIC — and readable without an account)** — you can pick
  places you have saved and publish them together as a **map** under your creator
  profile. Publishing takes a **copy** of the places you chose: for each pin on the
  published map we store its name, its address, its **coordinates**, its category,
  the **note you wrote on it**, and its position on the map — plus the map's title,
  blurb and cover emoji, stored with your account.
  **A published map is open to anyone: it is listed in the app's creator section, and
  it can be opened from a shared link by someone who has no Pinorama account at all.**
  What they see is: the map's title, blurb, cover emoji, how many pins it has,
  when you last updated it, every pin listed above — and **your creator profile's
  display name, @username and avatar emoji**. Your email address, the saved places you
  did **not** put on the map, and your private notes on those places are never part of
  a published map.
  The pins are a **copy taken at the moment you publish**, so editing or deleting one
  of your own saved places afterwards does not change a map you have already
  published — re-publishing is what updates it. **Unpublishing is what takes a map
  down:** it removes the map and its pins from view immediately. Making your creator
  profile private removes your maps from the public list. Deleting your account erases
  your maps and their pins.
  **Opening a published map records nothing about the person opening it** — there is
  no view counter, and a reader without an account can only read.

Your device stays the primary copy; the cloud copy is a synced backup. Syncing
happens when you sign in and when you open the app. Your saved places, profile,
and points stay private to your account.

**What signing out does — and what it erases.** Signing out leaves most of your
local data alone: your saved places, your profile, your notes, your points and
your trip history all stay on the phone. **There are two deliberate exceptions,
and both are cleared from the device when your session ends.**

**First, your dating data.** That means your date check-ins (including a safety
check-in for a first date), your date plans, your matches, and the cached
profiles of people you were shown are all removed from local storage.

**Second, your conversations.** The copy of your direct-message threads held on
the device is cleared, and so is your chat with the in-app NomadZach assistant,
which contains whatever you typed into it. The internal markers the app uses to
remember how far it has synced your messages are cleared with them.

We do this for both groups for the same reason: so that someone else signing in
on the same phone can never read them. **Please
note this also happens if your session simply expires** — not only when you tap
"sign out" — so if a check-in or a conversation matters to you, don't rely on it
surviving on the device.

**And one more clearing, on a different trigger — when the phone changes hands.**
Your blocked list and your safety reports are treated differently on purpose.
They are **not** cleared when you sign out or when your session expires, because
that would silently un-block people you had blocked just because your connection
dropped — and we would rather you keep that protection. They **are** removed when
a **different account** signs in on the same device, or when the app opens and
finds a different account owns it. Those two cases mean the phone has genuinely
changed hands, and both lists name other people, so they should not follow the
device to its next user. With an account, your blocked list is also saved to
your account so it comes back when you sign in on a new phone. Unblocking
someone removes them there too. Everything else on the phone is untouched. **Posts, likes, comments, and game nights are the exceptions:** a
text post you publish is visible to other signed-in users whenever your profile
is public — and accounts are public by default. Likes are visible
too: every post shows its like count, and the fact that your account liked a
post can be seen by other signed-in users. Comments you write are visible on
the post they're on to the same audience as the post itself. **Game nights go
further: they're shown on the map to everyone using the app, even people
without accounts** (they're venue promo content — that's their whole point).
You can delete any of your own posts, comments, or game nights at any time, and
deleting your account removes your posts, likes, comments, and game nights
along with everything else. **A map you publish is public in the same way** —
see "Maps you publish" above: anyone can open it, including someone with no
account.

**One thing leaves your device either way: figuring out where a place is.**
When you save a post, the app needs to turn text into a map pin:

- The **place text** (e.g. "Bánh Mì Phượng, Hội An") is sent to
  OpenStreetMap's Nominatim geocoding service to look up coordinates. Only
  the place text is sent.
- When a business owner types their venue's address in the partner sign-up,
  the **typed text** is also sent, as they type, to Photon (an open geocoding
  service by komoot running on the same OpenStreetMap data) to suggest
  matching addresses. Only the typed text is sent.
- If you share a **TikTok, Instagram, or X (Twitter) link**, the app fetches
  that post's public caption **and, where the platform provides one, the
  post's small preview image** from the platform's official oEmbed endpoint (a
  public lookup service those platforms provide; it only works for public
  posts). The platform sees the request came from your device, the same as
  if you opened the link in a browser. When a saved place needs a picture,
  your device asks that same service for the post's preview image and then
  loads the image itself from the platform's image server — which that
  server sees in the same way. **We do not store the picture, and we do not
  keep its address on our servers**; your phone remembers it for a few hours
  so it does not have to ask again, and after that it asks afresh. If the
  post has no picture, or we cannot reach the service, the place simply
  shows its coloured category tile.
- If the place still isn't clear, we **ask your permission first** before the
  **caption text** is sent to Anthropic's Claude API. Only if you tap "Use AI"
  on that prompt is the caption sent, through our server, so an AI model can
  extract the place name and city from it. If you tap "Not now," nothing is
  sent to Anthropic and the app falls back to matching the place on its own.
  Only the caption text is ever sent — we don't attach your account or profile
  to it — and you can turn this off any time under Settings → AI place
  detection. (This third-party-AI sharing is disclosed here and asked for
  in-app because it is your personal content leaving our systems.)

### Device location (live — opt-in, foreground only, never in the background)

**Location is off by default and the app works entirely without it. Nothing
reads your location until you have granted your device's location permission
yourself, and we never read it in the background — only while the app is open
on your screen.**

**Please read this part carefully, because it is the bit that surprises
people:** your phone asks for location permission **once**, and the permission
you grant covers the **whole app**, not the one button you tapped. Three
features below ask for it, and each of them only asks at the moment you tap
something. But once you have granted it — for any of them — the app can also
take the quiet city-level reading described in the last bullet without asking
you again. You can withdraw the permission at any time in your phone's
settings, and every one of these features degrades to its non-location
behaviour when you do.

These uses are live in the main app:

- **Pinning a game night at your venue.** When you log a game night you can
  tick "pin at my current location," which asks your device's permission and
  reads your location **once** to place your venue's pin. (The map's "game
  night near you" card uses the area of the map you're looking at, not your
  device's location.)
- **Pinning an event you create on the map.** The map's **create** button
  offers "use my current location" for the event's pin. Tapping it asks your
  device's permission and reads your location **once**. If you type or search
  for a place instead, no reading is taken. A **public** event's pin is then
  shown on the map to everyone — see "Events you create" above.
- **The "Local" tab in the feed.** If you are signed in and tap **Local**,
  the app asks your device's permission and takes **a single reading at that
  moment**. **The Local tab reads nothing before you tap it**, and it reads
  nothing in the background afterwards. **Those
  coordinates are not sent to us.** They are used on your phone to measure
  the distance to the feed posts your phone has already downloaded, so the
  tab can show you the nearby ones; the reading itself never leaves the
  device. If you decline the permission, the tab says location is off and
  offers a try-again button — nothing else changes. Signed out, tapping
  **Local** does not ask for or read your location at all.
- **Guessing which city you are in, to choose what to show you — no prompt,
  and only if you have already granted the permission.** When the **Home**,
  **Book**, **Social**, or **city chats** screens load, the app checks whether location permission is
  *already* granted. If it is not, nothing happens and nothing is asked. If it
  is, the app takes one foreground reading — the position your phone already
  has on hand, or a deliberately **coarse** fresh one if it has none — and
  turns it into a **city name**. That conversion is done by **your phone's own
  built-in map service** (Apple's on iPhone, Google's on Android), so those
  coordinates go from your phone to your phone's platform provider; they are
  **not sent to our servers** and we do not store them. The city name is used
  only to pick which deals to show you, which "popular in …" list to head
  the Book tab with, and **which city chat rooms to suggest to you** (as a list
  on the city-chats screen, and as a single ask-to-join card on the Social
  feed), and it is
  kept in the app's memory for a few minutes so
  the app doesn't repeat the lookup. **Suggesting a city chat is all it does
  there — it does not join you to any room, tell anyone where you are, or send
  anything to us. You join a room by tapping "join", exactly as before.** If you
  would rather this did not happen,
  turn Pinorama's location permission off in your phone's settings — the app
  falls back to your saved places and your profile's home base.

Other optional location features are described in their own sections below:
sharing your location on the map, the drop-off pin when you order a delivery,
and driver live location during an active run.

### Planned (not live yet — we'll update this policy first)

- **Meetups** — organised meet-ups are not built yet. (Text posts, follows and
  the creator maps you publish — all described above — are the social features
  live today.) Anything you choose to make public will be visible to other
  users.
- **Nearby alerts** — being notified about things close to you is still
  planned, and would be opt-in like every other use of location.
- **Push notifications** — opt-in via your device's normal permission
  prompt.
- **Phone or WhatsApp number** — optional, only for account recovery if you
  get locked out.

## How we use your data

To make the app work, place pins on your map, and — if you have an account —
sync your saved places and profile across your devices and back them up.
That's the whole list.

We do **not** sell personal data. We do **not** track you across other
apps or websites. There is **no analytics or advertising tracking** in the
app. If we ever add analytics, it will be a privacy-respecting option
(anonymized/aggregated) and disclosed here first.

**Crash reports (diagnostics).** The app sends automatic **crash reports** so
we can find and fix errors. When the app crashes or hits an internal error, a
report goes to **Sentry** (Functional Software, Inc., USA), our crash-reporting
provider. A report contains technical diagnostics: the error and stack trace,
device model, operating system version, and app version. We do not attach your
name, email, account identity, or precise location to crash reports, and crash
data is never used for advertising or cross-app tracking. Crash reports exist
only to fix defects. Sentry processes this data on our behalf; see Sentry's
privacy documentation at sentry.io/privacy for their practices.

## Third-party services

| Service | What it does | What it receives |
|---|---|---|
| Sentry (Functional Software, Inc.) | Crash reporting — collects error reports when the app crashes so we can fix defects | Crash stack traces, device model, OS version, app version. No name, email, or precise location attached by us |
| OpenStreetMap Nominatim | Turns place text into map coordinates | The place text only |
| Photon (komoot) | Suggests addresses while a business owner types their venue | The typed text only |
| Google Places API | Provides real place details — star ratings, review counts, price level, opening hours, photos, and review snippets — via our server | The place's name and coordinates only, sent from our server. Your identity, account, and precise device location are never sent to Google |
| TikTok / Instagram / X oEmbed | Fetches a shared post's public caption, and the post's preview image when a saved place needs one | The post link, requested from your device — and a request for the preview image itself, from your device, when the place is displayed. Nothing is stored on our servers; your phone caches the image address for a few hours |
| Anthropic (Claude API) | Extracts place names from captions, and reads dishes off menu photos for restaurant owners, via our server | Caption text, or the menu photo being scanned — no identity attached, and the photo is not stored |
| Supabase (AWS, Sydney) | Hosts our accounts database and cloud sync (region ap-southeast-2, Australia) | Your email, profile, saved places, points activity, and any posts, likes, comments, and game nights you create — only when you're signed in |
| Apple / Google / Expo | Standard app distribution and app infrastructure | Standard app-store and crash-level technical data per their own policies |
| Your phone's built-in map service (Apple on iPhone, Google on Android) | Turns a location reading into a city name, on your own device's request — see "Device location" above | The coordinates of that one reading, sent by your phone to its platform provider. It does not pass through our servers and we never see it |

Each of these services has its own privacy policy that governs its side of
the exchange.

**About Google place content:** ratings, review counts, price levels, hours,
photos, and review snippets shown on place pages are supplied by Google and
displayed with "Powered by Google" attribution; review snippets link back to
Google Maps. Our server caches this place content briefly (up to 7 days per
place) to avoid repeated lookups — the cache holds place facts only, never
anything about you. Google's own terms and privacy policy govern that content.

**LiteAPI (Nuitée) — hotel search and paid hotel bookings (live since August
14, 2026):** hotel availability and prices come from LiteAPI, and when you book
a room they are the merchant of record — the payment happens on their secure
hosted card form under their own privacy terms. See the "Hotel bookings"
section below for exactly what we store about a booking.

**Viator (Tripadvisor) — tours and activities (live since August 14, 2026):**
tour and activity listings come from Viator's partner API. Our server sends
Viator only the city being browsed — never your name, account, or location.

## Hotel bookings (accommodation)

When you book a hotel room in Pinorama we store a booking record: the guest
name and email you enter at checkout, the hotel, the stay dates, the price and
currency, the supplier's booking reference, and whether the booking was made in
the test ("sandbox") or live environment. We use this to show the booking in
your app, deliver your confirmation, and handle cancellation and support. The
guest name and email are passed to the accommodation supplier (LiteAPI/Nuitée)
so the hotel knows who is arriving — that is what a booking is. **Your card
details never touch Pinorama:** the card is entered on the payment processor's
hosted form and processed by them as merchant of record. Booking records are
deleted with your account, except records we must keep for bookkeeping and tax
law, which are kept only as long as those laws require.

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
  use the **"delete my account" button in the Settings screen** — tap the
  **⚙️ gear at the top of your Profile screen** to get there. It
  permanently erases your cloud account and everything stored for it
  (including your posts and likes) immediately. You can also delete any
  individual post yourself inside the app, or **email
  admin@nomadzachstudios.com** and we'll action the deletion for you
  promptly. **Deleting your account also signs you out on the phone, so
  everything listed under "What signing out does" above is cleared from the
  device too** — your dating data and your conversations. **Your saved places,
  your profile, your notes and your points stay on the phone** and are not
  deleted with your account; if you want those gone as well, delete the app.
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

**Date of birth.** If you use Pinorama's dating features, we ask for your
date of birth to confirm you are 18 or over and to let other travelers
filter by age range. We store the date; we only ever share your **age in
years** — never the date itself. You can remove it by deleting your dating
profile.

What other travelers can see: signed-in users searching nearby see your
display name, bio, interests, photos, gender (if you set one), whether
you're looking to date, to find a travel buddy, or both, city, and a
distance rounded to whole kilometers,
computed from a further-blurred (~1 km grid) position — never your legal
name, email, exact location, or coordinates. **Which genders you want to
meet is never shown to anyone** — it is only a filter. Who liked you is
not shown
to anyone; likes are stored server-side only to detect a mutual match. A
match is created only when two people like each other, and each match is
visible only to the two people in it.

Blocking is two-way and immediate: blocks are stored on your device and on
the server, and a blocked traveler no longer appears to you nor you to
them. When you report someone, we send us what you reported (which profile,
which surface), the reason you picked, anything you typed in the note, your
account id, and the time — so a moderator can review it and act. Blocking is
still the instant protection: it takes effect immediately, whether or not you
also report.

You can turn discovery off at any time (your profile stops being served to
others), and deleting your account permanently deletes your discovery
profile, likes, matches, and blocks.

## Sharing your location on the map (optional)

Pinorama has an optional **social map** that can show you're around. It is
**off until you turn it on** — we never share your location on the map unless
you tap to share it, and we never read your location in the background.

When you turn it on, we take a **single approximate location** and store it
rounded to roughly a city block (~110 m); we never store your exact GPS
coordinates for this feature. What others see is deliberately limited:

- Any signed-in traveler sees only **anonymous city counts** ("12 travelers in
  Da Nang") — no coordinates, no identity, no distance, and a city is only
  shown when at least two people are there.
- Only travelers you have a **mutual match** with can see an approximate,
  further-blurred (~1 km grid) pin and a whole-kilometre distance — never your
  exact spot, name, or coordinates.

Your shared location automatically ages off the map after a few hours, and
turning the social map off **deletes** your shared location from our servers
(it's gone, not hidden). Blocking a traveler stops the sharing between you.
Deleting your account removes your shared location too.

## Messages between matches

When you match with another traveler in dating / travel-buddy discovery, you
can send each other **direct messages**. Messages are stored on our servers
so they can be delivered, and each message is visible **only to the two of
you** — no other user can read it. We store the message text, who sent it to
whom, the time, and whether it was read. An anti-spam limit caps how fast
anyone can send. Blocking a traveler stops messages between you in both
directions, and deleting your account permanently deletes your messages.

## Reporting content and people

Every place you can report something — a post, a comment, a direct message, a
city-chat message, a dating profile, or a place — sends the report to us so a
person can look at it. Apple requires this for apps with user-generated content,
and we would want it anyway.

**What a report contains:** what you reported (which surface, and which item),
the reason you chose from the list, anything you typed in the optional note
(500 characters maximum), your account id, and the time you filed it.

**What we do with it:** a moderator reviews it and decides what happens to the
reported content or account. We keep the report so we can act on repeat
behaviour — a single complaint and a tenth complaint about the same person are
different situations.

**Who can see it:** you can see the reports you filed. **The person you reported
cannot see your report and is never told who reported them.** That is deliberate:
telling someone who reported them turns a safety tool into a way to retaliate.

**You cannot delete a report once filed.** That is also deliberate — a report a
user can delete is a report someone can pressure them into retracting, and
moderation needs the record to survive that pressure. If you delete your account,
your reports are deleted with it.

**Blocking is separate and immediate.** Blocking takes effect straight away and
does not require a report. Reporting does not automatically block — do both if
you want both.

## City chat rooms

Pinorama has **city chat rooms** — one public room per city, open to signed-in
travelers. Joining a room is **your choice, with one clearly-marked exception
below (a trip you booked)**: the app may suggest a room based on places you've
already saved or the base city on your profile (never from background location
tracking), you are never added to a room from a suggestion without tapping
join, and dismissing a suggestion means that city won't be suggested again.

**City chat after a booking.** When you book a trip in Pinorama (or tell us
you did), we use the destination city to add you to that city's public chat
room so you can meet travelers there. The app tells you the moment it happens,
with a one-tap **leave** right on the same card. You can leave any room with
one tap, a room you leave is never joined for you again, and dismissing a
suggested city also stops it being auto-joined. Your booking details are never
shown to the room — other travelers only see what you choose to post.

If you send a message, we store the message text, the room's city, your
account id, and the time — and every signed-in traveler in that room can see
the message with your display name. An anti-spam limit caps how fast anyone
can post. You can delete your own messages at any time (they disappear from
the room), block other travelers (their messages stop appearing for you, on
your device, immediately), and report messages — a report sends us the message
you reported, the reason you picked, anything you typed, your account id, and
the time, so a moderator can review it. Deleting your account permanently
deletes your chat messages and the reports you filed.

When you're signed in, we also remember **which city rooms you've joined** (the
city and the time you joined) so your rooms sync across your devices. You can
leave a room at any time, and deleting your account removes this too.

## Food delivery & express parcels (optional; not yet active)

Pinorama is adding **food delivery** (order from a local restaurant and have a
driver bring it) and **express parcels** (send a package from one address to
another). These are **not active yet** and will switch on gradually, so they may not be
available in your area at first. They require an account, and everything below
applies only once the service is active for you — we'll never turn them on
silently, and this section describes what they collect before they do.

**Food orders.** When you place a food order we store, with your account:

- **What you ordered** — the items/dishes, their options, quantities, the
  per-item and total prices, the currency, and the order's timestamps.
- **Where to bring it** — the **drop-off address** you enter, **optional
  map-picked coordinates** if you drop a pin on the map, and an optional
  free-text **delivery note** (gate code, building, floor, a landmark).
- **The order's status history** — placed → accepted → preparing → picked up →
  on the way → delivered (or cancelled) — kept with the order so you, the
  restaurant, and support can see what happened, **for safety and to resolve any
  dispute**.

**The optional location permission.** To help you set the drop-off pin, the app
can center the map on **roughly where you are** — this asks your device's
location permission and takes a **single foreground reading, only when you tap to
use it**. It is **never required to order** (you can always just type the
address), it is **never read in the background**, and if you decline, the map
simply centers on your saved places or your base city instead.

**Who can see a food order.** The order is not public. Only its parties can see
it:

- **The restaurant sees only its own orders** — the items, the total, and the
  drop-off address and note needed to make and hand off your food. One
  restaurant can never see another's orders, and none of them can browse the
  app's orders at large.
- **A driver** sees your order's delivery details (address, note, and the items
  to deliver) **only while they are actively carrying it** — from the moment they
  accept your order until it is delivered or cancelled. **Their access ends with
  the job:** once the food is handed over, they can no longer see your order.
- **Before a driver accepts**, drivers looking for a run see **only** the pickup
  restaurant's name, the order's value, and an **approximate drop-off area
  (rounded to about a kilometre)** so they can judge the trip — never your exact
  address, your note, your dishes, or who you are.

**Driver live location (during a live run only).** When the live-tracking
feature is on and a driver is **actively carrying a run**, the driver's app
sends their device's current position (a single latitude/longitude fix, roughly
every 15 seconds) **only while the app is open in the foreground** — we never
collect a driver's location in the background, and never outside an active
delivery. That position is visible to exactly **two people: the driver
themselves, and the one customer whose order that run is serving** (so the
customer can watch their delivery approach on the map). No merchant, no other
user, and no signed-out visitor can ever see it. We keep only the **latest
single position — each update overwrites the last, so there is no route
history** — and the record is **deleted automatically the instant the run ends**
(delivered, cancelled, or handed back). Deleting a driver's account removes it
too. Drivers grant their device's location permission themselves; declining it
simply means no live pin is shown.

**Express parcels.** When you send a parcel we store, with your account: the
**recipient's name and phone number** and an optional drop-off note (so the
courier can hand it over), the **package type and size**, the **pickup and
drop-off addresses** (and optional map coordinates for each), the **service
level**, price, currency, timestamps, the parcel's **status history**, and —
once it's delivered — a **proof-of-delivery record**. The recipient does **not**
need a Pinorama account; their name and phone are information **you provide** for
the delivery. By sending a parcel you confirm you're allowed to share those
recipient details for this purpose.

**Who can see a parcel.** You (the sender) see the full record. **The assigned
courier** sees the recipient's name, phone, notes, and address **only while the
delivery is live** (assigned, picked up, or in transit); once it is delivered or
cancelled, **the courier loses access to the recipient's details**. A driver
**browsing for a parcel to carry** sees only the package type and size, the
price, and **approximate (~1 km) pickup and drop-off areas** — never the
recipient's name or phone, the exact addresses, or who sent it.

**Retention.** Your own delivery and parcel history stays with your account so
you keep a record — a food order survives even if the restaurant later closes
its account (it simply stops being able to see it). **Dispatch and status
history is kept for safety and dispute purposes.** Deleting your account removes
your orders and parcels along with everything else. **No payment is taken inside
the app during this phase;** when paid delivery launches, payments will be
handled by established payment processors and we would never see or store your
full card number.

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
signed-in users when your profile is public (public by default),
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
**gender and which genders you want to meet** (a private filter, never
shown), and
up to **5 self-uploaded photos** (stored by us, deleted with your account)
— the section above describes all of it. Also switched on **city chat
rooms** (new section above): public per-city rooms for signed-in travelers,
joined only by your explicit tap — suggestions come from your saved places
or base city, never background location; messages are deletable by you and
erased with your account. Added **direct messages** between matched travelers
(private to the two of you, blocking ends them, erased with your account) and
an optional **social map** (off until you turn it on, single approximate
location rounded to ~110 m, others see only anonymous city counts or a blurred
match-only pin, auto-expires, deleting it or your account removes it).

**Changelog — July 20, 2026:** documented **driver live location** (new
paragraph in the delivery section): while a driver is actively carrying a run
and the tracking feature is on, their app sends a foreground-only position fix
(~every 15 s) visible **only to that run's customer and the driver themselves**;
we keep a **single latest position (no route history)** and **delete it the
moment the run ends** (or with account deletion); location is never collected in
the background or outside an active delivery.

**Changelog — July 18, 2026:** documented the upcoming **food delivery** and
**express parcel** services (new section above), which are switched on gradually. A food order stores your items and prices, the drop-off address,
**optional** map-picked coordinates, and an optional delivery note; the location
permission that centers the drop-off map is **optional and never required** —
a single foreground read only when you tap it, never in the background. Who can
see an order is spelled out: a **restaurant sees only its own orders**, a
**driver sees your delivery address and the items to deliver only while actively
carrying your order** and loses them once the job ends, and drivers **browsing
for a run** see only the
pickup name, the order value, and an **approximate (~1 km) drop-off area** —
never your exact address, dishes, or identity. For **express parcels**: the
recipient name/phone and drop-off note you provide, the package tier, the
pickup/drop-off addresses and optional coordinates, and a **proof-of-delivery**
record — the full record visible to you, and only while the delivery is live to
the assigned courier. **Dispatch/status history is kept for safety and
disputes**, and deleting your account removes it all.

**Changelog — July 26, 2026:** corrected how this policy describes **device
location**, in four ways. (1) Localizing your feed was listed as "planned," but
the **Local** tab in the feed is live and does use your location, so it has
been moved into its own live section above. (2) That section now also names two
uses the policy had never described: **"use my current location" when you
create an event on the map**, and — the important one — **the quiet city guess
on the Home and Book screens**. That guess never prompts you and never runs
unless you have *already* granted location permission for something else, but
it does take a foreground reading each time those screens load, and an earlier
draft of this section wrongly implied your device asks you before *every*
reading. It does not: the permission is granted once and covers the app. (3)
The coordinates of that city guess are turned into a city name by **your
phone's own map service** (Apple's or Google's), which is now listed in the
Third-party services table — they are not sent to us. (4) One behaviour change
shipped the same day: **tapping Local while signed out no longer asks for your
location**, because that tab has no feed to filter until you sign in. Nothing
here is read in the background, and nearby alerts via push remain planned and
opt-in.

**Changelog — August 1, 2026:** corrected three statements about what happens to
the data on your own phone. (1) The "what signing out does" section said there
was **one** exception — your dating data. There are **two**: your
direct-message threads and your chat with the in-app NomadZach assistant are
also cleared from the device when your session ends, and they are not dating
data. That section now names both. (2) This policy said **"deleting your account
does not touch the data saved on your own phone."** That was wrong: deleting
your account signs you out on the phone, and signing out clears the two things
listed above. It also contradicted the sign-out section on the same page. Both
now point at each other and say the same thing. (3) The **"delete my account"
button is in the Settings screen** (reach it from the ⚙️ gear at the top of your
Profile screen), not the Profile screen, and both documents said the wrong
place — anyone following the old instruction would not have found the control.
Nothing about the app's behaviour changed today; these are corrections to a
document that described it wrongly.

**Changelog — August 8, 2026:** one new use of the quiet city guess, described
here before it shipped. The **city chats** screen used to suggest rooms based on
the city you typed as your home base at signup, the city of the last place you
saved, and our launch city — so a traveler sitting in one city was offered the
chat for another. It now also suggests **the city your phone says you are in**,
listed first. This uses the same reading already described in "Device location"
above: it never asks you for permission, it does nothing at all unless you have
already granted location permission for something else, the coordinates are
turned into a city name **by your own phone** and never reach us, and nothing is
stored. **It suggests only.** It does not join you to a room, it does not tell
other travelers where you are, and you still join a room by tapping "join". A
city you have already declined is not suggested again. Turn the permission off
and the screen goes back to suggesting your home base, as before.

**Changelog — August 14, 2026:** documented **maps you publish**, and this entry
is late: the feature became readable to people without an account on **August 11,
2026**, and until today this policy still listed "shared/creator maps" as a
planned feature that was not live. We would rather say that plainly than quietly
move the line. A published creator map now has its own entry in "With an account"
above, which describes exactly what a visitor with **no Pinorama account** can see
when they open one from a shared link or from the app's creator section: the map's
title, blurb, cover emoji, pin count and last-updated date; every pin's name,
address, coordinates, category and the note the creator wrote on it; and the
creator's display name, @username and avatar emoji. Nothing about the person
opening a map is recorded — there is no view counter. Publishing takes a **copy**
of the chosen places, so later edits to a saved place do not change a map already
published; **unpublishing removes the map and its pins from view immediately**,
making your creator profile private removes your maps from the public list, and
deleting your account erases them. The "planned" list above no longer names
shared/creator maps.

Also documented today, and this part is late as well: **a saved place can show the
preview picture from the post you saved it from**, and this page did not say so.
That began on **August 8, 2026** on the place's own screen; from today it also
fills in your saved list. In both cases your device asks the platform's public
preview service for the picture's address and then loads the picture from that
platform's image server — the same way it would if you opened the post yourself.
**We do not store the picture, and we do not keep its address on our servers**;
your phone remembers it for a few hours so it does not have to ask again. If a
post has no picture, or the service cannot be reached, the place shows its
coloured category tile instead. **No new personal data is collected**, and
nothing new is sent to us or to anyone else.

**Changelog — August 16, 2026:** documented **referrals**, and this entry is
late: since around **August 10, 2026** the app has been able to record, on a
new account's profile, **which existing account's invite link that person
joined through and when** (with a 6-month expiry on the link between the two
accounts). Until today this page said nothing about it, and the only
invite-shaped sentence on the page — written about event invites — could be
read as a promise that no invite is ever visible to us. We would rather say
this plainly than quietly move the line: a new **"Who invited you
(referrals)"** entry now sits in "With an account" above, and the event-invite
sentence now points to it. What has *not* changed: we still never see who you
send any invite to — a referral is recorded only when the invited person
actually joins, and it is erased with either account's normal deletion rights.

**Changelog — August 17, 2026:** documented **what you are looking for on
the discovery profile** — whether you want to date, to find a travel
buddy, or both — and this entry is late. Since around **July 17, 2026**,
when the discovery profile gained these fields, that choice has been sent
to other signed-in travelers nearby and shown on their screen as whether
your goal matches theirs. Until today this page listed what other
travelers can see and left it out, and the sentence directly after that
list — "who you want to meet is never shown to anyone" — could reasonably
be read as covering it. We would rather correct that plainly than quietly
move the line: the field now appears in that list, and the sentence has
been narrowed to say what it always meant, which is **which genders** you
want to meet. What has *not* changed: which genders you want to meet is
still never shown to anyone and remains a filter only, and your date of
birth is still never shared — only your age in years.

**Changelog — August 17, 2026:** removed one line that contradicted the rest of
this page. Under "Planned (not live yet)" this policy still said: *"Payments for
bookings — handled by established payment processors (e.g. Stripe). We would
never see or store your full card number."* Two things were wrong with it. It
filed booking payments under "not live yet", while the **"Hotel bookings
(accommodation)"** section and the **LiteAPI (Nuitée)** entry further up already
describe how a hotel payment works and exactly what we keep about a booking — so
one page was saying both things at once. And it named the wrong company:
**Stripe does not process hotel payments in Pinorama.** The card is entered on
the accommodation supplier's own hosted payment form and **LiteAPI (Nuitée) is
the merchant of record**, which is what those two sections say. The old wording
is quoted above rather than quietly deleted, so nobody has to guess what
changed. **No new data is collected and nothing new is shared:** what we keep
about a booking is unchanged, and the promise that line was making — that your
full card number never reaches us — still stands and is stated in "Hotel
bookings (accommodation)".

## Contact

**NomadZach Studios**
admin@nomadzachstudios.com
