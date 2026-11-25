# chargeportugal.com

Publishes **https://chargeportugal.com**, the Portugal-wide version of [madeirachargers.com](https://madeirachargers.com).

All code and data live in [PartyTrix/madeira-chargers](https://github.com/PartyTrix/madeira-chargers) (see `sites/portugal/` there). This repo only exists because GitHub Pages serves one custom domain per repo: its workflow checks out madeira-chargers every 6 hours, runs `node scripts/build-site.mjs portugal _site` and deploys the result here. Run it by hand from **Actions → Build & deploy chargeportugal.com → Run workflow** to publish a change straight away.

Settings → Pages: Source "GitHub Actions", custom domain `chargeportugal.com`.

Licence: PolyForm Noncommercial 1.0.0, as in the main repo.
