# Go live

You've connected your platform. The finish line is the same for everyone.

## Test the connection

In **Commerce → Connection**, click **Test connection** → expect green (HTTP 200 + latency). Once
green, catalog sync starts automatically and AI agents can discover your products.

Watch **Recent errors** for any outbound issues — they're shown in plain language (e.g. "couldn't
reach your store"), not raw stack traces.

## Production tips

- **HTTPS** — required in production. (Shopify / WooCommerce are HTTPS already; for custom REST, use
  HTTPS in production.)
- **Custom REST timeout** — set a per-request timeout you can meet (default 30s; configurable 5–60s).
- **Your store address** — a free `*.ecommxai.com` subdomain, or [your own domain](your-domain.md).

That's it — connection green + sync running = you're discoverable by AI agents. 🎉
