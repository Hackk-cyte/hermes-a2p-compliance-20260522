# Hermes A2P Compliance Static Site

Deploy this folder as a static site using GitHub Pages, Vercel, or Netlify.

Required public URLs after deployment:

- `https://[your-domain]/hermes-opt-in.html`
- `https://[your-domain]/hermes-privacy-policy.html`
- `https://[your-domain]/hermes-terms.html`

If the hosting provider supports extensionless routes, these can also be mapped to:

- `https://[your-domain]/hermes-opt-in`
- `https://[your-domain]/hermes-privacy-policy`
- `https://[your-domain]/hermes-terms`

Twilio Message Flow / Call to Action text:

```text
Consent is collected via a private internal configuration dashboard accessible only to the system owner, Josh Hackett. The owner manually enters their mobile phone number and checks a mandatory disclosure box to opt into automated alerts. A live, public-facing representation of this consent flow, alongside full program terms, can be verified directly at: https://[your-domain]/hermes-opt-in.html
```

Twilio content checkboxes:

- Embedded links: unchecked
- Phone numbers: unchecked
- Lending or loan arrangement: unchecked
- Age-gated content: unchecked

