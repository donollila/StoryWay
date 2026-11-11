# StoryWay Kids

Narrated choose-your-path stories for kids. Every choice shows a character trait (empathy, honesty, courage, vulnerability, and more). Weaker choices play out with real consequences and a chance to try again. Each story ends with a "What I learned" page and talk-about-it questions for parents.

**Play it:** https://donollila.github.io/StoryWay/

On iPhone, open the link in Safari, tap Share, then **Add to Home Screen**. After the first visit it works offline.

## How it's organized
- `index.html`: the app
- `catalog.json`: the list of stories (owned and locked)
- `stories/<id>/story.json` and `stories/<id>/audio/`: one pack per story
- `audio/common/`: shared narration clips
- `sw.js`, `manifest.json`, icons: home-screen app and offline support
