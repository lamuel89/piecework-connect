PIECEWORK CONNECT — FIREBASE MVP

This version connects to the Firebase project configured in index.html.
Features: Firebase email/password registration and sign-in, Firestore job listings, worker profiles, job posting, search, and WhatsApp contact.

IMPORTANT BEFORE USE
1. In Firebase Authentication, enable Email/Password.
2. In Firestore Rules, publish the rules supplied in the setup conversation.
3. This app uses Firebase JS SDK modules. Do not open index.html directly as a file on Android. It must be served from an HTTPS website (for example Firebase Hosting or GitHub Pages) or localhost.
4. The Firestore rules discussed so far permit public job reads and authenticated worker-profile reads. Users must sign in to view worker profiles.
5. Do not add payment details or upgrade to Blaze for this MVP.
6. Before public launch, add moderation/reporting, input validation, privacy/consent wording, account deletion, rate limits, and review the security rules carefully.

Firebase project ID: piecework-connect-2bd9b
