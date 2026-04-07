---
layout: page
title: Privacy Policy
---

**Last Updated:** March 10, 2026

This Privacy Policy explains how Valen ("the App"), built by GrowthFlux, handles your data — what we collect, why, and what control you have over it.

---

## 1. What We Collect

### Account Info

When you sign up, we collect your **email** and **display name** (of your choosing). If you use a password, it's securely hashed — we never see or store it in plain text.

If you sign in with Google, Apple, Discord, or X, we receive your name and email from that provider. Your real name, email or any private information are never shown to other users.

### Profile (Optional)

You can optionally add a **profile photo** and **gender** to personalize your experience.

### Onboarding

During onboarding, you answer questions about your goals and habits. These responses help us tailor the AI coaching to you. They're stored on your private profile and are never shared with other users.

### Your Content

Everything you create in the App is yours:

- Goals, tasks, and reflections
- Chat conversations with the AI assistant
- Achievements and progress data
- Timer and focus session data

### Analytics & Error Reports

We collect usage data to improve the App and fix bugs:

- Which screens you visit and features you use
- Error reports with a trail of recent actions (so we can reproduce and fix issues)
- Device info (model, OS version, app version)
- IP address (for approximate location only — not stored long-term)

We **don't** track your keystrokes, record your screen, or send your messages or personal information to analytics.

### Payments

If you subscribe to premium features, payments are handled entirely by the App Store (Apple) or Play Store (Google). We never see your credit card or billing details — we only know whether your subscription is active or not.

---

## 2. How We Use It

- **Run the app** — store your goals, tasks, and chats so they're there when you come back
- **Personalize coaching** — use your onboarding answers and patterns to make the AI more helpful
- **Power the AI** — send relevant context (your goals, tasks, chat history) to our AI provider so it can give useful responses
- **Fix bugs** — analyze errors and usage patterns to make the App better
- **Leaderboard** — show your display name, avatar, and task count to other users
- **Subscriptions** — check your subscription status for premium features

We **don't** sell your data, use it for ads, or share your personal content with other users (beyond what's visible on the leaderboard).

---

## 3. Third-Party Services

Here's who helps us run the App and what data they see:

| Service | What it does | What it sees |
|---------|-------------|-------------|
| **Supabase** | Database, auth, file storage | Your account, profile, goals, tasks, chats, avatar |
| **OpenAI** | AI coaching (ChatGPT) | Your messages, goal/task context, coaching profile |
| **PostHog** | Analytics & error tracking | Usage events, device info, errors, user ID |
| **Superwall** | Subscription management | User ID, email, name, subscription status |
| **Google / Apple / Discord / X** | Sign-in | Email and name (only if you choose that sign-in method) |

### About the AI

When you chat with the AI coach, we send your message, recent chat history, and relevant goal/task context to OpenAI. They process it to generate a response and **don't use your data to train their models** (per their API policy).

### About Analytics

PostHog runs on **EU servers**. We use it to understand how people use the App and catch errors. We don't send the content of your messages or notes to analytics — just events like "user completed a task" or "error occurred on this screen."

---

## 4. Where Your Data Lives

- **Cloud database** — Supabase (PostgreSQL)
- **Your device** — local cache for offline use
- **Analytics** — PostHog EU servers

Everything is transmitted over **HTTPS**, passwords are **hashed with bcrypt**, and **Row-Level Security** ensures you can only access your own data.

---

## 5. How Long We Keep It

- **While you're active** — your data stays as long as your account exists
- **When you delete** — it's permanently removed from our database (see below)
- **Analytics** — retained per PostHog's policies
- **Backups** — may briefly retain data after deletion per our infrastructure provider's schedule

---

## 6. Leaderboard

The leaderboard shows your **display name**, **avatar**, **completed task count**, and **rank** to other Valen users. If you'd rather stay anonymous, just change your display name to something non-identifiable.

---

## 7. Your Controls

You're in control of your data:

- **View** — see all your data anytime in the App (goals, tasks, chats, profile)
- **Edit** — update your name, photo, and date of birth from Edit Profile
- **Clear Data** — wipe all your goals, tasks, chats, and achievements while keeping your account (Profile > Security)
- **Delete Account** — permanently delete everything, including your account itself — type "DELETE" to confirm (Profile > Security)
- **Sign Out** — clears your local session and resets your analytics identity

---

## 8. Kids & Minors

Valen is suitable for all ages (rated 4+ / Everyone). If you're a minor, we recommend using the App with a parent or guardian's knowledge. If a parent or guardian wants their child's data removed, contact us and we'll take care of it.

---

## 9. International Transfers

Our service providers operate globally. By using the App, you're okay with your data being processed by these providers. Analytics specifically runs on PostHog's **EU servers**.

---

## 10. Changes

We may update this policy. If we do, we'll update the date at the top. Continued use after changes means you accept the update.

---

## 11. Questions?

Reach out:

**Email:** [support@valenai.com](mailto:support@valenai.com)

---

*This policy applies to the Valen mobile application by GrowthFlux.*
