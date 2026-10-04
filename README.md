# Masar
Business case study simulation, for a customer self serve portal project.

**Live:** https://azzam-alrashed.github.io/Masar/

A Monte Carlo model of the 16-week Masar delivery plan. It runs the plan 10,000 times and shows:
- the chance of launching on the committed date, Sun 27 Dec 2026
- what drives the risk
- what each mitigation is worth

## What it does
- **Calendar:** exact Saudi working days (Sunday to Thursday, National Day excluded). That gives 79 working days from kick-off to launch.
- **Plan:** the delivery plan as an activity network, with three-point estimates for each activity.
- **Client dependencies:** each one has an owner. The IT manager's four items are modelled as one queue, not four independent risks.
- **Levers:** scope options A, B and C, plus mitigations. Each lever shows its effect before you switch it on.
- **What drives the risk:** the same 10,000 runs, re-run with one risk source held to plan each time.
- **Play one run:** an animated timeline of a single run, with the chain of causes behind it.

## Use it
Open `index.html` in a browser. It's a single file with no dependencies and works offline. `DEMO.md` is a two-minute walkthrough.

## Notes
The client, people and project are fictional, taken from a case study brief. Every number in the model is an illustrative assumption, listed in full under *Assumptions* on the page.
