# Wildly Wired website

*Different minds. Same need to belong.* 🌈

The one-page home for Wildly Wired: the Wildly Wired Humans community, the Square shop and Wildly Wired Stories. It's a single file, `index.html`, with no build step. Fonts load from Google Fonts; everything else is inside the file.

## 1. Swap in your real links

Open `index.html` and use find-and-replace (Ctrl+H, or Cmd+Option+F on a Mac) for each placeholder below. Replace every match, not just the first one.

| Find this | Replace with | Where it shows up |
|---|---|---|
| `https://YOUR-SHOP.square.site` | your Square Online shop address | nav "Shop", hero button, shop section, footer (5 places) |
| `https://www.facebook.com/groups/YOUR-GROUP` | your Wildly Wired Humans group link | hero "Find your people", community section, footer (4 places) |
| `https://www.instagram.com/YOUR-HANDLE` | your Instagram profile | footer |
| `https://www.facebook.com/YOUR-PAGE` | your Facebook Page | footer |
| `https://YOUR-NEWSLETTER-SIGNUP-LINK` | your email sign-up form (Mailchimp, MailerLite, Kit, etc.) | "Get the monthly letter" button |

The same list sits in a comment near the top of `index.html` (search for `EDIT YOUR LINKS HERE`). When you're done, search for `YOUR-` and you should get zero matches.

**Images:** all pictures live in the `images/` folder (Lisa's photo, mood board pieces, and `sky.svg` for the stars and galaxies). To swap one, upload a new file with the same name.

## 2. Put it online

Pick one. Both are free for a site this size.

### Netlify (recommended: fastest, free custom domain support)

1. Go to [app.netlify.com](https://app.netlify.com) and sign in with GitHub.
2. **Add new site → Import an existing project → GitHub**, then pick this repo.
3. Leave the build command **empty** and set the publish directory to `/` (the repo root).
4. Click **Deploy**. You'll get a link like `wildly-wired.netlify.app` in under a minute.
5. Every time a change is merged into `main`, Netlify redeploys on its own.

Optional: **Site configuration → Change site name** to get a nicer `.netlify.app` address, and **Domain management** to connect your own domain (e.g. `wildlywired.co.uk`).

### Replit

1. Go to [replit.com](https://replit.com), click **Create App → Import from GitHub**, and pick this repo.
2. Replit detects a static HTML site. Press **Run** to preview it.
3. Click **Deploy → Static** and set the public directory to `/`. Static deploys are the cheapest option and need no server.
4. After you merge changes on GitHub, pull them into Replit (Git pane → Pull) and redeploy.

Netlify updates itself from GitHub automatically; Replit needs that pull-and-redeploy step, which is why Netlify is the easier choice here.

## 3. Before you share the link

- [ ] Search `index.html` for `YOUR-`: zero matches.
- [ ] Click every button on your phone and on a laptop.
- [ ] Shop button opens the Square shop (checkout always happens there, never on this site).
- [ ] Group button opens the Wildly Wired Humans join page.

## Brand notes

Colours, fonts and tone come from the Wildly Wired brand brief: night sky `#120C2B`, hot pink `#FF5FA2`, sunshine `#FFD84A`, mint `#4FE39A`, sky blue `#4CC3FF`; Shrikhand for headlines, Atkinson Hyperlegible for everything else. Keep contrast high and avoid flashing or fast animation.
