# Antistar VCC Listing

The VCC listing for Antistar's Unity tools:

- **Antistar.Tooltip**, the support and FAQ window that comes with our packs.
- **Antistar.Exporter**, the team's pack exporter. It brings Antistar.Tooltip with it.

Add it to VCC from the [listing page](https://theamazingcobra.github.io/Antistar-VCC-Listing/), or under Settings > Packages > Add Repository:

```
https://theamazingcobra.github.io/Antistar-VCC-Listing/index.json
```

## How it updates

The listing collects every release of the two package repos. It rebuilds when `source.json` changes, when you run **Build Repo Listing** by hand, and on its own every hour, so a new release shows up in VCC within the hour.

## Setup, once

Settings > Pages > Build and deployment, set **Source** to **GitHub Actions**. Then run **Build Repo Listing** from the Actions tab.
