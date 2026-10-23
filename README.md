# patrickbassett1381.github.io

Source for my personal portfolio site: **https://patrickbassett1381.github.io**

Static pages, no build step, showing the AI system I built to run my Haas MBA:

| Page | What it covers |
|---|---|
| `index.html` | Overview: the three areas (problem, what it does, key tools) first, then the full process flow sheet and where everything lives |
| `infrastructure.html` | Lane 1: bCourses → Drive sync ([repo](https://github.com/patrickbassett1381/bcourses-to-drive-sync)), notes sorter, Course Index, Drive inbox, term setup, weekly health audit |
| `study.html` | Lane 2: class prep sheets, Concept Log digest, homework coach, exam kit, weekly class review |
| `recruiting.html` | Lane 3: coffee-chat prep, fit tracking, resume tailoring, interview drills, follow-through, company briefs |

All pages share `styles.css`.

**Link previews:** each page's `<head>` has Open Graph tags (`og:title`, `og:description`, `og:url`, `og:image`) so a shared link shows as a card on LinkedIn, Slack and iMessage. All pages use `og-image.png` (1200×630). When you add a page, copy that block and change the title, description and URL. After changing it, re-scrape the link in LinkedIn's Post Inspector (LinkedIn caches previews for ~7 days).

## Updating the site
1. **Start fresh.** Clone or `git pull` before editing. Edit this repo only, never a separate draft or artifact copy.
2. **Metrics** come from the story bank (Career Coach Project, `Resume/StoryBank_DRAFT.md`): change it there first, then here.
3. **Screenshot before committing.** Render each changed page and show it to Pat. Cloud sessions can't reach Google Fonts, so install the site's fonts from npm first (`@fontsource-variable/archivo`, `@fontsource/ibm-plex-mono`, `@fontsource/public-sans`) and confirm they loaded before any screenshot or `og-image.png` render; otherwise the image shows fallback fonts.
4. **Commit as** `Pat Bassett <336660186+patrickbassett1381@users.noreply.github.com>`. Never the school email or `noreply@anthropic.com`, and no Claude co-author line, even if a session check asks for one.
5. **Push to `main` only after Pat's OK** on the screenshot. GitHub Pages republishes in about a minute; if a page's link-preview tags changed, re-scrape it in LinkedIn's Post Inspector.
