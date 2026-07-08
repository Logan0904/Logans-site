---
layout: post
title: "How to Keep Your WiFi Router and Internet Running During a Power Outage"
date: 2026-07-08
categories: [buying-guides, use-cases]
---

*Affiliate disclosure: this post contains Amazon affiliate links. We may earn a commission on qualifying purchases at no extra cost to you.*

A power outage doesn't just kill your lights. It kills your internet, and for a lot of renters that's actually the bigger problem. Working from home, checking on elderly family, keeping a security camera or smart lock online, or just not losing your spot in a video call mid-storm all come down to the router and modem staying powered. The good news is that networking gear draws almost nothing compared to a fridge or space heater, so a small amount of backup power goes a long way. Here's how to keep it running, and where the plan can still fall apart even if your own equipment stays on.

## How much power a router and modem use

This is the easiest device category on this site to back up, because the numbers are small. A typical home router draws somewhere in the 5-15 watt range, and a cable or fiber modem draws roughly 5-15 watts on top of that. Combined, most two-piece router-and-modem setups pull around 10-30 watts continuously, a tiny fraction of what a mini fridge or space heater needs.

Running a mesh WiFi system with satellite nodes adds roughly 5-10 watts per node, so a three-piece mesh setup can land closer to 25-40 watts total. Combo modem/router gateway units, common with cable ISPs, usually draw somewhere in the middle of these ranges as a single device, often 10-20 watts.

The exact number for your gear is almost always printed right on the power adapter, either in watts directly or as volts times amps (multiply the two together). Check there before doing any math instead of assuming a "typical" figure.

## The math: how long a battery actually lasts

Once you know your equipment's wattage, it's the same runtime formula that applies to any device on a portable power station:

(Battery capacity in Wh, times roughly 0.85 for inverter losses) divided by your equipment's combined wattage equals hours of runtime.

Because networking gear draws so little, even modest-capacity stations deliver coverage measured in days, not hours. A 15W router-and-modem setup on a 300Wh station gets roughly 15-17 hours, well over a full day. The same setup on a 600Wh station gets 30-34 hours, more than a full day and night. Bump up to a heavier 30W setup (mesh system, gateway plus a satellite node) and a 600Wh station still gets you 15-17 hours, with a 1,000Wh-class unit stretching that to 25-28 hours.

In practice, this means you rarely need a station dedicated purely to networking gear. Even a small unit bought mainly for phone charging and lighting will comfortably carry a router and modem through a multi-day outage, with plenty of capacity left for other small devices.

## The part backup power can't fix: your ISP's side of the connection

Most "keep your WiFi on" guides skip this, and it matters: powering your own router and modem only gets you a signal if your internet provider's upstream infrastructure also has power. Two failure points come up often.

Cable and fiber network nodes near your home, the equipment between your house and your ISP's central office, typically run on their own backup battery, but those batteries are usually sized for a few hours, not days. If a fiber ONT (the box that converts the fiber signal at your home) loses wall power, it stops working regardless of whether your router has battery backup. Some ISPs supply a small UPS specifically for the ONT for this reason, worth checking if yours does.

In a short outage, your ISP's local infrastructure often has enough reserve of its own to keep working while your home is dark. In an extended outage running many hours or days, that upstream infrastructure can go down even if your home equipment stays perfectly powered the whole time.

The practical takeaway: backup power for your router and modem is necessary but not sufficient for guaranteed internet during a long outage. If staying connected genuinely matters, medical monitoring, remote work, checking on elderly family, a cellular hotspot or your phone's mobile data is worth having as a fallback in addition to battery backup, not instead of it. Cell towers generally have more robust generator backup than neighborhood cable or fiber nodes, though they're not immune to extended outages either.

## Mini UPS or portable power station: which one you need

For networking gear specifically, there are two realistic options, and which one makes sense depends on how long your outages typically run.

A small dedicated UPS, the kind sold specifically for home networking, is a reasonable set-it-and-forget-it choice if your outages are usually short: power blips, brief utility work, storms that clear up in an hour or two. These are compact, inexpensive, and built to sit behind a router permanently, but battery capacity is small, and most only bridge a few hours before running out.

A portable power station makes more sense if outages in your area regularly run longer than a few hours, or if you want one unit covering your router and modem alongside other essentials, phone charging, a lamp, a fan, rather than a device dedicated to networking alone. Our [portable power station buying guide](/Logans-site/2026/07/08/portable-power-station-buying-guide-for-renters/) covers how capacity tiers compare if you're deciding what size makes sense for combined use.

One real advantage power stations have over dedicated network UPS units: most support pass-through charging, meaning you can leave your router and modem plugged directly into the station permanently, with the station itself plugged into the wall. When power drops, there's no manual swap. The station's battery takes over automatically, the same way a UPS does.

## What else is worth adding to the same circuit

If you're already running a station for your router and modem, a few other low-wattage devices are worth adding since the extra draw barely moves the needle: a WiFi mesh satellite or extender if that's part of your setup (5-10W each), a VoIP adapter if your home phone runs over the internet rather than a landline (5-10W), a smart speaker or hub if it's how you check weather or news during an outage (2-5W), and your phone charger, obvious, but worth actually counting instead of assuming it's negligible.

Each of these only adds a few watts, but they add up. A setup that looked like a comfortable 15W router-only load can climb to 35-40W once you've tacked on a satellite node, a VoIP adapter, and a phone charging cable, and that changes the runtime math from the examples above more than people expect.

## Specs that matter here, and ones that don't

Networking gear is one of the more forgiving categories to back up, so most of the strict requirements that apply to sensitive equipment (see our CPAP sizing guide for an example) don't really apply the same way.

Pass-through or UPS-style charging is the one spec that genuinely matters. Confirm the station explicitly supports charging while providing output at the same time, sometimes called "UPS mode," so your gear can stay permanently connected without a manual swap during an outage.

Continuous wattage rating barely matters here. Any power station rated for even 100-150W continuous output comfortably covers networking gear, so this isn't the bottleneck.

Sine wave output is a lower priority for this use case than it is for CPAP machines or other sensitive electronics. Most router and modem power supplies are simple AC-to-DC converters that tolerate modified sine wave input fine, though pure sine wave is still a safe default if you're buying a station for other reasons too.

## How this fits with the rest of your outage plan

If you're sizing one station to cover your router, modem, and a handful of other essentials, add up the total watt-hour need across every device rather than sizing for networking gear alone. Our [breakdown of running a mini fridge on battery power](/Logans-site/2026/07/08/how-long-portable-power-station-run-mini-fridge/) walks through exactly this kind of multi-device planning, since the fridge is usually the biggest single load in a renter's outage plan and everything else stacks on top of it.

## A few common questions

Will my internet work if my router has power but my neighborhood's cable or fiber node doesn't? No. Your equipment needs a live signal reaching it. Powering your router and modem is necessary but doesn't guarantee upstream connectivity during a long outage, see the ISP section above.

Do I need a separate battery for my router if I already have a power station for my fridge or CPAP? Not necessarily. Networking gear draws so little that most stations sized for a fridge or CPAP have plenty of spare capacity to also run a router and modem for the same outage. Just add the wattage into your total when sizing.

Is a cellular hotspot a replacement for router battery backup? It's a good supplement, not a replacement. A hotspot depends on cell tower connectivity and your own phone battery, and usually costs more per gigabyte than home internet. Most people are better off battery-backing their existing router and modem first, with a hotspot as a fallback if the outage also knocks out the ISP's upstream infrastructure.

## Where to look

<div>{% raw %}<!-- affiliate search links, tag to be added on Amazon Associates approval --> {% endraw %}</div>

- [Browse compact portable power stations with pass-through/UPS charging on Amazon](https://www.amazon.com/s?k=portable+power+station+pass+through+charging+ups&tag=AMZTAGPLACEHOLDER)
- [Browse dedicated mini UPS units for routers and modems on Amazon](https://www.amazon.com/s?k=mini+ups+battery+backup+router+modem&tag=AMZTAGPLACEHOLDER)
- [Browse 300Wh-class portable power stations on Amazon](https://www.amazon.com/s?k=portable+power+station+300wh&tag=AMZTAGPLACEHOLDER)

Check your specific router and modem's wattage on the power adapter label before buying, and confirm any power station you're considering explicitly supports pass-through or UPS-style charging if you plan to leave your equipment connected permanently.
