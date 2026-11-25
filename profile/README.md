# Runsten

**Every trip of your Volvo, carved in stone.**

Runsten reads your Volvo electric car through the Volvo API and keeps its trips, charges and costs, as a history and as statistics. It is in development, and will be available soon.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://runsten.app/screens/stats-dark-desktop.png">
  <img alt="The statistics of a month: distance, consumption, energy charged and cost." src="https://runsten.app/screens/stats-light-desktop.png">
</picture>

## What it keeps

- **The car, now**: its charge, range, odometer and position, each with when it was last read.
- **Trips**: distance, consumption and times. A trip made while nothing could be read is still found, from the odometer, and marked as reconstructed.
- **Charges and their cost**: the energy, the place and the cost of each charge, from your tariffs, off-peak hours included, or from the receipt you enter.
- **The battery**: an estimate of its remaining capacity, charge after charge, against the data sheet of your model.

## Honest by design

Runsten shows what it read, and when. It does not fill the gaps with guesses.

- **Times are ranges**: a trip starts somewhere between two readings, and the page says so.
- **Unknown is not zero**: a value the car did not give is shown as unknown, and left out of the totals.
- **Every reading kept**: when Runsten improves, the whole history is worked out again.
- **No map service**: positions are coordinates, with a link to OpenStreetMap you follow if you want.

In English, French and Swedish, on a phone and a desktop, light or dark, usable with the keyboard alone or a screen reader.

## Two ways to run it

- **Self-hosted**, on your own machine.
- **Hosted**: we run it for you.

## Support Runsten

Runsten is free software. If it is useful to you, you can [buy us a coffee on Ko-fi](https://ko-fi.com/runstenapp): it helps keep the self-hosted version free and pays for the work on new makes.

→ [runsten.app](https://runsten.app) · Questions: [support@runsten.app](mailto:support@runsten.app)
