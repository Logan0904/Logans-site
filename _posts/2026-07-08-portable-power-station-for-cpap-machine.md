---
layout: post
title: "Portable Power Station for a CPAP Machine: Sizing It So You Sleep Through an Outage"
date: 2026-07-08
categories: [buying-guides, use-cases]
---

*Affiliate disclosure: this post contains Amazon affiliate links. We may earn a commission on qualifying purchases at no extra cost to you.*

If you use a CPAP or BiPAP machine, a power outage isn't just an inconvenience. It's a night without treatment, and that matters if you have sleep apnea for medical reasons, not just comfort. Most general "backup power" guides don't size for this correctly, because a CPAP's power profile looks nothing like a fridge's or a laptop's. Here's how to size a portable power station so it actually gets you through the night, and what to check before you buy.

## Why CPAP machines need their own sizing math

On its own, a CPAP draws surprisingly little: most units pull somewhere in the 30-60 watt range at typical pressure settings, with no heated accessories running. That's trivial next to a mini fridge or space heater, and if that were the whole story, almost any power station could run one all night without trying.

The complication is the heated humidifier and heated tubing that ship with most modern machines. Run the humidifier at a mid-to-high setting and you can add 50-70% on top of the base draw, with heated tubing adding more on top of that. A machine pulling 45W with the humidifier off might pull 90-120W with it on. That's the number that actually determines your runtime, and it's also the number most people get wrong, because they check the machine's minimum draw instead of how they actually run it at night.

## The math: watt-hours, not "battery size"

Power stations are rated in watt-hours (Wh). Divide your CPAP's actual wattage into that number and you get hours of runtime. The formula:

(Battery capacity in Wh, times roughly 0.85 for inverter losses) divided by your CPAP's actual wattage equals hours of runtime.

That 0.85 factor is easy to forget, but it matters: no power station delivers 100% of its rated capacity as usable output once inverter inefficiency is accounted for, and skipping this step is the most common way people overestimate how long a unit will last.

A few examples make it concrete. A 45W CPAP with no humidifier, on a 500-600Wh power station, gets roughly 9-11 hours, enough for a full night with margin. The same machine with a mid-setting humidifier (call it 90W) on that same unit drops to around 4.5-5.5 hours, probably short of a full night. Step up to a 1,000Wh-class unit with the humidifier running, and you're back to 9-10 hours, comfortably covering a night even with heat on.

If you run a heated humidifier every night and want real margin, size for the 1,000Wh tier rather than 500-600Wh. If you're fine running the humidifier low or skipping the heat during an outage (passive humidification still works, just without warmth), the smaller tier is usually enough.

## What matters more than capacity alone

Pure sine wave output isn't optional for medical equipment. It produces power that closely matches the clean waveform a CPAP's internal electronics expect. Modified sine wave units, common in cheaper power stations and older jump-starter-style packs, can make CPAP motors run hotter, less efficiently, or in some cases throw error codes. The listing should say "pure sine wave" outright. If it doesn't say it, don't assume it.

A UPS or pass-through function matters if you want zero interruption. Standard power stations take a brief moment to switch from idle to delivering power when the wall drops out, which doesn't matter for a fridge but might matter if you don't want your CPAP to stop mid-breath during the handoff. Some newer units advertise sub-20-millisecond UPS switching aimed specifically at medical device use. Most CPAPs tolerate a brief handoff fine since they're not ventilators, but check this if it matters to you.

Continuous output rating barely matters here, honestly. CPAP machines don't have the startup spike that compressor-based appliances like fridges do, so peak wattage isn't the bottleneck. Any power station rated for even 300W continuous can run a CPAP without issue; capacity and waveform quality are what actually decide things.

## A note on medical necessity and redundancy

If a CPAP is medically necessary for you, treat the power station as backup infrastructure, not a gadget. A few habits are worth building regardless of which unit you buy: keep it charged at all times rather than only when a storm's forecast, know your machine's exact wattage (check the label or the power brick rather than guessing), and think about whether a second, smaller backup-to-the-backup makes sense if outages in your area tend to stretch across multiple nights. This post covers the electrical math, not medical guidance, so if you have questions specific to your prescribed settings, that's a conversation for your durable medical equipment supplier or physician.

## How this fits the bigger picture

The watt-hour math here is the same math that applies to backing up any device. Our [portable power station buying guide](/Logans-site/2026/07/08/portable-power-station-buying-guide-for-renters/) covers how capacity tiers compare across use cases, and our breakdown of [running a mini fridge on battery power](/Logans-site/2026/07/08/how-long-portable-power-station-run-mini-fridge/) is a good worked example if you're trying to cover more than one appliance on the same unit.

If you're covering a CPAP plus other essentials, router, phone charging, a lamp, on the same outage, add up the watt-hour needs for each rather than sizing around the CPAP alone. It's a common oversight, and it's the reason people end up short on capacity when it actually matters.

## Why battery chemistry matters for this specific use

Most current power stations use lithium iron phosphate (LiFePO4) cells rather than older lithium-ion nickel-cobalt chemistries. That distinction matters more for CPAP use than it does for occasional camping trips, since a CPAP power station sits plugged in and cycling far more often than one bought purely for emergencies. LiFePO4 cells are rated for a lot more charge cycles before capacity fades, often several thousand cycles to 80% capacity versus a few hundred to low thousand for older chemistries, and they run cooler too. If this unit is going to be nightly-ready rather than sitting untouched in a closet for a year, look specifically for listings that say LiFePO4 (sometimes written LFP).

## Finding your CPAP's actual wattage

Don't guess. It's usually printed right on the machine's data label or on the power brick, either directly in watts or as volts times amps (multiply the two together). If it's not there, the user manual or manufacturer's support site will list it, often broken out separately for the machine alone versus with the humidifier running. Some manufacturers list different wattage figures by pressure setting too. If your prescription is on the higher end, size around the higher figure.

## Charging habits for medical backup use

A dead power station doesn't help anyone when the outage hits, so charging habits matter almost as much as which unit you buy. Keep it at a comfortable charge buffer rather than sitting at 100% indefinitely (check your unit's guidance on storage charge level, since many manufacturers recommend against leaving lithium batteries fully charged when not in imminent use). Recharge fully as soon as you can after any use instead of leaving it partially depleted. If outages in your area run long or frequent, a unit with solar input gives you a secondary way to recharge if a single outage stretches past overnight, though for most single-night scenarios it's a nice-to-have rather than something you'll actually rely on.

## A few common questions

Can a phone-charger-style power bank run a CPAP instead? No. Standard USB power banks don't provide AC output or the wattage a CPAP needs. You need a unit with an AC outlet and a pure sine wave inverter, which is the actual line between a power station and a power bank.

Will battery power damage the machine? Not if the station puts out pure sine wave at a wattage the machine's rated for. The real risk is modified sine wave units specifically, not battery power in general.

How many nights should I plan for? Depends entirely on how long outages actually run where you live. A single 500-600Wh unit reasonably covers one night. If outages in your area tend to run multiple days, either size up or plan a way to recharge between nights (solar, a car inverter, or a generator if you have one).

## Where to look

<div>{% raw %}<!-- affiliate search links, tag to be added on Amazon Associates approval --> {% endraw %}</div>

- [Browse pure sine wave portable power stations in the 500-600Wh range on Amazon](https://www.amazon.com/s?k=pure+sine+wave+portable+power+station+500wh&tag=backuppowergu-20)
- [Browse 1000Wh-class portable power stations for CPAP and medical backup on Amazon](https://www.amazon.com/s?k=portable+power+station+1000wh+cpap&tag=backuppowergu-20)
- [Browse CPAP-specific DC battery packs on Amazon](https://www.amazon.com/s?k=cpap+battery+backup&tag=backuppowergu-20)

Verify your specific CPAP's wattage before buying (the label or power brick will have it, in watts or volts times amps), and confirm the listing states pure sine wave output outright.
