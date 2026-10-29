# Yuvashree Murali — Terminal Engineering Portfolio (Option B)

A distinct, terminal-first Next.js portfolio with a professional portrait, interactive CLI, career timeline, public-safe project descriptions, and a simulated network lab.

## Run locally

Install Node.js 20.9+ and run:

```bash
npm install
npm run dev
```

Visit http://localhost:3000. Verify production build with `npm run build`.

## Deploy to Vercel (free Hobby plan for eligible personal, noncommercial use)

1. Create a **new** GitHub repository, e.g. `yuvashree-terminal-portfolio`.
2. Upload the **contents** of this folder, retaining the `app/` and `public/` directories. Do not flatten folders. The root should contain `package.json` and `app/`.
3. Visit https://vercel.com/new and import the new repository.
4. Framework: Next.js; Root Directory: `./`; other settings: defaults.
5. Deploy. The resulting URL will be a separate website from Option A.

## Customize

- Profile picture: replace `public/yuvashree-profile.png` with another image of the same name.
- Career and project content: edit the `roles` and `projects` arrays in `app/page.tsx`.
- Theme: edit CSS variables at the beginning of `app/globals.css`.
- LinkedIn URL: update `linkedIn` in `app/page.tsx`.
- Terminal commands: update `execute()` in `app/page.tsx`.

## Notes

- The command line, BGP output, traceroute and network topology are **educational simulations**; they are not connected to real networks.
- Employer case studies intentionally avoid confidential details. Review all public-facing claims before publishing.
- No resume file or email address is included, because those assets were not supplied.
- The professional photograph is provided by the portfolio owner.
