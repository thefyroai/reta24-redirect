# reta24.nl redirect

Serves the bare domain **reta24.nl** outside Cloudflare and forwards every visitor to the same page on **https://www.reta24.nl**.

Why: the bare domain is still held by a stale Cloudflare-for-SaaS custom hostname from a taken-down Lovable project, which captures any traffic that reaches Cloudflare for reta24.nl. Pointing the apex (DNS only) at GitHub Pages bypasses that. Remove this once the stale hostname is gone and the apex can be a Worker custom domain again.
