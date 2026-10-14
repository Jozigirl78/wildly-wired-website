# Wildly Wired website

*Different minds. Same need to belong.* 🌈

The one-page home for Wildly Wired: the Wildly Wired Humans community, the Square shop and Wildly Wired Stories. It's a single file, `index.html`, with no build step. Fonts load from Google Fonts; everything else is inside the file.

## 1. Swap in your real links

Open `index.html` and use find-and-replace (Ctrl+H, or Cmd+Option+F on a Mac) for each placeholder below. Replace every match, not just the first one.

| Find this | Replace with | Where it shows up |
|---|---|---|
| ~~`https://YOUR-SHOP.square.site`~~ | done: https://wildly-wired.square.site | nav "Shop", hero button, shop section, footer (5 places) |
| ~~`https://www.facebook.com/groups/YOUR-GROUP`~~ | done: https://www.facebook.com/groups/wildlywiredhumans/ (Women group: https://www.facebook.com/groups/wildlywiredwomen/) | hero "Find your people", community section, footer (4 places) |
| ~~`https://www.instagram.com/YOUR-HANDLE`~~ | done: https://www.instagram.com/wildlywiredhumans/ | footer |
| ~~`https://www.facebook.com/YOUR-PAGE`~~ | done: https://www.facebook.com/wildlywired/ | footer |
| `https://YOUR-NEWSLETTER-SIGNUP-LINK` | your email sign-up form (Mailchimp, MailerLite, Kit, etc.) | "Get the monthly letter" button |

The same list sits in a comment near the top of `index.html` (search for `EDIT YOUR LINKS HERE`). When you're done, search for `YOUR-` and you should get zero matches.

**Images:** all pictures live in the `images/` folder (Lisa's photo, mood board pieces, and `sky.svg` for the stars and galaxies). To swap one, upload a new file with the same name.

## 2. Put it online (Netlify)

The site is published by Netlify, which rebuilds it automatically every time a change is merged into `main`. `netlify.toml` already tells Netlify there's no build step, so there's nothing to configure.

**First-time setup**
1. Go to [app.netlify.com](https://app.netlify.com) and sign up with GitHub.
2. **Add new project → Import an existing project → GitHub**, and pick `wildly-wired-website`. If it isn't listed, click **Configure the Netlify app on GitHub** and give it access to this repo.
3. Click **Deploy**. You get a `.netlify.app` link within a minute.

**Custom domain (wildlywired.co.uk)**
1. In Netlify: **Domain management → Add a domain**, enter `wildlywired.co.uk`.
2. Netlify shows the DNS records to add. Copy them into your domain registrar's DNS settings.
3. Once DNS updates (minutes to a few hours), Netlify switches on free HTTPS by itself.

**Making changes:** ask Claude in the project thread; it opens a pull request here. Merge it, and Netlify publishes it. Don't edit the site in Replit or other AI builders, or you'll end up with two versions.

## 3. Before you share the link

- [ ] Search `index.html` for `YOUR-`: zero matches.
- [ ] Click every button on your phone and on a laptop.
- [ ] Shop button opens the Square shop (checkout always happens there, never on this site).
- [ ] Group button opens the Wildly Wired Humans join page.

## Brand notes

Colours, fonts and tone come from the Wildly Wired brand brief: night sky `#120C2B`, hot pink `#FF5FA2`, sunshine `#FFD84A`, mint `#4FE39A`, sky blue `#4CC3FF`; Shrikhand for headlines, Atkinson Hyperlegible for everything else. Keep contrast high and avoid flashing or fast animation.
