# jaysmarti.github.io

Static pages for **jaysmarti tools**, a personal tool for the @jaysmarti woodturning account
(uploads the owner's own videos to TikTok drafts and shows his own video statistics).

| Page | Purpose |
|---|---|
| [index.html](https://jaysmarti.github.io/) | **Link-in-bio page** (Instagram bio link): Amazon storefront (featured), YouTube @jaysmartiwoodworking, Instagram @jaysmarti, TikTok @jaysmartwoodworking, "message me". Images in `img/`. GoatCounter analytics (jaysmarti.goatcounter.com) with per-button click events and `?src=ig/tt/yt` sources |
| [terms.html](https://jaysmarti.github.io/terms.html) | Terms of Service (TikTok app requirement) |
| [privacy.html](https://jaysmarti.github.io/privacy.html) | Privacy Policy (TikTok app requirement) |
| [callback.html](https://jaysmarti.github.io/callback.html) | TikTok Login Kit redirect: shows the login result so the owner can copy it into the local tool; sends nothing anywhere |
| `tiktok8tVrVtK66hRFVOAYlJauI8Fp7HRNb5mv.txt` | TikTok URL-prefix ownership verification for the first app ("jaysmarti tools"). **Do not delete** |
| `tiktokChA8I3nzQjcb3vgXgP8VllutcTsv9IHe.txt` | TikTok URL-prefix verification for the second app ("Jay \| Woodworking & Outdoors", added 2026-10-18). **Do not delete** |

Published with GitHub Pages from the `main` branch.

## Parked campaign buttons (removed 2026-10-16)
The owner removed three Amazon Creator Connections buttons "for now". The plan is to add each one back, above the
YouTube button, once a video using that tool is live.

| Button | Amazon link | GoatCounter event |
|---|---|---|
| 🪵 Mini block plane (Jorgensen No.101) | https://www.amazon.com/dp/B0BVZK331X?ref=t_ac_view_request_product_image&campaignId=amzn1.campaign.FZTBORP4GVA7&linkCode=tr1&tag=javlonismatov-20&linkId=amzn1.campaign.FZTBORP4GVA7_1791481245152 | click-plane |
| 🗜 6" F-clamps (4-pack) | https://www.amazon.com/dp/B0F28MHL96?ref=t_ac_view_request_product_image&campaignId=amzn1.campaign.2K22K7EU4XZLX&linkCode=tr1&tag=javlonismatov-20&linkId=amzn1.campaign.2K22K7EU4XZLX_1791481284382 | click-clamps |
| 🔨 Small rubber mallet (non-marring, 8 oz) | https://www.amazon.com/dp/B0H1JSZNJQ?ref=t_ac_view_request_product_image&campaignId=amzn1.campaign.2Z4UXI4YH0HGW&linkCode=tr1&tag=javlonismatov-20&linkId=amzn1.campaign.2Z4UXI4YH0HGW_1791488593889 | click-mallet |

The full button HTML, with icons, is in commits 4d05e8e, cd14e5e and 913d73a. Restore one with
`git show 913d73a -- index.html`. Each button's note must keep the "#ad paid link" label.
