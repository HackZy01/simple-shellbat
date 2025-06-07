# simple-shellbat
a taiHEN plugin that adds battery percentage to the statusbar

![Screenshot](https://github.com/user-attachments/assets/3d7d2ca3-67f9-4a4d-aad5-7861ceaf2c2e)

## why
**It's generally easier to tell the user the console will shut off at 1% instead of 11-13%**

PlayStation Vita doesn't allow the battery to fully drain so usually the console goes into deep sleep at around 12-13%. This plugin is meant to recalculate the percentage based on this fact thanks to [leonardputra's fork for IRS-1001 models]([https://github.com/leonardputra/vita-shellbat-irs-1001)

### installation

Add this plugin under `*main` section in `ur0:tai/config.txt` / `ux0:tai/config.txt`:

```c
*main
ur0:tai/shellbat.suprx
```
