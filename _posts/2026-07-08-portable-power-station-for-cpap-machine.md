---
layout: post
title: "Portable Power Station for a CPAP Machine: Sizing It So You Actually Sleep Through an Outage"
date: 2026-07-08
categories: [buying-guides, use-cases]
---

*Affiliate disclosure: this post contains Amazon affiliate links. We may earn a commission on qualifying purchases at no extra cost to you.*

If you use a CPAP or BiPAP machine, a power outage isn't just an inconvenience — it's a night without treatment, which matters if you have sleep apnea for medical reasons and not just comfort. Most general "backup power" guides don't size for this use case correctly, because CPAP machines have a power profile that's different from a fridge or a laptop. Here's how to size a portable power station so it actually gets you through the night, and what specs to check before you buy.

## Why CPAP machines need their own sizing math

A CPAP machine on its own draws relatively little power — most units pull somewhere in the 30-60 watt range at the pressure settings most people use, without any heated accessories running. That sounds trivial next to a mini fridge or a space heater, and if that were the whole story, almost any power station could run one all night without breaking a sweat.

The complication is the heated humidifier and heated tubing that ship with most modern machines. Running the humidifier at a mid-to-high setting can add 50-70% on top of the base draw, and heated tubing adds more still. A machine that draws 45W with the humidifier off might draw 90-120W with it on. That's the number that actually determines your runtime, and it's also the number most buyers guess wrong, because they check the machine's minimum draw instead of how they actually use it.

## The math: watt-hours, not just "battery size"

Portable power stations are rated in watt-hours (Wh), which is the number you divide your CPAP's actual wattage into to get hours of runtime. The formula is straightforward:

**(Battery capacity in Wh x ~0.85 for inverter/conversion losses) / your CPAP's actual wattage = hours of runtime**

The 0.85 factor matters — no power station delivers 100% of its rated capacity as usable output once you account for inverter inefficiency, and ignoring it is the most common way people overestimate runtime.

A few worked examples:

- **A 45W CPAP with no humidifier**, on a ~500-600Wh power station, gets roughly 9-11 hours — enough for one full night with some margin.
- **The same machine with a mid-setting humidifier** (call it 90W), on that same 500-600Wh unit, drops to around 4.5-5.5 hours — probably not a full night.
- **Step up to a 1,000Wh-class unit** with the humidifier running, and you're back to roughly 9-10 hours, comfortably covering a full night even with heated settings on.

If you routinely run a heated humidifier and want a true one-night-with-margin buffer, size for the 1,000Wh tier rather than the 500-600Wh tier. If you're comfortable running the humidifier at a lower setting or skipping it during an outage (passive humidification from the water chamber still works, just without the heat), the smaller and lighter 500-600Wh tier is usually enough.

## Three specs that matter more than capacity alone

**Pure sine wave output.** This isn't optional for medical equipment. A pure sine wave inverter produces power that closely matches the clean waveform your CPAP's internal electronics expect. Modified sine wave units (common in cheaper power stations and older jump-starter-style battery packs) can cause CPAP motors to run hotter, less efficiently, or in some cases trigger error codes. Check the listing explicitly states "pure sine wave" before buying — it should be stated outright, not implied.

**A UPS or pass-through function, if you want zero interruption.** Standard power stations take a brief moment to switch from being idle to delivering power when the wall drops out, which is irrelevant for a fridge but could matter if you want your CPAP to never fully stop mid-breath during a transition. Some newer units advertise sub-20-millisecond UPS switching specifically marketed at medical device use — worth checking if this level of continuity matters to you, though most CPAP machines tolerate a brief handoff without issue since they're not the same as ventilators.

**Continuous output rating, even though it's overkill.** CPAP machines don't have the surge/startup spike that compressor-based appliances like fridges do, so you don't need to worry about peak wattage the way you would for other devices. Any power station rated for even 300W continuous output can run a CPAP; this spec simply isn't the bottleneck for this use case the way capacity and waveform quality are.

## A note on medical necessity and redundancy

If a CPAP is medically necessary for you, treat the power station as backup infrastructure, not a nice-to-have gadget — which means a few practices are worth adopting regardless of which unit you buy: keep it charged at all times rather than only charging it when a storm is forecast, know your machine's exact wattage draw (check the label on the machine or its power brick rather than guessing), and consider whether a second, smaller unit as a backup-to-the-backup makes sense if outages in your area tend to run multiple nights. Talk to your durable medical equipment supplier or physician if you have questions about backup power specific to your prescribed settings — this post covers the electrical math, not medical guidance.

## How this fits into the broader capacity picture

The sizing logic here follows the same watt-hour math that applies to any device you're trying to back up — see our [portable power station buying guide](/Logans-site/2026/07/08/portable-power-station-buying-guide-for-renters/) for how capacity tiers compare across different use cases, and our breakdown of [running a mini fridge on battery power](/Logans-site/2026/07/08/how-long-portable-power-station-run-mini-fridge/) if you're trying to cover multiple appliances on one unit rather than just a CPAP.

If you're covering both a CPAP and other essentials (router, phone charging, a lamp) on the same outage, add up the watt-hour requirements for each rather than sizing for the CPAP alone — it's a common oversight that leaves people short on total capacity.

## Battery chemistry: why it matters for overnight, unattended use

Most current-generation portable power stations use lithium iron phosphate (LiFePO4) cells rather than the older lithium-ion nickel-cobalt chemistries. For CPAP use specifically, this distinction matters more than it does for occasional camping use, because a CPAP power station sits plugged in and cycling far more often than a station bought purely for emergencies. LiFePO4 cells are rated for substantially more charge cycles before capacity degrades — often several thousand cycles to 80% capacity, versus a few hundred to low thousand for older chemistries — and they run cooler and are considered more thermally stable. If you plan to use the unit as a nightly-ready backup rather than something that sits in a closet untouched for a year, prioritize listings that specify LiFePO4 (sometimes written LFP) explicitly.

## How to find your CPAP's actual wattage

Don't guess — check the actual number, since it's usually easy to find. Most CPAP machines list their power draw or input specifications directly on the machine's data label, or on the power supply "brick" that comes with it, printed as either watts directly or as volts times amps (multiply the two to get watts). If you can't find it there, the machine's user manual or the manufacturer's support site will list power consumption specifications, often broken out separately for the machine alone versus the machine with humidifier running. Some manufacturers also publish separate wattage figures for different pressure settings, since higher prescribed pressures draw slightly more power — if your prescription is on the higher end, use the higher figure when sizing.

## Charging considerations for medical backup use

A power station that's dead when the outage hits doesn't help anyone, so charging habits matter as much as the unit you buy. A few practices worth adopting: keep the unit charged to a comfortable buffer (many manufacturers recommend not leaving lithium batteries at 100% for extended periods when not in imminent use, so check your specific unit's guidance on storage charge level), recharge it fully as soon as possible after any use rather than letting it sit partially depleted, and if you live somewhere with frequent outages, consider a unit with solar charging input as a secondary recharge path if an outage runs long enough to drain a full charge overnight and into the next day. Solar recharging is a nice-to-have for this use case rather than a requirement, since most single-night CPAP backup scenarios resolve well before solar becomes relevant.

## Frequently asked questions

**Can a power bank (phone-charger-style) run a CPAP instead of a power station?** No — standard USB power banks don't provide AC output or the wattage a CPAP needs. You need a unit with an AC outlet and pure sine wave inverter, which is what separates a power station from a phone power bank.

**Will running my CPAP off battery power damage the machine?** Not if the power station provides pure sine wave output at a wattage the machine is rated for. The risk is specifically with modified sine wave units, not battery power in general.

**How many nights of backup should I plan for?** That depends entirely on how often and how long outages last where you live. A single 500-600Wh unit reasonably covers one night; if outages in your area commonly run multiple days, either size up to a larger unit or plan on a way to recharge (solar, a car inverter, or a generator if you own one) between nights.

## Where to look

<div>{% raw %}<!-- affiliate search links, tag to be added on Amazon Associates approval --> {% endraw %}</div>

- [Browse pure sine wave portable power stations in the 500-600Wh range on Amazon](https://www.amazon.com/s?k=pure+sine+wave+portable+power+station+500wh&tag=AMZTAGPLACEHOLDER)
- [Browse 1000Wh-class portable power stations for CPAP and medical backup on Amazon](https://www.amazon.com/s?k=portable+power+station+1000wh+cpap&tag=AMZTAGPLACEHOLDER)
- [Browse CPAP-specific DC battery packs on Amazon](https://www.amazon.com/s?k=cpap+battery+backup&tag=AMZTAGPLACEHOLDER)

As always, verify your specific CPAP model's wattage (check the label on the power supply brick, usually listed in watts or as volts times amps) before buying, and confirm any listing explicitly states pure sine wave output.
