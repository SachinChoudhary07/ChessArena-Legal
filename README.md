# Legal pages

Host these files on HTTPS (Vercel recommended) before Play submission.

## Links required

| Page | Required for | In-app use |
|------|----------------|------------|
| Privacy Policy | Google Play Data safety / App content | Profile, Register |
| Account Deletion | Google Play account deletion URL | Profile |
| Terms of Service | Recommended (signup copy) | Register |

## Local files

- `index.html`
- `privacy-policy.html`
- `delete-account.html`
- `terms.html`
- `styles.css`

## Deploy

```bash
cd legal
npx vercel --prod
```

Then set the live URLs in `lib/Constant/legal_urls.dart` and Play Console.
