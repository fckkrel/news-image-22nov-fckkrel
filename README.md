# Sunday 22 November 2026 — The World in One Image

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/fckkrel/news-image-22nov-fckkrel/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/fckkrel/news-image-22nov-fckkrel/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

One image summing up the world's news of [Sunday 22 November 2026](https://make.fun/bounty/news-image-20261122), for make.fun's "Sum up 22 November's world news in one image" bounty.

The front page carries 32 stories across 7 regions, every one dated to that single day. The lead is the collapse of the COP31 climate summit in Antalya with no deal. Under it sit seven colour-coded sections: Europe, Middle East, Asia-Pacific, Africa, North America, Latin America, and a markets, science and sport column — from the drone strike on a block of flats near Kyiv and settler arson in the West Bank, to the Cikande factory fire toll in Indonesia, drones over Khartoum, BepiColombo reaching Mercury orbit and Alcaraz winning his first ATP Finals title.

`build_entry.py` draws the page with Pillow (1024×1024, bold headlines sized to stay readable when the image is shrunk) and saves it as `entry.png`. `main.ts` checks that file is a PNG within the bounty's limits and writes it to `/output/entry.png`. No network, no clock, no randomness: Node 22 standard library only, and both runs write the same bytes.
