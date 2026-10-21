# Opportunity Lab: Founder Itch Feed (concept demo)

**A visual prototype of a live feed of problems founders and developers say out loud,
so builders can find them and fix them.**

**▶ Live demo:** https://gowthamkumar09.github.io/opportunity-lab-itch-feed/opportunity-lab-itch-feed.html

*(update this link if you name the repo differently)*

> **Demo only.** The feed, counters and quotes are **sample data**. The sign-up box
> stores nothing. No social media data is collected or connected yet.

Inspired by Razorpay's Fix My Itch program. This project is independent and is
**not affiliated with Razorpay or any social media platform.**

## The idea

Founders rarely file tickets about their problems. They vent in posts, threads,
podcasts and interviews. This concept imagines a feed that gathers those
"itches" in one place, groups repeats, and links back to where each was said, so
someone can reach the person, build the fix, or pitch it to a program.

It is the "problem discovery" vision. For a working tool that scores and
validates ideas with evidence, see my other project:
[OpportunityLab](https://github.com/Gowthamkumar09/opportunity-lab).

## What the demo includes

- 3D night-time Earth globe (Three.js) that follows the mouse
- Demo itch feed with source filters. Every card carries a "Demo" tag
- Animated counters, sample quotes and a "how it works" section
- Glass sticky navigation, scroll animations and a scroll-progress bar
- Responsive layout for desktop, tablet and mobile
- Respects `prefers-reduced-motion`

## About the globe

The 3D globe in the hero is a visual metaphor, not live data.

- **Earth and city lights:** a real night-time map of the world. The glowing
  lights mark where people actually live and build.
- **Gold dots:** twelve major startup cities (such as San Francisco, London,
  Bengaluru, Singapore and Lagos) where founder problems might be posted.
- **Violet arcs and pulses:** each pulse represents a founder problem travelling
  toward someone who could fix it. The violet stands for the AI layer that would
  listen for these problems and match them.
- **Orbit ring and stars:** decoration only.

The arcs run between hand-picked cities at random. They illustrate the idea and
are not connected to real posts, people or locations.

## Run it

Open `index.html` in a browser. No install needed. It loads Three.js and a web
font from the internet, so you need to be online.

## Honest limitations

- All feed items, names, numbers and quotes are made up for the demo.
- There is no backend, database or accounts.
- Real data would need platform APIs, access keys and a server. Several
  platforms restrict or charge for search access, so this is not trivial.

## Roadmap

- [ ] "Post your itch" form with a small database
- [ ] Real feed from open sources (Hacker News, Bluesky)
- [ ] AI filter that separates real problems from noise and groups duplicates
- [ ] Each itch links back to its original source
- [ ] Optional paid sources (for example X) behind a spending cap

## Tech

HTML, CSS and JavaScript in a single file. 3D with [Three.js](https://threejs.org/)
(loaded from cdnjs). Font: Manrope (Google Fonts).

## Credits

- Three.js (MIT).
- The Earth texture is made from the example images shipped with the
  [`three-globe`](https://github.com/vasturiano/three-globe) package
  (MIT, by Vasco Asturiano). That package does not document where those images
  originally came from. They look like NASA Earth imagery, but this is unverified.
  If you reuse this beyond a demo, swap in a map with a clear license, such as
  imagery from [NASA Visible Earth](https://visibleearth.nasa.gov/).

## License

MIT. See [LICENSE](LICENSE).
