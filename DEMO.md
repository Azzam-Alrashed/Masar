# Masar launch simulator: demo script

Open `index.html` by double-clicking it. It works offline, with no internet needed. Seed 2026 gives the same numbers every time. The numbers below are for that seed.

## Two minutes, five beats

**1. Turn on "Remove all uncertainty".** The hero reads 100% and every run lands on Sun 27 Dec.
> "This is the plan on slide 10 with nothing going wrong. It lands exactly on the day. That's what 'no buffer' means: it only holds if everything goes to plan."

**2. Turn uncertainty back on.** You're at option A, as briefed: **2%**, typically Thu 14 Jan.
> "With realistic uncertainty, the brief as written almost never makes it. That's why I said option A misses on slide 8. The drivers panel shows why: the full AI assistant doesn't fit."

**3. Click scope B (9%), then point at the drivers.** Bandar's four items are at the top, worth 3.1 days together but only 2.2 days fixed one at a time.
> "Four dependencies with one person isn't four risks. It's a queue. While one item waits on him, so do the rest."

Turn on **"Treat Bandar as four people"**: 9% goes to **16%**.
> "This is what the risk register would tell you if you treated them separately. The queue costs seven points."

Turn it back off.

**4. Apply the mitigations one at a time, following the badges.** Each badge shows what that lever is worth before you click it.
- **QA full-time for testing:** about +10.
- **Named backup, weekly slot:** +7 and +6.
- **Content templates, Saud workshop:** +5 and +4.
- **Keep the designer to week 10:** ±0.
  > "The obvious fix, more design time, buys nothing. The risk isn't design capacity."

With all of them on, you're at **60%**. Switch to **C** for **69%**.

**5. Kick-off question: switch the payment owner to TSC IT.** Option B with no mitigations drops from 9% to **3%**.
> "That's why 'who owns the payment gateway request?' is on my kick-off list. If it's Bandar, it's five of seven, and the queue gets longer."

**Close:**
> "Every input here is an assumption. In week 1 I'd replace them with real data: the call logs, Bandar's actual availability, the CRM's real state. Then this becomes the steering committee's risk view."

## If they ask
- **"Where do the numbers come from?"** Open *Assumptions* at the bottom. Every estimate is a three-point range and every one is visible. "It's illustrative calibration, the same as the slide 7 chart. The method is the point."
- **"Is it rigged?"** Click *Reseed*. The numbers move by a point or two, and the conclusions don't.
- **"Why Monte Carlo?"** "A plan with nine paths merging into testing has merge bias. Each path can be likely on time and the whole still be unlikely. You can't see that on a Gantt chart."
- **"Play one run"** (tab on the chart) animates a single run and names the chain of cause that made it late.
- **The slip cost** uses SAR 92k a week, which is contract value at 5.6 FTE, not margin. That matches the backup slide.
