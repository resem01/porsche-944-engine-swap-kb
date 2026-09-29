# 07K Donor Selection and Engine Notes

This document consolidates the useful donor-selection and engine-family information from the long Rennlist 07K development thread. It intentionally excludes conversational filler.

## Core architecture

The naturally aspirated Volkswagen 07K is a 2,480 cc inline five with:
- cast-iron block
- aluminum DOHC 20-valve cylinder head
- variable intake cam timing
- chain-driven camshafts
- port fuel injection
- 60-2 crank trigger integrated at the rear-main-seal area

The 07K is not simply a newer version of the older Audi 20V inline-five. The bellhousing pattern, timing-chain layout, and accessory packaging are materially different.

Primary development source:
- [Rennlist 07K swap thread](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread.html)

## Engine-code groups

### BGP / BGQ / BPR / BPS — approximately MY2005-2007

Thread summary:
- roughly 148 hp / 166 lb-ft in stock form
- earlier timing-chain design
- six-bolt flywheel/crank interface
- forged crankshafts appeared in some engines, but not predictably
- visual identification of forged vs cast crank was discussed by forging flash-line width; treat this as builder guidance, not factory identification data

The early engines can work, but the thread increasingly favored later engines because of the revised timing-chain system.

### CBT / CBU — approximately MY2008+

Thread summary:
- roughly 168-170 hp / 176-177 lb-ft stock
- revised timing-chain hardware
- six-bolt crank/flywheel interface
- factory forged crank is not generally expected
- Audi TT-RS forged eight-bolt crank is physically relevant to high-power builds

## Practical donor recommendation from the development team

A recurring recommendation in the thread was **2008-2010**:
- revised timing-chain system
- earlier mechanically controlled oil-pump arrangement
- inexpensive donor availability
- simple six-bolt crank arrangement adequate for ordinary NA and moderate turbo builds

Later 2011+ engines use a different pressure-controlled oil-pump strategy. Page 144 records the development team's view that the earlier pump is **not known to retrofit** to the 2011+ engine. They also reported examples of later engines operating at high rpm with the oil-pressure solenoids disabled so the pump remains in high-pressure mode.

The 2008-2010 preference should therefore be read as a **simplicity/package preference**, not a hard prohibition against 2011+ engines. On a later engine, the pressure-control solenoid/mount clearance also needs to be checked against the specific generation of swap mount being used.

Relevant thread pages:
- [Page 75](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-75.html)
- [Page 109](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-109.html)
- [Page 140](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-140.html)
- [Page 144](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-144.html)

## EA855 Evo / later aluminum-block five-cylinder

Page 140 notes that the later aluminum-block Audi five-cylinder retains the general bellhousing relationship, but is **not a drop-in substitute** for the normal iron-block 07K swap. The thread identifies:
- likely driver-side mount differences,
- changed coolant/oil-system packaging,
- greater top-end height because of Audi Valvelift hardware.

Until common-datum measurements exist, the EA855 Evo/RS3 engine should be treated as a separate packaging problem rather than another 07K donor-year option.

Source:
- [Page 140, post #2087](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-140.html#post16712164)

## Crankshaft and flywheel interface

### Six-bolt VW crank

The normal VW 07K six-bolt crank was treated as suitable for:
- naturally aspirated builds
- moderate turbo power
- approximately 300-400 hp class builds

At higher torque, builders raised concern about the six-bolt flywheel interface and bolt stretch. ARP fasteners and/or additional crank/flywheel retention work were discussed.

### Eight-bolt TT-RS crank

The forged TT-RS crank was repeatedly described as an upgrade path for high-output builds because it combines:
- forged construction
- eight-bolt flywheel interface
- stronger high-torque flywheel attachment

It is **not required** for a normal 07K swap. Later thread discussion explicitly pushed back on the idea that a rare Audi crank should be treated as mandatory.

Relevant thread pages:
- [Page 93](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-93.html)
- [Page 176](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-176.html)
- [Page 177](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-177.html)

## Stock-internal power discussion

The thread repeatedly references approximately **400 hp / 400 whp-class** use on stock cast internals as plausible, but this is builder/community evidence rather than a controlled endurance limit.

For higher power, the discussion consistently shifts toward:
- forged rods
- forged pistons
- improved fasteners
- TT-RS / RS3-derived crank and internal-component strategies

Do not treat any single horsepower number as a hard engine limit.

## RPM considerations

Useful distinctions from the thread:
- the 60-2 crank trigger is not tied to the flywheel, simplifying standalone ECU use
- stock cams become a limiting factor at higher rpm
- discussion of 7,200+ rpm repeatedly introduces harmonic-balancer, valvetrain, oiling, and crank considerations
- 8,000+ rpm operation belongs in a purpose-built engine, not a generic donor-motor recommendation

## Packaging relative to the Porsche M44

The development thread reports:
- about **6.5 in shorter** from bellhousing plane to front crank pulley
- block itself about **2.5 in shorter**
- timing-chain housing protrudes roughly **4 in behind** the nominal rear block/bellhousing region

The rear timing housing is the reason a simple 1.8T-style adapter plate is problematic.

These are builder-development dimensions and should eventually be replaced or confirmed by common-datum measurements on project engines.

## Project recommendation

For a practical street/track 944 build today:

**Default screening donor: 2008-2010 CBT/CBU-family 07K.**

Use an earlier engine only when price/condition makes it compelling. Use a TT-RS crank only when the power target and flywheel-retention requirements justify the cost and additional work.
