# Zanti Heat demo

An interactive prototype of Zanti Heat, a worker-first heat early-warning and decision-support system for outdoor and industrial workers. Built by 6.0 Industries for the Future Health Digital Innovation Challenge (Population Health: Climate-Resilient Worker Health).

**Live demo:** https://thatonthodi.github.io/Zanti-heat-demo/

## What it shows

Set the site conditions and crew context, and the demo returns:

- a graded alert (Green, Yellow, Orange, Red, Emergency) with the reason and one safe action
- the worker's message in English, isiZulu, Sesotho or Setswana
- a supervisor view with a work-rest plan and no individual health data

It also simulates:

- Network down: a local gateway runs the rules offline, without the forecast.
- Sensor failure: the safety margin widens.
- Worker consent: an opt-in personal advisory that can only make advice more cautious, and stays on the worker's phone.
- Red-flag symptoms: a report that triggers the Emergency tier.

## How the risk is estimated

The effective WBGT (wet-bulb globe temperature) is compared with a crew limit that depends on task intensity and acclimatisation. Heavy or impermeable PPE and sensor or network faults add a safety margin. The alert tier depends on how far the effective WBGT is above or below the limit, and on the 2-hour forecast when it is available.

## Important limits

- All data is simulated. No field testing or sensor integration has been done.
- The thresholds are illustrative and will be calibrated with an occupational-health physician.
- The translations are drafts and need native-speaker review before any field use.
- This is a safety-advisory prototype, not a diagnostic or medical device.

## Run it locally

It is a single HTML file with no dependencies. Open index.html in a browser.

## Licence

All rights reserved, 6.0 Industries (Pty) Ltd.
