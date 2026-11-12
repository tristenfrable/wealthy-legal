---
layout: default
title: Privacy Policy — Wealthy
permalink: /privacy/
---

# Privacy Policy — Wealthy

**Last updated:** November 12, 2026
**Effective:** November 3, 2026

---

## 1. Who we are

Wealthy ("Wealthy", "we", "us") is a personal finance education app published by
Wayne Ventures LLC, a limited liability company registered in Oregon, United
States, at 2301 Melrose Rd, Roseburg, OR 97471.

Questions about this policy or your data: **tristenwaynef@gmail.com**

## 2. The short version

- **An account is optional.** Wealthy works fully without one. If you choose to
  sign in — with Apple, never a password of ours — your data is backed
  up to your account so you can use it on more than one device (section 3.4).
  Without an account, we never ask for an email address, phone number, or password.
- During setup we do ask for your **first name, date of birth** (from which only
  your age is kept), **monthly income**, and **the goals you want to work on**.
  These are stored on your device and are sent with every Penny message
  (section 5).
- Your budget, expenses, bills, savings goals, net worth, and check-in history
  are stored on your device. If you have not signed in, their amounts, names,
  and notes are never sent anywhere; if you have, they are also stored in your
  account (section 3.4). Analytics do record short labels about how you use those features —
  for example the category of an expense you add, or which answer you picked in
  a check-in (section 3.3).
- We collect **product analytics** through PostHog (section 4): which screens are
  opened and which features are used, tied to a random identifier generated on
  your device, along with basic device and app information. Analytics never
  include money amounts and never include anything you or Penny typed.
- **Penny is the exception, and it is an important one.** To answer you, your
  conversation and a short profile summary are sent to our server and on to
  Anthropic. Section 5 explains exactly what that includes.
- Every time the app opens or returns to the foreground, it checks your
  subscription status with RevenueCat,
  sending an anonymous RevenueCat identifier and your device's vendor identifier —
  whether or not you have ever subscribed (section 6).
- You can erase everything Wealthy stores on your device — and, if you signed
  in, your account and everything in it — at any time: **Settings → Delete my
  data**. That does not reach copies already held by
  PostHog, RevenueCat, or Anthropic, and leaves RevenueCat's own on-device data in
  place — section 9 explains exactly what it does and does not do.

## 3. What is stored on your device

Everything you enter is saved in the app's local storage on your phone and is
removed when you delete your data, sign out, or uninstall the app. If you have
not signed in, we keep no copy of it on a server and cannot recover it for you
if you delete it. If you have, it is also kept in your account, as section 3.4
describes.

Without an account, most of it never leaves your phone. **Some of it does**, and
this section says exactly which.

### 3.1 Stored on your device, and in your account only if you sign in

Unless you sign in, the contents of the following never leave your phone. If you
do sign in, all of them except the feedback note are also stored in your account
(section 3.4). Analytics may record *that* you used one of these features (see
3.3), but never the amounts, names, or notes in it:

- Your budget: daily limit, expense amounts and notes, and bills
- Your savings goals: their names, targets, and progress
- Your net worth figures (assets and liabilities)
- Your full check-in history and longest streak
- Any note you type into the "Not really" feedback box when asked to rate the app
- Whether you have completed setup, seen the in-app tips, and accepted
  Penny's disclaimer

### 3.2 Stored on your device and also sent when you use Penny

Each time you send Penny a message, the following are sent to our server, and
from there to Anthropic, as described in section 5:

- Your profile: first name, age, monthly income, and the goals you selected
  during setup
- Your Penny conversation — the whole conversation to our server, and the most
  recent 40 messages of it to Anthropic

If you never use Penny, none of this leaves your phone.

### 3.3 Stored on your device and summarised in analytics

A few short labels about what you do are sent to PostHog as part of the analytics
described in section 4 — always a fixed option, a count, or a setting's value,
never an amount and never anything you typed. The ones that relate to the data
above are listed here; section 4.1 lists everything the app can record:

- When you complete a daily check-in: the answer you picked (for example "Yes" or
  "Stressed") and your current streak length
- When you add an expense: its category (for example "Food"), not its amount or
  note
- When you change a notification setting: which setting and its new value (for
  example turning a reminder off, or a new reminder time such as 7:00 PM)
- When you create or finish a savings goal: that it happened, and whether it has
  a monthly plan — not its name or amounts

The rest of this data stays on your device unless you sign in (3.4).

### 3.4 If you sign in: your account

Signing in is optional, and you can do it at any time from Settings. Wealthy
offers Sign in with Apple; we never see your Apple ID password. Accounts are run
on Supabase, a database service provided by Supabase Inc.

**What your account holds.** Once you sign in, the app keeps a copy of the
following in your account and keeps it up to date as you make changes, so that
it is the same on every device you sign in on:

- Your profile: first name, age, monthly income, and the goals you selected
- Your budget: daily limit, expenses (amounts, categories, and notes), and bills
- Your savings goals, their progress, and each contribution you record to them
- Your net worth figures
- Your check-in history and streak
- Your Penny conversation
- Your notification settings, which in-app tips you have seen, and when you
  accepted Penny's disclaimer

Not in your account: the "Not really" feedback note, your analytics
identifiers, your subscription status (which stays with Apple and RevenueCat,
section 6), and the fact that setup was blocked by the age check.

**What Supabase receives about you to run the account:**

- The email address Apple gives us when you sign in. If you choose
  Apple's "Hide My Email", this is a relay address Apple creates, not your real
  one.
- Your name, if Apple shares it — Apple does this only the first time you sign
  in to Wealthy
- That you signed in with Apple, a random account ID created for you, and
  when your account was created and when you last signed in
- Your IP address whenever the app connects, as any internet service sees it.
  Supabase records it in its sign-in logs.

**Who can read it.** The app can read and change only the account you are signed
in to; the database refuses everything else. As the operator of the service, we
have administrative access to the database.

**Where it is kept.** Supabase stores the database on Amazon Web Services
infrastructure in the United States, in the West US (Oregon) region
(us-west-2).

**How long.** For as long as you have the account. Signing out removes your data
from that device but leaves your account as it is, so signing in again restores
it. To delete the account and everything in it, use Settings → Delete my data
while signed in (section 9). Wealthy's Supabase project is on a plan that does
not include automatic database backups, so deleting your account does not leave
a copy of it behind in a database backup.

## 4. Analytics (PostHog)

We use [PostHog](https://posthog.com) to understand how the app is used so we can
improve it.

### 4.1 What is collected

**Identifiers**

- **The app's analytics identifier.** A random string of letters and numbers,
  generated on your device the first time you open the app. It is not derived
  from your name, your device's identifiers, your advertising ID, or anything else
  about you. It is not linked to your Wealthy account if you have one: the app
  never gives PostHog your account ID, email address, or name. It
  stays the same across launches until you use Delete my data or delete the app
  (section 9).
- **PostHog's own anonymous identifier.** PostHog's software generates a second
  random identifier of its own on your device and sends it alongside ours, which
  links the two together in PostHog.
- **A session identifier**, generated by PostHog to group events from one period
  of use. A new one starts after a period of inactivity.

None of these is shown in the app.

**What you do in the app.** When you use certain features, we record that it
happened, sometimes with a short label for context. This is the complete list —
the app cannot record anything that isn't on it:

| What happened | What is recorded with it |
|---|---|
| You open the app | how many days it has been since you installed it |
| You start setup | nothing else |
| You finish setup | how many goals you picked (a count, not which ones) |
| Setup is blocked because of the date of birth you entered | nothing else — never your age |
| You see the subscription screen | which version you saw: the offer, mid-trial, trial ended, or already subscribed |
| You start a free trial, or subscribe | that it happened, and whether it went through the App Store — never the price, currency, or plan |
| You send Penny a message | whether you tapped a suggested question or typed your own, and whether it was your first message — never the message |
| You set a daily budget | nothing else — never the amount |
| You add an expense | its category (for example Food) — never the amount or note |
| You create a savings goal | whether it has a monthly plan — never its name or amounts |
| You finish a savings goal | nothing else |
| You use the investing calculator | which control you touched first (monthly amount, years, or rate) — never the values |
| You are shown the daily check-in | which question it asked (progress or mood) |
| You complete a check-in | which question, the answer you picked from its fixed options (for example "Yes" or "Stressed"), and your current streak length |
| You reach a streak milestone | which one: 3, 30, or 100 days |
| Your monthly streak freeze covers a missed day | nothing else |
| You are asked whether to allow notifications, and your answer | if the request failed because of an error, that it was an error |
| Reminders are scheduled | which kind of reminder, and how many |
| You tap a reminder | which kind of reminder |
| You change a notification setting | which setting and its new value: reminders on or off, the reminder time (for example 7:00 PM), or one of the optional reminders on or off |
| You are asked to rate the app, and how you answer | what prompted the request (a 30-day streak, a completed goal, or five Penny messages in one session), and, if the request wasn't shown, why — never any feedback you type |
| You start, finish, or skip the in-app tips | which screen's tips, how many there are, and if you skipped, how far you got |
| You accept Penny's disclaimer | which disclaimer |
| You sign in, or a sign-in fails | that it was Sign in with Apple, and if it failed, an error code — never your email address or account ID |
| You choose not to sign in when offered | where you were offered it |
| You sign out | that it was Sign in with Apple |
| You delete your account | nothing else |
| You use Delete my data | nothing else |

**Which screen you are on.** Each time you move to a new screen, which screen it
was — for example the home screen, your budget, Penny, or settings. This never
includes anything shown on the screen.

**App activity**, recorded automatically by PostHog: when the app is installed,
updated (with the previous version number), opened, brought back to the
foreground, or sent to the background. If the app was opened from a link, that
link is recorded too; in Wealthy, that is only ever a link to one of the app's
own screens.

**Device and app information**, attached automatically by PostHog to everything
above: your device's manufacturer and model (for example "Apple", "iPhone 16 Plus"
— the model, not the name you gave your phone), its operating system and version,
whether it is a simulator, the app's name, App Store identifier, version and build
number, your language and time zone settings, and your screen size.

**Your IP address.** Whenever the app sends analytics to PostHog, or checks in
with PostHog when it starts, PostHog sees your IP address, as any internet
service does. We have set PostHog **not to store your IP address** with your
analytics, and **not to use it to work out your location**, so no location is
recorded.

Session replays are **not** collected. See 4.3.

### 4.2 What is never collected

No analytics ever include a money amount, your age, anything you typed, or
anything Penny said. The list in 4.1 is everything the app adds, and none of it is
any of those things.

As a safeguard, the app also checks everything before sending it, and drops any
label that is about money, age, or text, and any long piece of free text. The
main protection, though, is that the app never attaches that information in the
first place. A few numbers are sent on purpose, and they are all listed in 4.1:
your streak length, counts, days since install, and your reminder time.

We record *that* you sent Penny a message. We do not record what it said.

### 4.3 Session replay

PostHog session replay is **turned off**. No recording of your screen, and nothing
displayed on it — balances, your name, Penny's messages — is sent to PostHog.

### 4.4 Where it goes and how long it is kept

Analytics are processed by PostHog Inc. in PostHog's US Cloud, in the United
States. Analytics data is retained for 12 months and then deleted.

## 5. Penny, and what is sent to Anthropic

Penny is powered by Claude, an AI model from Anthropic PBC. **To generate a
reply, we must send your question somewhere.** It happens in two steps.

**From the app to our server**, each time you send a message:

- **The whole conversation so far** — every message you have sent Penny and every
  reply, as stored on your device — including the new message
- **A short profile summary**: your first name, your age, your stated monthly
  income, and the goals you selected during setup

Because this request comes from your phone, our server and the service hosting it
also receive your IP address. The request carries no identifier: not the
analytics identifier from section 4, and not the RevenueCat identifier from
section 6.

**From our server to Anthropic:**

- **The most recent 40 messages** of that conversation (all of it, if it is
  shorter). Our server drops anything older before forwarding.
- **The same profile summary**
- Our own instructions to Penny, which are the same for everyone

Anthropic receives the request from our server, not from your phone, so it does
not receive your IP address.

This is not analytics and is not covered by the restrictions in section 4.2 —
those apply to PostHog. It is the feature working as intended: Penny cannot give
you a useful answer about your situation without knowing something about you.

**That list is everything Penny receives.** She is not sent your budget, expenses,
bills, savings goals, net worth, or check-in history. If you want her to take any
of those into account, you have to tell her in a message — and whatever you type
is then sent like any other message.

**Your monthly income is included in that profile summary.** Setup requires a
monthly income above zero, and the app has no way to change or remove your name,
age, income, or goals afterwards — the only way to remove them is Settings →
Delete my data, which erases everything (section 9). If you would rather your
income were not sent, do not use Penny.

Anthropic's handling of this data is governed by its own terms. As of October 6,
2026, Anthropic states that requests sent to it this way, and its replies, are not
used to train its models.

- Our server does not save your Penny conversations. It forwards each request to
  Anthropic and returns the reply, and keeps nothing itself.
- Your conversation content is never written to our logs. If a request to
  Anthropic fails, our server records only the type of error and a short
  description of it — never your messages, Penny's replies, or your profile
  summary.
- Our server is hosted on EAS Hosting, a service run by Expo, which runs on
  Cloudflare Workers. EAS Hosting records basic details of each request it
  handles (such as the time, the result, and how long it took), and keeps the
  error records described above. We have not yet confirmed with Expo whether it
  keeps any record of the content of requests, or for how long it keeps its
  records. We will update this section once we have.
- Anthropic does receive a copy of each request, as described above, and keeps
  it according to its own terms. The full conversation history stays on your
  device, and, if you have signed in, in your account (section 3.4).

## 6. Subscriptions and payments

Subscriptions are sold through the Apple App Store and managed with RevenueCat.

- **We never see your payment details.** Your card, billing address, and Apple ID
  are handled entirely by Apple. They are never sent to us and never pass through
  our servers.
- **RevenueCat is contacted every time the app starts or comes back to the
  foreground**, for every user — not only people who have subscribed — so that the
  app knows whether a subscription is active and which plan to offer. Each of
  those requests includes:
  - an anonymous identifier that RevenueCat's software creates and stores on
    your device — or, once you sign in, your Wealthy account ID (section 3.4)
    instead, so that a subscription follows you to your other devices. The app
    never gives RevenueCat your name, email address, or anything else about you
    to attach to it.
  - your device's **identifier for vendor** — an ID Apple gives your device that
    is the same for all apps from one developer, and resets if you remove all of
    them. This is not your advertising ID.
  - your device model, operating system version, preferred languages, the App
    Store country, the app's version, build number and App Store identifier, and
    whether it is a test version of the app
  - your IP address, since the request comes from your phone
- **When you buy, start a trial, or restore purchases**, RevenueCat also receives
  the App Store transaction and receipt information for it.
- We receive aggregate revenue reporting from Apple and RevenueCat. The purchase
  events the app sends to analytics (section 4.1) carry no price, currency, or
  product identifier.

## 7. Bank account connections

**Wealthy does not connect to your bank.** The app has no bank-linking feature.
Every figure in the app — income, expenses, bills, assets, liabilities — is one
you typed in yourself, and none of it comes from a bank or any other outside
source. Without an account, only your monthly income ever leaves your device: it
is sent with every Penny message (section 5), and expenses, bills, assets, and
liabilities are never sent anywhere. If you sign in, all of these figures are
also stored in your account (section 3.4).

## 8. Children

Wealthy is not directed to children. **You must be at least 13 years old to use
Wealthy**, and if you are under 18 you may only use it with the involvement of a
parent or guardian.

We do not knowingly collect personal information from anyone under 13. If we learn
that we have, we will delete it. If you believe a child under 13 has used the app,
contact us at **tristenwaynef@gmail.com**.

The app holds to this minimum. During setup it asks for your date of birth.
If the date shows you are under 13, the app asks you to confirm it, and once
confirmed it does not let you finish setting up. It remembers on your device only
*that* setup was blocked — not your age and not your date of birth — so the
question cannot simply be answered again. If you are 13 or over, only your age is
kept, never the date itself.

## 9. Your choices and rights

- **Delete my data.** If you are signed in, Settings → Delete my data first
  **deletes your account**: the account itself and everything stored in it
  (section 3.4) are removed from Supabase, and, if you signed in with Apple, the
  app asks you to confirm with Apple once more so that Wealthy's access to your
  Apple ID can be revoked. If that fails, nothing is deleted and you can try
  again. Then, signed in or not, it does three things on your device,
  immediately and irreversibly:
  - It **erases everything Wealthy itself stores on your device**: your profile,
    budget, goals, net worth, check-in history, Penny conversations, feedback
    notes, and settings.
  - It **cancels every reminder** the app has scheduled.
  - It **resets your analytics identifiers** — the app's and PostHog's own — so
    nothing the app sends to PostHog afterwards can be connected to anything it
    sent before.

  Two things on your device are left as they are:
  - **RevenueCat's own data**: its anonymous identifier and its cached copy of
    your subscription status, which RevenueCat's software stores separately from
    the app's data.
  - **Your notification permission.** If you allowed notifications, iOS keeps
    that setting until you change it in the iOS Settings app.

  It does **not** delete data that has already left your device:
  - **PostHog** keeps the analytics events already sent under your previous
    identifier (section 4) until its retention period ends.
  - **RevenueCat** keeps its subscription and purchase records (section 6).
    RevenueCat's anonymous identifier is **not** reset by Delete my data, so
    purchases made before and after a deletion stay associated with the same
    RevenueCat ID.
  - **Anthropic** keeps Penny requests already sent according to its own data
    retention terms (section 5).

  To ask for data held by those services to be deleted, contact
  **tristenwaynef@gmail.com**.

  **Deleting the app** removes everything stored in the app's storage area,
  including the app's and PostHog's analytics identifiers and RevenueCat's
  anonymous identifier and cache, so reinstalling starts with new identifiers.
  Your device's identifier for vendor (section 6) changes only if no other app
  from the same developer is still installed. As with Delete my data, nothing
  already sent to PostHog, RevenueCat, or Anthropic is deleted.
- **Opt out of analytics.** There is no way to opt out of analytics in the app.
  Delete my data resets your analytics identifier but does not stop analytics
  from being sent afterwards; the only way to stop it entirely is to stop using
  the app.
- **Stop notifications.** Settings → Notifications, or your device's notification
  settings.
- **Sign out.** Settings → Sign out removes your account's data from that device
  and leaves the account itself untouched.
- **Request information.** If you have not signed in, we hold no account and no
  server-side profile, so we generally have nothing to send you beyond what is
  already on your device. If you have, your account holds what section 3.4
  lists, and you can ask us for a copy. For these requests, and requests
  concerning the analytics identifier, contact
  **tristenwaynef@gmail.com**. The app does not currently show you your analytics
  or RevenueCat identifier, so we may be unable to find the records that belong
  to you.

## 10. Security

**On your device.** The app keeps your data in its own storage area, which iOS
isolates from other apps. The app relies on iOS's default file protection: if
your phone has a passcode, the files are encrypted until you first unlock the
phone after it restarts, and readable while it stays on. The app adds no
encryption of its own: anyone who can unlock your phone and open the app can see
what is in it.

**Your account.** If you sign in, the app keeps your sign-in session in its own
storage area on your device, alongside the rest of your data. Supabase encrypts
the database where it is stored, and the database itself only lets the app read
or change the account it is signed in to.

**In transit.** Every connection the app makes over the internet — to our
server, Supabase, PostHog, and RevenueCat — is encrypted (HTTPS), and the app is set up so
that your phone refuses to let it connect any other way. Our server's connection
to Anthropic is also encrypted.

No method of storage or transmission is perfectly secure, and we cannot guarantee
absolute security.

## 11. Changes

We may update this policy. When we do, the "Last updated" date above will change.
The app does not currently tell you when this policy changes, so check this page
for updates.

## 12. Contact

**tristenwaynef@gmail.com**
Tristen Frable, 2301 Melrose Rd, Roseburg, OR 97471
