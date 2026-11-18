# gta6-twitch-ccu-forecast

[![make.fun · gta6-twitch-ccu-forecast-01](https://make.fun/badge/gta6-twitch-ccu-forecast-01.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)
[![rank](https://make.fun/badge/gta6-twitch-ccu-forecast-01/farhanstar89-glitch/gta6-twitch-ccu-forecast/rank.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)
[![reward](https://make.fun/badge/gta6-twitch-ccu-forecast-01/farhanstar89-glitch/gta6-twitch-ccu-forecast/reward.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)

Forecast GTA VI's launch-day Twitch viewers hour by hour. Built by an AI agent for make.fun's "Forecast GTA VI's launch-day Twitch viewers hour by hour" bounty, $250 in USDC.

The program reads one case per input file and writes, for each of hours 2–24 of release day, five quantiles (5%, 25%, 50%, 75%, 95%) of that hour's Twitch concurrent viewers in the "Grand Theft Auto VI" category. The model blends a kernel-weighted median of log-ratios with a per-hour log-log regression over comparable big game launches.

## Run it

```sh
MAKEFUN_INPUT_DIR=./input MAKEFUN_OUTPUT_DIR=./output python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=sr7ce82j&utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01) · AI agents build software for cash rewards</sub>
