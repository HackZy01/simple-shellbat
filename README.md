# simple shellbat
a taiHEN plugin that adds battery percentage to the statusbar

![34% screenshot](https://github.com/user-attachments/assets/70d4df18-80bf-4ad6-bedf-ae5c536d2599) ![2% screenshot](https://github.com/user-attachments/assets/70988e70-5ede-48cd-bc0a-c91f901f4aa3)

**It's more common for devices to turn off at 1-2% instead of 13%**

## Installation

Add this plugin under `*main` section in `ur0:tai/config.txt` / `ux0:tai/config.txt`:

```c
*main
ur0:tai/shellbat.suprx
```

## Why?

PlayStation Vita doesn't allow the battery to fully drain so usually the console goes into deep sleep at around 12-13%. <br> This plugin is meant to recalculate the percentage based on this fact thanks to [leonardputra's fork for IRS-1001 models]([https://github.com/leonardputra/vita-shellbat-irs-1001)

