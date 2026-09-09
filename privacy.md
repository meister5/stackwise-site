# Privacy Policy

**Effective date:** September 9, 2026

StackWise ("the app", "we", "us") is a medication and supplement tracker built around one rule: your health information stays on your device. This page explains exactly what data exists, where it goes, and what it never does.

## The short version

- What you take, your dosages, your schedule, and your history of marking doses taken or skipped — this all lives in a local database on your phone. It is never uploaded to our servers.
- We don't require an account and we don't collect your email address or name.
- The few things that do leave your device are limited to anonymous technical data needed to run subscriptions, keep the app stable, and understand feature usage in aggregate — never the content of what you take.

## What stays on your device only

All of your health data — the items you track, dosages, schedules, and your log of doses taken or skipped — is stored locally on your device using SQLite. This data is never transmitted to StackWise or any third party. It leaves your device only if you choose to export it yourself (see "Backups and exports" below).

## What we send to third-party services, and why

StackWise uses a small number of external services, each limited to a narrow purpose:

**Supabase (anonymous authentication and subscription status).** The app creates an anonymous session with Supabase — there's no sign-up, no email, no password. Supabase receives only an anonymous user identifier, your subscription status, and a purchase receipt token used to verify your subscription. It never receives the names of items you track, dosages, or schedules.

**RevenueCat (subscription management).** RevenueCat processes in-app purchases and tells the app whether you have an active Pro subscription. It receives standard purchase/receipt data needed to validate your subscription — never your health data.

**PostHog (anonymous product analytics).** PostHog receives an anonymous device identifier and behavioral events — for example, that an item was added, a dose was marked, or a screen was opened. These events never include item names, dosages, or any other health content.

**Sentry (crash reporting).** If the app crashes or hits an error, Sentry receives technical crash data and the name of the screen where it happened, so we can fix bugs. It never receives your health data.

**OpenRouter (optional, only if you use the Stack Optimizer's AI suggestions).** The Stack Optimizer can suggest a better time-of-day schedule for your items. Most of the time this runs entirely on your device. If you opt into the AI-assisted version, a privacy-scrubbed summary is sent through our server to OpenRouter — this summary contains only canonical ingredient names, general timing categories, how often you take something, the names/times of your reminder slots, and generic interaction summaries. It never includes the names you gave your items, your dosages, or anything that identifies you personally.

## Backups and exports

You can export your data as a JSON file or a PDF at any time, and you can restore from a previously exported JSON backup. These exports are created and stored under your control — StackWise does not receive a copy, and nothing is uploaded automatically. Sharing an export (for example, emailing it to your doctor) is entirely your choice.

## Accounts and email

StackWise does not require you to create an account and does not collect your email address, name, or other personal contact information as part of using the app.

## Notifications

Reminder notifications are scheduled entirely on your device using your phone's local notification system. StackWise does not use push notification servers and does not receive any data related to your reminders.

## Data retention and deletion

Because your health data lives only on your device, you control it directly — deleting an item, clearing your history, or uninstalling the app removes that data from your device. Anonymous analytics and crash data held by our third-party providers are retained according to their own standard retention practices and contain no health information to begin with.

## Children's privacy

StackWise is not directed at children and is not intended for use by anyone under the age of 16.

## Changes to this policy

If we make material changes to this policy, we'll update the effective date above and, where appropriate, note the change within the app.

## Contact us

Questions about this policy? Email us at [support@stackwise.app](mailto:support@stackwise.app).
