# Bobzi Labs legal pages

These are public privacy policies and account deletion pages for games by Bobzi Labs. They are
published with GitHub Pages from the `main` branch, at the repository root.

| Page | URL |
| --- | --- |
| Home | https://bobzilabs.github.io/bobzi-labs-legal/ |
| Pocket Ricochet privacy policy | https://bobzilabs.github.io/bobzi-labs-legal/pocket-ricochet/privacy/ |
| Pocket Ricochet account deletion | https://bobzilabs.github.io/bobzi-labs-legal/pocket-ricochet/account-deletion/ |

## Structure

```text
index.html                     legal homepage (lists every game)
assets/style.css               shared styles (no external fonts, scripts or trackers)
<game-slug>/privacy/           one privacy policy per game
<game-slug>/account-deletion/  one account deletion page per game
```

**To add a game:**
1. Copy the `pocket-ricochet/` folder to a new game slug.
2. Rewrite both pages for that game's actual data practices.
3. Add a card for it on `index.html`.

**Rules:**
- This repository holds only public static pages.
- Never add game source code, configuration, credentials, keys or player data.

Contact: bobziLabs@gmail.com
