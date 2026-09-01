# Martin Stamenov — Portfolio

Single-file portfolio site. No build step, no dependencies, no framework —
one `index.html` with everything inline (styles, scripts, the neural field,
the mind-sphere, the holo rings). Fonts load from Google Fonts.

## Host on GitHub Pages (free, 2 minutes)

1. Create a new repository named exactly: `stamenovmartin.github.io`
2. Upload `index.html` to the repository root (drag & drop on github.com works)
3. Wait ~1 minute. The site is live at: https://stamenovmartin.github.io

Updates: replace `index.html` and push — changes go live automatically.

## Host anywhere else

Any static host works the same way (Netlify, Vercel, Cloudflare Pages,
or any plain web server): serve `index.html`, done.

## Custom domain (optional, later)

Buy a domain, add a `CNAME` file containing the domain name to the repo,
and point the domain's DNS (CNAME record) at `stamenovmartin.github.io`.
Then update the `og:url` meta tag in `index.html`.

## Editing

Everything is in `index.html`:
- Content: search for the section text you want to change
- Colors: the `:root` CSS variables at the top
- Neural field behavior: the last `<script>` block (cycle length `T=26`,
  neuron count, link distance `LINK`, the M shape)
