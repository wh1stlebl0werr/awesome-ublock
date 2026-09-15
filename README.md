Documentation of the current filter lists:
- instagram-reels-hardened intercepts the API calls that load reels content & removes them all. Instagram posts are slightly broken due to there being changes in the interactive meta. Also hides sponsored posts. No class selectors used since Meta redeploys CSS every 48-72hrs, all rules use stable attributes like href and aria-label.
- youtube-clean is a decluttering filter that removes shorts, algorithmic shelves, homepage clutter, sidebar bloat, and channel page noise. Strips distractions in video page, including merch, surveys, popups, membership nags, & paid comments. Bypasses YouTube's adblock detection and blocks select JS files for lighter page loads.

Add the filter lists to your ad-blocker!
- [Subscribe to youtube-clean](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/wh1stlebl0werr/awesome-ublock/main/youtube-clean.txt&title=YouTube%20Clean)
- [Subscribe to instagram-reels-hardened](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/wh1stlebl0werr/awesome-ublock/main/instagram-reels-hardened.txt&title=Instagram%20Reels%20Hardened)

My ad-blocking solution that I use on a daily basis.
- Currently using uBlock Origin (Manifest V2, Sideloaded).
- On Supermium M144.0.7559.256 (Due to RAM limitations).

Plans to execute on this repository:
- Documenting each filter with its purpose, reasoning & known breakage, with a changelog to track tested updates.                ❌
- Building tiered presets as importable filter lists + a 1-stop preset for users who want clean browsing out of the box.         ❌
- Expanding filter coverage to more platforms & cookie consent banners, combining 3rd-party lists that work without conflict.    ❌
- Adding DNS resolver recommendations with benchmarks covering latency, logging policy & DNSSEC support + bonus NSFW filtering?  ❌

This is nothing more than a hobby, so I won't spend much time here - but efforts will be present.
Whoever's content I add/use here, they shall get their proper credits. 
Any tip or query can be slid into my email -> *vxrnzr@gmail.com*.
Help is always appreciated!
