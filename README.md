# James Wild & Company — B2B Trade Pitch Microsite

## What's new in this pass (all on wild-earth-stays.html)

**Real content pulled from your live sites.** I fetched wildearthstays.com/about, your Aguas Claras listing (main page + #view-stays + #overview), and the four lodge sites you named, to ground everything in real facts rather than invented copy.

**The platform description, rewritten with your exact language:**
> "James Papagno, Founder & CEO of James Wild & Company, built Wild Earth Stays as a personal, hand-selected portfolio: places, itineraries, and vessel small cruises that James, or a trusted on-the-ground DMC partner, has either stayed in or carefully vetted for the JWC portfolio. Each is recorded and added to the Ledger as a stay worthy of return, and the platform itself is a dedicated resource to educate new and existing advisors."

This now sits as a featured block right below the hero.

**Real Aguas Claras images, hotlinked from your own live listing** (not screenshots, not placeholders):
- The dossier's archive strip (4 real property photos)
- The room manifest table (each room category now shows its real photo, matching wildearthstays.com/property/aguas-claras#view-stays)
- The "How Travelers See This Property" preview now uses your actual page hero image

Since these are hotlinked directly to your own CDN (cdn.prod.website-files.com), they'll load fine once this is live on the web — my local preview environment has no internet access, so you'll see broken-image icons if you open the file directly on this machine, but that's a sandbox limitation, not a bug. One practical note: hotlinking means these images depend on your site staying live at those URLs. If you ever redesign wildearthstays.com or move that CMS, these links could break — worth downloading and self-hosting the images here eventually.

**Four new gallery entries, with real names and facts** (Pacuare Lodge, DumaTau Camp, Matachica Resort, Le Taha'a), replacing the previous placeholder-named entries:
- **Pacuare Lodge**, Costa Rica — remote rainforest lodge on the Pacuare River, reached by whitewater raft, founded 1986, flagship of Böëna Lodges
- **DumaTau Camp**, Botswana — "roar of the lion" in Setswana, Africa's highest density of elephants, Linyanti Reserve, Osprey Retreat spa
- **Matachica Resort**, Belize — adult-only, 33 casitas and villas, Ambergris Caye, Michelin-listed
- **Le Taha'a**, French Polynesia — first Relais & Châteaux property in French Polynesia, overwater suites, Bora Bora views

**Important: I did not pull photography from these four sites.** They're other companies' proprietary marketing images, not yours — different from Aguas Claras, which is your own listing. These four still use the placeholder treatment with real names and entry numbers attached. The standard move here is requesting an approved trade/media image kit directly from each property (Pacuare, Wilderness, The Lighter Collection, Pearl Resorts) — most hotels have one for exactly this purpose.

**IGGI now has its own brand color** — a deep forest green (#3F5A45), scoped only to the "Meet IGGI" section: the badge, the phase labels, the chat bubble. Distinct from CRUX's orange/rust on the Safaris page, both sitting inside the master Ledger palette.

**Header and footer logo sizing confirmed** — both render cleanly (56px in the header, 88px in the footer), nothing was actually broken, but I checked both directly to be sure.

## One important flag: your own About page says 1981, age 17 — not 1982

I fetched wildearthstays.com/about directly, and it reads: *"At 17, he picked up a surfboard and set off for a small, little-known island in the Bahamas called Eleuthera. It was 1981."*

Every "1982" on this site — including the ones baked directly into your logo artwork (the seal, the hare stamp) — currently doesn't match your own official story. I did **not** silently change this, since it would mean re-touching logo images, not just text. Worth a decision on your end: is 1982 or 1981 the version you want to use going forward? I can update all the text instances immediately either way; the logo artwork would need to be reprocessed separately if the year changes.

## Deploying
Upload all files + `assets` folder to your GitHub repo (`jpapagno-ux/ILTMVIEW`) — Vercel/Pages redeploys automatically if connected.
