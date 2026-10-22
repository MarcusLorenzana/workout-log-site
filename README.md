## Workout Logger Site

Static marketing site for IronStack, deployed on Cloudflare Pages.

## Support Form (Formspree)

This repo now includes:

- `support/index.html`: user-facing support page with a Formspree contact form

### Configuration

- Public contact email: `info@buildwithzana.com`.
- Support form endpoint: `https://formspree.io/f/xgolryej`.
- In the Formspree dashboard, set the notification recipient for form `xgolryej` to
  `info@buildwithzana.com` and complete any email verification Formspree requests.
  The recipient is configured in Formspree, not in the HTML form; changing the
  public contact links does not change submission delivery.
- Deploy the site to Cloudflare Pages after changing the HTML.
