# Space Traveller

Design a spacecraft, launch it anywhere from the Sun to Pluto, and bring the science home.

A browser game for students aged 10–14, made for the **NASA Space Apps Challenge 2026** ("Space Mission Design Game" challenge).

**Play it:** https://sahandurairaj.github.io/Space-Traveller/

## How to play

1. **Pick a destination.** There are 10: the Sun, Mercury, Venus, the Moon, Mars, Asteroid Psyche, Europa, Titan, Uranus and Pluto.
2. **Build your spacecraft.** Add instruments, power, engines, antennas and protection. Stay within the budget, mass, power and fuel limits.
3. **Pick a rocket.** Bigger rockets lift more but cost more. Any money left becomes your emergency reserve.
4. **Watch the launch and pilot the mission.** Countdown, liftoff, stage separation, then fly a 3D space highway yourself: a glowing, curving path that leads to your destination. When you arrive, a 3D scene shows your spacecraft orbiting (or flying past) the world. Trips take about 5 minutes (the Moon) up to 15 minutes (Uranus and Pluto). Press **P** to pause. If you close the game mid-flight, it picks up where you left off.
   - **← →** arrow keys (or A/D) steer, **↑** boosts, **↓** brakes. Stay on the path: drifting off slows you down. On phones and tablets, use the on-screen buttons.
   - Dodge the occasional space rock or comet (each hit costs $5M in repairs). Collect gold **SpaceCoins**, blue data sparks (+2% science each) and green repair kits (+$5M).
   - Watch for milestones as you cross the orbits of other planets, and extra rocks in the asteroid belt.
   - At each checkpoint, deal with an event like a solar flare, dust storm, radiation or a computer glitch.
   - Phones vibrate for liftoff, crashes, hits and big moments: strong pulses on Android, haptic taps on iPhone (iOS 18+). Use the **Vibration** / **Haptics** button to turn it off.
5. **Read your report card.** See your stars and badges, what went wrong, and a fact from the real NASA mission.
6. **Upgrade in the Hangar.** Spend SpaceCoins (collected in flight, plus 20 per star and 10 per badge) on upgrades that stay with you:
   - **Engine upgrade** (5 levels): up to 60% faster travel.
   - **Debris shield** (5 levels): blocks up to 10 hits per trip and recharges as you fly.
   - **Coin magnet** (3 levels): pulls coins and data sparks toward you.

   Coins and upgrades are saved on your device.

## What players learn

- Every part costs money **and** mass. Heavier spacecraft need bigger, pricier rockets.
- Solar power drops with distance from the Sun. Far away, you need a nuclear battery (RTG).
- Science only counts if the data gets back to Earth.
- Backups and protection cost more but save missions.
- Getting into orbit takes fuel. Without enough, you can only fly past.

## Install it as an app

Space Traveller is an installable web app: it has an app icon, opens full screen and works offline. See **[APP-GUIDE.md](APP-GUIDE.md)** for step-by-step instructions to:

1. Install it on any phone or computer (free).
2. Publish it on Google Play.
3. Build native iPhone and Android apps with Capacitor (the `native-app` folder), which gives the strongest haptics.

Privacy policy: [privacy.html](privacy.html). The game collects no personal data.

## Run it locally

It's one page with no build step. Open `index.html` in any modern browser. Installing and offline play need it served over https, for example on GitHub Pages.

## Credits and sources

Costs, masses and scores are simplified for play. Sunlight levels, trip times and the mission facts come from NASA.

Planet and Sun images load from the [NASA Photojournal](https://photojournal.jpl.nasa.gov/) and are credited in the game. If a photo can't load, the game shows a realistic illustration it draws itself, with craters, clouds, ice cracks and lighting.

| Destination | Image | Credit |
| --- | --- | --- |
| The Sun | [PIA26681](https://photojournal.jpl.nasa.gov/catalog/PIA26681) | NASA/GSFC/Solar Dynamics Observatory |
| Mercury | [PIA15162](https://photojournal.jpl.nasa.gov/catalog/PIA15162) | NASA/Johns Hopkins APL/Carnegie Institution of Washington |
| Venus | [PIA00104](https://photojournal.jpl.nasa.gov/catalog/PIA00104) | NASA/JPL |
| The Moon | [PIA00405](https://photojournal.jpl.nasa.gov/catalog/PIA00405) | NASA/JPL/USGS |
| Mars | [PIA00407](https://photojournal.jpl.nasa.gov/catalog/PIA00407) | NASA/JPL/USGS |
| Asteroid Psyche (artist's concept) | [PIA24472](https://photojournal.jpl.nasa.gov/catalog/PIA24472) | NASA/JPL-Caltech/ASU |
| Europa | [PIA19048](https://photojournal.jpl.nasa.gov/catalog/PIA19048) | NASA/JPL-Caltech/SETI Institute |
| Titan | [PIA14602](https://photojournal.jpl.nasa.gov/catalog/PIA14602) | NASA/JPL-Caltech/Space Science Institute |
| Uranus | [PIA18182](https://photojournal.jpl.nasa.gov/catalog/PIA18182) | NASA/JPL-Caltech |
| Pluto | [PIA19952](https://photojournal.jpl.nasa.gov/catalog/PIA19952) | NASA/Johns Hopkins APL/Southwest Research Institute |

Other sources:

- [NASA Juno mission](https://science.nasa.gov/mission/juno/)
- [JPL Mars 2020 Perseverance power press kit](https://www.jpl.nasa.gov/news/press_kits/mars_2020/launch/mission/spacecraft/power/)

Fonts: Bungee, Atkinson Hyperlegible and IBM Plex Mono, from Google Fonts.
