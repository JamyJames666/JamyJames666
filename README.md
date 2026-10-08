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

By day I'm a data and analytics engineer. Warehouses and the reporting on top of them. That work has to be right, and right in a way somebody else can audit six months after I've stopped thinking about it.

This account is the other half. It's where the creative projects live, the ones I made because I wanted to, not because a ticket said so. Treat most of what's here as a hobby shelf. These are personal projects, built for me and a handful of people I know, and none of them are asking to be taken seriously. There's no roadmap, no support, and the commit messages get worse on a Sunday.

That said, a fair few exist because something was actually annoying me and nothing off the shelf fixed it. An argument nobody could settle. A number I kept recalculating by hand. A thing that should have taken ten seconds and took ten minutes, every single time. Those ones I cared about, and it shows in the parts that matter.

So, low stakes, real problems. Both things are true.

## Things that are public

| Project | What it is | Why it exists |
|---|---|---|
| [**pool-leaderboard**](https://github.com/JamyJames666/pool-leaderboard) | The office 8-ball ladder. Quarterly ELO seasons, ball difference tie breaks, and a knockout cup every quarter. | "Who is actually best at pool" was an unwinnable argument. Now it has a number attached to it. |
| [**overtime**](https://github.com/JamyJames666/overtime) | Counter-Strike 10-mans as a career rather than a scoreboard. Scrapes Popflash back to 2021, folds smurf accounts into one identity, and puts every player against every map. | Popflash shows you one match at a time, so nobody could prove who had been quietly losing us games for two years. |
| [**jammy-beat-box**](https://github.com/JamyJames666/jammy-beat-box) | A self-hosted Discord music bot with a web dashboard, forked from [muse](https://github.com/museofficial/muse). Paste a 500 track Spotify playlist and run the room from a browser. | Skipping a song by typing a slash command, in a room full of people, is a bad interface. |
| [**Pulse Engine**](https://github.com/JamyJames666/FITBIT) | Health data kept in Postgres rather than binned after a week, with thirteen model layers over it, all written out in TypeScript rather than called out to a Python service. | The app that came with the watch shows you last week and hands you advice without showing its working. |

Plenty more sits in private repos. Some of it is half finished, some of it has other people's names and data in it, and some of it is just not interesting to anyone but me.

## How I tend to build

Work code and this code don't get built the same way, and I think that's right. Production work is planned up front, reviewed, tested and documented, because somebody else ends up owning it and a wrong number costs real money. Here I can start in the middle, bin the first version, and let the shape turn up late. There are only two questions. Does it work, and will I still understand it in March.

- **Small, and finished.** A thing that works end to end beats a bigger thing that is 80 per cent done. I would rather ship a single page that does one job properly.
- **Derive, don't store.** If a number can be recomputed from the raw records, it gets recomputed. Stale derived data is the bug you find six months later.
- **The raw data is the source of truth.** Databases get rebuilt from it. Nothing important should live only in something I would be happy to delete and regenerate.
- **No build step if I can help it.** Dependencies are a cost I pay every time I come back to a project after three months away.
- **Write it down while it's fresh.** Every repo gets a README that explains how it fits together, because future me has forgotten all of it.

Which is probably why half of these turn out to be a scraper, a database and a scoreboard wearing a different hat.

---

<p align="center"><sub>Activity is hidden on purpose. The repositories tab is not, so have a look around.</sub></p>
