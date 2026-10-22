# patrickbassett1381.github.io

Source for my personal portfolio site: **https://patrickbassett1381.github.io**

Static pages, no build step, showing the AI system I built to run my Haas MBA:

| Page | What it covers |
|---|---|
| `index.html` | Overview: the whole system as one process flow sheet, plus where everything lives |
| `infrastructure.html` | Lane 1: bCourses → Drive sync ([repo](https://github.com/patrickbassett1381/bcourses-to-drive-sync)), notes sorter, Course Index, Drive inbox, term setup, weekly health audit |
| `study.html` | Lane 2: class prep sheets, Concept Log digest, homework coach, exam kit, weekly class review |
| `recruiting.html` | Lane 3: coffee-chat prep, fit tracking, resume tailoring, interview drills |

All pages share `styles.css`.

**Link previews:** each page's `<head>` has Open Graph tags (`og:title`, `og:description`, `og:url`, `og:image`) so a shared link shows as a card on LinkedIn, Slack and iMessage. All pages use `og-image.png` (1200×630). When you add a page, copy that block and change the title, description and URL. After changing it, re-scrape the link in LinkedIn's Post Inspector (LinkedIn caches previews for ~7 days).

## Updating the site
Edit the page, then commit and push to `main`. GitHub Pages republishes in about a minute.
Site metrics come from the story bank (Career Coach Project, `Resume/StoryBank_DRAFT.md`): change it there first, then here.
