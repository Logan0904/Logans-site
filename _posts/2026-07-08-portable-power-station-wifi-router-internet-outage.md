---
layout: post
title: "How to Keep Your WiFi Router and Internet Running During a Power Outage"
date: 2026-07-08
categories: [buying-guides, use-cases]
---

*Affiliate disclosure: this post contains Amazon affiliate links. We may earn a commission on qualifying purchases at no extra cost to you.*

A power outage doesn't just kill your lights — it kills your internet, and for a lot of renters that's the bigger problem. Working from home, checking on elderly family members, keeping a security camera or smart lock online, or just not losing your place in a video call mid-storm all depend on the router and modem staying powered. The good news: your networking gear draws almost nothing compared to a fridge or a space heater, which means a small amount of backup power goes a very long way. Here's how to actually keep it running, and where the plan can still fail even if your equipment stays powered.

## How much power a router and modem actually use

This is the easiest device category on this site to back up, because the numbers are small. A typical home router draws somewhere in the 5-15 watt range, and a cable or fiber modem draws roughly 5-15 watts on top of that. Combined, most two-piece router-and-modem setups pull somewhere around 10-30 watts continuously — a tiny fraction of what a mini fridge or space heater needs.

If you're running a mesh WiFi system with multiple satellite nodes, each additional node typically adds another 5-10 watts, so a three-piece mesh setup can land closer to 25-40 watts total. Combo modem/router gateway units (common with cable ISPs) usually draw somewhere in the middle of these ranges as a single device, often 10-20 watts.

The exact number for your equipment is usually printed on the power adapter itself, listed as either watts directly or as volts x amps (multiply the two to get watts) — check there before doing the math below rather than assuming a "typical" figure.

## The math: how long a battery actually lasts

Once you know your equipment's wattage, the runtime formula is the same one that applies to any device on a portable power station:

**(Battery capacity in Wh x ~0.85 for inverter losses) / your equipment's combined wattage = hours of runtime**

Applied to networking gear specifically, because the wattage is so low, even modest capacity stations deliver outage coverage measured in days, not hours:

- **A 15W router-and-modem setup on a 300Wh power station**: roughly 15-17 hours — well over a full day.
- **The same setup on a 600Wh station**: roughly 30-34 hours — more than a full day and night.
- **A heavier 30W setup (mesh system, combo gateway plus a satellite node) on a 600Wh station**: roughly 15-17 hours.
- **That same 30W mesh setup on a 1,000Wh-class station**: roughly 25-28 hours.

In practice, this means you rarely need to dedicate a large station purely to networking gear — even a small unit bought mainly for phone charging and lighting will comfortably carry a router and modem for a full multi-day outage, with plenty of capacity left for other small devices.

## The part backup power can't fix: your ISP's side of the connection

This is the caveat that most "keep your WiFi on" guides skip, and it matters: powering your own router and modem only guarantees a signal reaches your equipment if your internet provider's upstream infrastructure also has power. Two common failure points:

**Cable and fiber network nodes.** Your neighborhood's cable amplifier or fiber distribution node (the equipment between your home and your ISP's central office) typically runs on its own backup battery, but those batteries are usually sized for a few hours, not days. If a fiber ONT (the box that converts the fiber signal at your home) loses power from the wall, it also stops working regardless of whether your router has battery backup — some ISPs supply a small UPS specifically for the ONT for this reason, and it's worth checking if yours does.

**Extended outages beyond the node's own backup.** In a short outage, your ISP's local infrastructure often has enough of its own reserve to keep working even while your home is dark. In an extended outage lasting many hours or days, that upstream infrastructure may go down even if your home equipment stays perfectly powered.

The practical takeaway: backup power for your router and modem is necessary but not sufficient for guaranteed internet during a long outage. If truly staying connected matters (medical monitoring, remote work continuity, elderly family check-ins), a cellular hotspot or a phone's mobile data as a fallback is worth having in addition to, not instead of, battery backup for your home equipment — cell towers generally have more robust generator backup than neighborhood cable/fiber nodes, though they aren't immune to extended outages either.

## Mini-UPS vs. portable power station: which one you actually need

For networking gear specifically, you have two realistic options, and the right one depends on how long your outages typically run:

**A small dedicated UPS (uninterruptible power supply)**, the kind sold for home networking specifically, is a reasonable "set it and forget it" choice if your outages are usually short — power blips, brief utility work, storms that resolve in an hour or two. These are compact, inexpensive, and purpose-built to sit behind a router permanently, but their battery capacity is small, and most only bridge a few hours before running out.

**A portable power station** is the better choice if outages in your area regularly run longer than a few hours, or if you want one unit that covers your router and modem alongside other essentials — phone charging, a lamp, a fan — rather than a device dedicated to networking alone. See our [portable power station buying guide](/Logans-site/2026/07/08/portable-power-station-buying-guide-for-renters/) for how capacity tiers compare across different use cases if you're deciding what size to buy for combined use.

One advantage worth calling out for power stations over dedicated network UPS units: most portable power stations support pass-through charging, meaning you can leave your router and modem plugged directly into the station permanently, with the station itself plugged into the wall. When the power goes out, there's no manual swap required — the station's internal battery takes over automatically the moment wall power drops, the same way a UPS does.

## What else is worth plugging in alongside your router

If you're already running a power station for your router and modem, a few other small, low-wattage devices are worth adding to the same circuit since the additional draw is minimal:

- A WiFi mesh satellite or extender, if part of your setup (5-10W each)
- A VoIP adapter, if your home phone service runs over the internet rather than a traditional landline (5-10W)
- A smart speaker or hub, if it's your primary way of checking weather updates or news during an outage (2-5W)
- Your phone charger — obvious, but worth explicitly accounting for in your total wattage rather than assuming it's negligible

Each of these adds only a few watts, but tally them up rather than assuming they're free — a setup that looked like a comfortable 15W router-only load can climb to 35-40W once you've added a satellite node, a VoIP adapter, and a phone charging cable, which meaningfully changes your runtime math from the examples above.

## Specs that matter for this specific use case

Networking gear is one of the more forgiving device categories to back up, so most of the strict requirements that apply to sensitive equipment (like the CPAP sizing guide on this site) don't apply here in the same way:

**Pass-through / UPS-style charging.** This is the one spec that genuinely matters — confirm the station explicitly supports charging while simultaneously providing output (sometimes called "pass-through charging" or "UPS mode"), so your equipment can stay permanently connected without a manual swap during an outage.

**Continuous wattage rating.** Any power station rated for even 100-150W continuous output comfortably covers networking gear — this spec is not the bottleneck for this use case.

**Sine wave output is a lower priority here** than it is for CPAP machines or other sensitive electronics — most router and modem power supplies are simple AC-to-DC converters that tolerate modified sine wave input without issue, though pure sine wave units are still a safe default if you're already buying a station for that reason.

## How this fits with the rest of your outage plan

If you're sizing a single power station to cover your router, modem, and a handful of other essentials during an outage, add up the total watt-hour requirement across every device rather than sizing for networking gear alone. See our [breakdown of running a mini fridge on battery power](/Logans-site/2026/07/08/how-long-portable-power-station-run-mini-fridge/) for a worked example of exactly this kind of multi-device planning, since the fridge is usually the largest single load in a renter's outage plan and everything else layers on top of it.

## Frequently asked questions

**Will my internet actually work if my router has power but my neighborhood's cable/fiber node doesn't?** No — your equipment needs a live signal reaching it. Powering your router and modem is necessary but doesn't guarantee upstream connectivity during an extended outage; see the ISP infrastructure section above.

**Do I need a separate battery for my router if I already have a power station for my fridge or CPAP?** Not necessarily — since networking gear draws so little, most stations sized for a fridge or CPAP have plenty of spare capacity left over to also run a router and modem for the same outage window. Just add the wattage to your total when sizing.

**Is a cellular hotspot a replacement for router battery backup?** It's a good supplement, not a replacement — a hotspot depends on cell tower connectivity and your phone's own battery, and typically costs more per gigabyte than home internet. Most people are best served by battery-backing their existing router/modem first, with a hotspot as a fallback if the outage also affects your ISP's upstream infrastructure.

## Where to look

<div>{% raw %}<!-- affiliate search links, tag to be added on Amazon Associates approval --> {% endraw %}</div>

- [Browse compact portable power stations with pass-through/UPS charging on Amazon](https://www.amazon.com/s?k=portable+power+station+pass+through+charging+ups&tag=AMZTAGPLACEHOLDER)
- [Browse dedicated mini UPS units for routers and modems on Amazon](https://www.amazon.com/s?k=mini+ups+battery+backup+router+modem&tag=AMZTAGPLACEHOLDER)
- [Browse 300Wh-class portable power stations on Amazon](https://www.amazon.com/s?k=portable+power+station+300wh&tag=AMZTAGPLACEHOLDER)

As always, check your specific router and modem's wattage on the power adapter label before buying, and confirm any power station you're considering explicitly supports pass-through or UPS-style charging if you plan to leave your equipment connected permanently.
