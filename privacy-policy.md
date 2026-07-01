# Privacy Policy — Loaf Budget

**Effective date:** July 1, 2026
**Provider:** Moeed Faisal ("we", "us", "our")
**Contact:** support@loafbudget.com

Loaf Budget ("the app") helps you understand your daily cost of living. We built it to
collect as little as possible. This policy explains what we collect, why, and the
choices you have.

## 1. Information we collect

**Account information.** When you create an account we collect your **email address**.
If you sign in with **Apple** or **Google**, we receive your email and, optionally, your
name from that provider. We do not receive your Apple/Google password.

**Financial information you enter.** The app stores the budgeting data you create:
expenses (amounts, descriptions, merchants, notes, tags, dates, and a reimbursable flag),
income, accounts, "loaves" (savings envelopes) and the "bread" groups they belong to, and
cash-balance entries. This is the core content of the app and is tied to your account.

**AI spend logging (only if you use it).** When you use the "describe a spend" feature to
log a spend in plain language, the text you enter is sent to **Google's Gemini API** to
turn it into a structured spend (amount, date, merchant, and which loaf it belongs to). To
help it map your words correctly, we also send limited context: your loaf and account
**names**, your recently used merchant names, your currency symbol, and today's date. We do
**not** send Google your name, email, or account identifier. If you never use this feature,
nothing is sent to Google's AI — spends you enter by hand stay within the app and our
database provider.

**Voice input (only if you use it).** If you speak a spend instead of typing it, your
device's built-in speech recognition converts your speech to text. Depending on your device
and OS settings this may be processed by Apple. The resulting text is then handled exactly
like text you typed (including the AI step above, if enabled). We do not store audio.

**Technical information.** Standard information needed to operate the service (for
example, authentication tokens to keep you signed in, and basic error/connection state).
On your device, authentication tokens are **encrypted at rest** in the system keychain.

**We do _not_ collect:** advertising identifiers, your location, your contacts, or
analytics/usage-tracking data. The app contains **no third-party analytics, advertising, or
tracking SDKs**. Reminders, if you enable them, are scheduled **locally on your device** — we
do not run a push-notification server.

## 2. How we use your information

- To provide the app: authenticate you, store and sync your budget across your devices.
- To parse a spend you describe in words or voice, when you choose to use that feature.
- To operate and secure the service (e.g. keep you signed in, prevent unauthorized access).
- To respond to support requests you send us.

We do **not** use your information for advertising, profiling, or tracking across apps
or websites, and we do **not** sell your information.

## 3. How your information is stored and protected

Your data is stored with our cloud database provider, **Supabase** (hosted in the
**United States**). Access is restricted per-account using row-level security, so your data
is only accessible to your authenticated account. When signed out, the app runs on local
device storage only.

## 4. Sharing and disclosure

We do not sell or rent your information. We share it only with service providers that
operate the app on our behalf, and only as needed:

- **Supabase** — database, authentication, and sync.
- **Google (Gemini API)** — only when you use AI spend logging, to parse the text you
  describe into a structured spend (see Section 1). Google processes this input under its
  own API terms.
- **Apple** and **Google** — only if you choose to sign in with them (identity). This is
  separate from the Gemini API above.

We may disclose information if required by law, or to protect the rights, safety, or
security of our users or the service.

## 5. Data retention and deletion

We keep your data for as long as your account exists. You can **delete your account at
any time** from **Settings → Delete account**. Deleting your account permanently removes
your account and all associated data (expenses, income, loaves, accounts, and cash
history). This cannot be undone.

## 6. Your rights

Depending on where you live, you may have the right to access, correct, export, or delete
your personal data. You can export your data or delete everything yourself from within the
app (Settings → Delete account), or contact us at support@loafbudget.com for any request.

## 7. Children

The app is not directed to children under 13 (or the minimum age required in your
country), and we do not knowingly collect their information.

## 8. Changes to this policy

We may update this policy from time to time. We will update the "Effective date" above
and, for material changes, provide notice within the app.

## 9. Contact

Questions about this policy or your data: **support@loafbudget.com**.
