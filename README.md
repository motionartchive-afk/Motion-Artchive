# Motion Artchive

Static site. `index.html` must stay in the repository root.

## Deploy on Vercel
1. Push this folder to a GitHub repository (index.html at the top level).
2. In Vercel: Add New > Project > import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Deploy.

## Update content
- Videos: replace files in `assets/video/` (keep the same names).
- Posters and logo: `assets/img/`.

- Client videos: `assets/video/client/` (client-01.mp4 to client-17.mp4) with posters in `assets/img/client/`.

## Contact and policies
- Email: motionartchive@gmail.com. WhatsApp: +62 851-4777-0039 (the number is set in the `WA` constant in `index.html` and in the `wa.me` links).
- The contact form opens the visitor's email app. To receive submissions directly, switch it to a form service such as Formspree or Web3Forms.
- Terms, privacy, refund and license texts live in the `<dialog id="lg">` block at the bottom of `index.html`. Review them against how you actually work.

## Before launch
- Testimonials and the "recent deliveries" feed were removed because they were sample data. Add real ones back only when they are real.
- Add titles and categories to the work captions: `<figcaption><b>Work 01</b></figcaption>`.
