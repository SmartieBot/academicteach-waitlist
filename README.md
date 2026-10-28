# Academic Tēach · leak waitlist

A one-page waitlist for the "leak" Instagram Story.

- `site/index.html` is the whole page (plain HTML/CSS/JS, no build step). `site/logo.png` is the app icon.
- Sign-ups go to the separate Supabase project **academic-teach-waitlist**, through one function, `join_waitlist(email, role, consent, source)`. That function validates the input, stores each email once, and returns the person's place in line. The public can't read the list.
- `?src=...` on the URL tags which Story a sign-up came from (default `leak-1`).
- Hosted on Render as a static site that publishes `site/`.

**Planned deletion: mid-November 2026** (DPDP). Delete the Supabase project and this Render site. There's a reminder on 15 Nov in Google Calendar.
