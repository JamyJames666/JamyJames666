<h1 align="center">JamyJames</h1>
<p align="center"><strong>Most of this is for fun. Some of it fixed something that was genuinely bothering me.</strong></p>

<p align="center">
  <img alt="Mostly weekends" src="https://img.shields.io/badge/built-mostly%20weekends-5A8F5A?style=flat-square">
  <img alt="Scope personal" src="https://img.shields.io/badge/scope-personal-444?style=flat-square">
  <img alt="Seriousness low" src="https://img.shields.io/badge/seriousness-low-444?style=flat-square">
  <img alt="Stakes occasionally real" src="https://img.shields.io/badge/stakes-occasionally%20real-D92A50?style=flat-square">
</p>

---

## The honest framing

Treat most of what's here as a hobby shelf. These are personal projects, built for me and a handful of people I know, and none of them are asking to be taken seriously. There's no roadmap, no support, and the commit messages get worse on a Sunday.

That said, a fair few of them exist because something was actually annoying me and nothing off the shelf fixed it. An argument nobody could settle. A number I kept recalculating by hand. A thing that should have taken ten seconds and took ten minutes, every single time. Those ones I cared about, and it shows in the parts that matter.

So, low stakes, real problems. Both things are true.

## Things that are public

| Project | What it is | Why it exists |
|---|---|---|
| [**pool-leaderboard**](https://github.com/JamyJames666/pool-leaderboard) | The office 8-ball ladder. Quarterly ELO seasons, ball-difference tie breaks, and a knockout cup every quarter. | "Who is actually best at pool" was an unwinnable argument. Now it has a number attached to it. |
| [**music-private-**](https://github.com/JamyJames666/music-private-) | TypeScript. | <!-- one line from you and I'll fill this in --> |

Plenty more sits in private repos. Some of it is half-finished, some of it has other people's names and data in it, and some of it is just not interesting to anyone but me.

## How I tend to build

- **Small, and finished.** A thing that works end to end beats a bigger thing that is 80 per cent done. I would rather ship a single page that does one job properly.
- **Derive, don't store.** If a number can be recomputed from the raw records, it gets recomputed. Stale derived data is the bug you find six months later.
- **The raw data is the source of truth.** Databases get rebuilt from it. Nothing important should live only in something I would be happy to delete and regenerate.
- **No build step if I can help it.** Dependencies are a cost I pay every time I come back to a project after three months away.
- **Write it down while it's fresh.** Every repo gets a README that explains how it fits together, because future me has forgotten all of it.

## Elsewhere

Day job is data engineering, warehouses and the reporting on top of them. Which is probably why half of these turn out to be a scraper, a database and a scoreboard wearing a different hat.

---

<p align="center"><sub>Activity is hidden on purpose. The repositories tab is not, so have a look around.</sub></p>
