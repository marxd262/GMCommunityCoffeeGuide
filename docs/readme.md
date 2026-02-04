<meta charset="utf-8">  

The GaggiMate Community guide to great Espresso

Contents:

- [1. Preamble](#1-preamble)
  - [1.1. Important notes](#11-important-notes)
- [2. Cheat Sheat](#2-cheat-sheat)
- [3. Core Concepts](#3-core-concepts)
  - [3.1. Repeatability and Workflow](#31-repeatability-and-workflow)
  - [3.2. Water as a Solvent](#32-water-as-a-solvent)
  - [3.3. What does Gaggimate even do?](#33-what-does-gaggimate-even-do)
  - [3.4. Profiles](#34-profiles)
  - [3.5. The Taste of coffee](#35-the-taste-of-coffee)
  - [3.6. The Lifecircle of a shot](#36-the-lifecircle-of-a-shot)
- [4. Variables and how they change the Taste](#4-variables-and-how-they-change-the-taste)
  - [4.1. Variables before Extraction](#41-variables-before-extraction)
    - [4.1.1. Bean choice](#411-bean-choice)
    - [4.1.2. Amount of ground coffee (dose) ](#412-amount-of-ground-coffee-dose)
    - [4.1.3. Bed depth](#413-bed-depth)
    - [4.1.4. Grindsize](#414-grindsize)
  - [4.2. Variables during a shot](#42-variables-during-a-shot)
    - [4.2.1. Yield](#421-yield)
    - [4.2.2. Ratio](#422-ratio)
    - [4.2.3. Temperature](#423-temperature)
    - [4.2.4. Pressure](#424-pressure)
    - [4.2.5. Flow](#425-flow)
- [5. Calibration based on Taste](#5-calibration-based-on-taste)
- [6. The Ideas behind Shot styles](#6-the-ideas-behind-shot-styles)
- [7. How to read the GM Graph](#7-how-to-read-the-gm-graph)


# 1. Preamble

## 1.1. Important notes

The most important info before anything else: Espresso is as complicated as you want it to be. In the end Gaggimate gives you alot of Data and Graphs and so on. It can be very tempting to go heavy into all this data and try to read stuff into it. But thats where a big mistake lies. The data you get is just a trend. It can help with a general direction, especially if you know your input parameters like coffee, water and so on. 

But all this data leaves one thing out: coffee is highly subjective! 

The coffee someone else loves, doesn't have to be the right coffee for yourself! And even if you found a graph that tastes perfect for your current beans, as soon as you change the beans, the perfect graph will probably not taste as good as on the beans before. Every coffee is different and thats why its so beautiful.

I can tell you alot about what a nice graph should look like, but every profile is different and what you like will be different then what I like.  
  
While I will try to explain some points graphs and how to read what GM gives you, I will also try to link this to taste and how to change variables more based on taste then what you see on the graph.   
  
The one and only thing you should learn from this document is:

TASTE IS KING!

Ignore the Data and focus on taste. Use the data as a rough estimate but not as a rule. If it tastes good to you, all the data is unimportant. 

# 2. Cheat Sheat

Espresso has a limited but tightly coupled set of variables. Because each parameter affects the others, the most reliable way to learn is to change only one variable at a time, pull a shot, and evaluate how the flavor, body, and balance shift. This step‑wise method builds intuition and ensures repeatable results.

Most Profiles provide a rough guide where the creator thinks it tastes best. Try to get somewhere in that area and see what you want to change.  
  
Here is what I would focus on and in what order:

1. Set temp to a fitting start for the roast. Usually 88℃ dark, 91℃ medium, 93℃ light. The Profile creator sometimes suggests other values
2. Adjust the grind size based on time and get in the rough ballpark of the profile suggested time.

After that I would focus on taste and let it guide you:

- To Bitter (dry..)?
    - If way to bitter: grind coarser
    - Alternatively: reduce dose
    - If only a bit to bitter: decrease yield
    - Lower Temp a bit
- To sour (salty…)?
    - If Way to sour: grind finer
    - Alternatively: increase dose
    - If only a bit to sour: increase yield
    - Increase Temp a bit
- Not sweet/heavy/concentrated enough or too weak?
    - Decrease yield to get a higher ratio
    - Alternatively increase temp

Practical workflow

1. Identify the dominant flaw (bitterness, sourness, lack of body).
2. Apply (an) adjustment (coarser/finer grind, dose change, yield change, or temperature tweak).
3. Pull a shot and taste.
4. Iterate, changing only one variable at a time to build clear cause‑and‑effect understanding.

Two Guides from Baristahustle that I think are helpfull.

![Baristahustle Espresso Compas 1](./assets/Screen_Shot_2021-12-21_at_3.33.17_PM.png)

![Baristahustle Espresso Compas 2](./assets/The%20Espresso%20Compass-1.jpg)


# 3. Core Concepts

## 3.1. Repeatability and Workflow

I can't stress this point enough. Repeatability is one of the most important factors. The biggest advantage for GM is repeatability. It can replicate shots and do it again and again and again. All this with a stable pressure, flow and temperature. But for that to matter, you have to get some things right. It's important that your puck prep is repeatable. It doesn't matter what you do, you have to be able to repeat it. It starts with weighing the beans. GM cant do its job, if you don't use the same dose for your shots. The dose should have a good distribution in your portafilter and afterwards the tamp should be even with a consistent pressure. GM should also be repeatable set up.To have this repeatable I recommend to implement a workflow and stick to this workflow. Experiment with this and find out what works for you. It doesn't have to be complicated but it should be repeatable. 

My current workflow

1. Preheat my machine for 20 minutes. (The default standby time is too short for this. Increase if you want to preheat a bit longer)
2. Start my scale
3. Flush through the portafilter to make sure the grouphead and portafilter is preheated. I flush into the cup I'm gonna drink from to make sure its up to temp.
4. Weigh my beans.
5. Check that the grindsetting on my grinder is correct.
6. I grind directly into a cheap blindshaker from amazon.
7. While the grinder is working I put the cup with hot water on the cupwarmer and take the portafilter out.
8. I clean the portafilter with a towel to make sure it's dry and clean.
9. Put the portafilter with a funnel on my tampstation
10. Use the blower of my grinder to make sure all the grinds are in the Portafilter.
11. Use the blindshaker by shaking for 5-10 seconds
12. From about 5cm height use the blind shaker and let the grinds fall into the portafilter. I aim for a small mount in the middle.
13. Check distribution in the portafilter. Like I said, I aim for a small mount in the middle. If needed I distribute by knocking the portafilter.
14. Afterwards I knock the portafilter flat on the table to compress the beans a bit.
15. Use a self leveling spring tamper to tamp flat. ( If you don't have a calibrated tamper, it's better to tamp harder than to soft. It's not possible to tamp too hard, just too soft.)
16. Add my puckscreen and spring.
17. Empty my cup
18. Put the portafilter in the machine
19. Reduce pressure in machine by opening the steam valve for a second or two
20. Place the cup under the portafilter
21. Start the extraction
22. While extracting I clean around the prep area what needs cleaning
23. After extraction I instantly take the cup and put it on the cupwarmer.
24. I remove the portafilter, take the puckscreen and spring of
25. Knock the puck out and put the Portafilter back in.
26. Enjoy the espresso

That sounds like a lot of steps and extras, but in the end it's a workflow that I find easy to replicate without thinking too much. Maybe you noticed that some stamps that may be recommended seem to be missing. Like WDT, Distributor, flush after the shot. For me personally I noticed that they don't make a big difference.  
  
The Idea behind WDT is to remove clumps and distribute the grinds evenly. My grinder doesn't produce many clumps. Further I use a stepdown basket and don't have to grind as finely, this also reduces clumps. Also the distribution with a WDT isn’t needed in my workflow. The Blindshaker and hitting the portafilter lightly is enough to get a good distribution. I personally don't like the spinny distributors. They mostly just distribute on top and flatten it all out. The bottom stays untouched. They give the impression of a nice distribution but don't really deliver on this. And for a flush after the shot, After using a puckscreen I noticed that the water on top of the puck was clean and flushing after the shot just gave me clean water. So I just removed the step.

My checklist and workflow doesn't have to work for you. You should try to see what works for you and experiment if needed. Maybe some steps are too much for you or feel like a hassle? That's totally ok. Just find something that gives you repeatable results.

## 3.2. Water as a Solvent

In espresso, hot water functions as a solvent that pulls soluble flavors from the coffee grounds. Changing different variables, alters how much material the water extracts, shaping the final taste.

## 3.3. What does Gaggimate even do?

Gaggimate isn't just a magical creation that our saviour the mighty Wasp brought to us to awaken us. It's a fancy PID with extrastep and an automated recipe user. Those Recipes are called Profiles. They can massively change how the coffee tastes but in the end we as the user decide how they do it. These Profiles give us all one important thing: Repeatability.

## 3.4. Profiles

Espresso profiles are programmable sequences that tell GM what temperature, flow rate, and pressure to apply at each stage of extraction. A profile can contain several sections (such as pre‑infusion, pressure ramp, and steady‑state) each with its own targets. By selecting or customizing a profile, the user decides which aspects of the shot to emphasize, while the ultimate flavor still depends on the barista’s variables (grind size, dose, tamp, bean quality, etc.).

The most used profiles would be:  
Cremina Lever (medium - darker)

Damians Lever (light - medium)

Adaptive v2 (light - medium)

Automatic pro (light - dark)

All profiles have a sweet spot where they work the best. What they aim at and what to look out for is normally described in the Discord thread of the different profiles. Look at those threads first to get a starting point. Afterwards they need to be tweaked by hand.

## 3.5. The Taste of coffee

Espresso flavor can be boiled down to two primary taste axes: sour (linked to under‑extraction) and bitter (linked to over‑extraction). Balancing these extremes is the first step toward a good shot. Beyond taste, mouthfeel (the body and viscosity of the espresso)adds another dimension, ranging from thin and light to thick, juicy, or syrupy. Because each coffee bean (origin, roast, processing) expresses a unique combination of acidity, bitterness, and texture, the ideal profile varies from bean to bean. The only reliable way to discover your preferred espresso is to experiment with different variables, tasting the results and adjusting until the desired balance is achieved.

## 3.6. The Lifecircle of a shot

During extraction, the coffee bed releases compounds at different rates. The first seconds deliver the bulk of oils, volatile aromatics, and soluble solids, creating a thick mouthfeel, strong crema, and pronounced acidity. As the shot continues, fewer solids are drawn out, the liquid becomes more watery, and the balance shifts toward bitter, higher‑molecular‑weight compounds. An under‑extracted shot therefore tastes sour, while an over‑extracted shot tastes bitter.

A practical way to experience this progression is the onion‑shot test: during extraction switch the cups every 5–6 seconds. This results in multiple cups with an extraction gradient. Taste the cups in reverse order (last‑collected first) to perceive how the early, concentrated portion differs from the later, more diluted portion. This exercise highlights the evolution of flavor, body, and crema across the extraction. It also trains to taste the differences between sour and bitter.

# 4. Variables and how they change the Taste

Directly controllable

- Bean choice – origin, roast level, freshness
- Dose (amount of ground coffee) – determines bed depth and resistance
- Grind size – affects flow resistance and extraction speed
- Target yield (output volume) – defines brew ratio together with dose
- Brew temperature – influences solubility of flavor compounds
- Basket diameter – changes bed geometry and pressure distribution

Indirectly influenced (result of the above)

- Flow rate – the speed at which water moves through the puck
- Brew ratio – dose ÷ yield, a key metric for balancing extraction
- Pressure – generated by the pump; affected by grind, dose, and basket size
- Extraction time – total time water contacts the coffee, derived from flow and pressure

## 4.1. Variables before Extraction

These are the variables that get decided before we even start the extraction.

### 4.1.1. Bean choice

- Roast level: Light roasts are denser, so they need a finer grind, higher brew temperature, or more pressure to achieve proper extraction. Dark roasts are more porous and extract more readily, allowing a slightly coarser grind or lower pressure. Adjust your extraction variables accordingly.
- Freshness: After roasting, beans retain CO₂-especially darker roasts. Allow ~7‑10 days for degassing before brewing. As beans age, volatile aromatics dissipate and the coffee becomes harder to extract, so you may need to fine‑tune grind size, dose, temperature, or pressure to maintain flavor balance. Use beans within the first two months of the roast date for optimal results. That doesn't mean you should throw away older beans.

### 4.1.2. Amount of ground coffee (dose) 

Increasing the dose adds more soluble compounds for the water to extract and creates a deeper puck. The greater bed depth raises the puck’s resistance, slowing flow and extending extraction time. Adjustments in other areas like yield, grind size and so on will be needed.

### 4.1.3. Bed depth

Bed depth is set by dose and basket size; a deeper puck raises hydraulic resistance, so you typically coarsen the grind (or lower the dose) to maintain flow. A smaller‑diameter basket (stepdown basket) can keep the same grind size only if the dose is reduced.

### 4.1.4. Grindsize

Grindsize is probably the best known variable, because for a lot of machines it's one of the only variables that can be changed.  
  
Grind size controls resistance and therefore extraction: finer → higher extraction, coarser → lower extraction. 

One more or less important factor: Grind size not only sets extraction level but also determines the uniformity of the particle distribution. Finer grinds extract faster but produce a broader range of particle sizes, mixing fast‑extracting fines with slow‑extracting larger particles and blurring flavor clarity. Since all grinders inherently generate some size variance, opting for a modestly coarser grind (which narrows the distribution) can give the clearest, most defined cup - assuming the rest of the brew parameters are adjusted to maintain adequate extraction. A coarser grind size could be achieved with a higher beddepth which could be achieved through a stepdown basket (lower diameter) or using a higher dose.

## 4.2. Variables during a shot

This are variables that get set through the profile or other 

### 4.2.1. Yield

Yield (output volume) has the greatest influence on espresso taste. A higher yield-more water passing through the puck-extracts more bitter and sweet solubles, reducing the perceived sourness. Conversely, a lower yield emphasizes acidity.

### 4.2.2. Ratio

Ratio describes the relationship between dose and yield. The Ratio impacts the concentration and mouthfeel. Lower ratio (e.g., 1 : 1.5) → higher concentration → richer, heavier body and more pronounced mouthfeel.

Higher ratio (e.g., 1 : 2.5) → lower concentration → lighter texture and a more delicate mouthfeel.

### 4.2.3. Temperature

Water temperature is the primary driver of solvent power. Higher brew temperatures increase extraction, while lower temperatures reduce it. As a rule of thumb, begin with:

- Dark roasts: 88 °C – 90 °C
- Medium roasts: 90 °C – 92 °C
- Light roasts: 92 °C – 96 °C

Then adjust up or down in small increments (±1 °C) until the desired balance of acidity, sweetness, and body is achieved for the specific bean.

### 4.2.4. Pressure

Higher brew pressure drives water deeper into the coffee puck, extracting more solubles. Excessive early pressure can over‑compact the puck, raising pressure later in the shot.

Pressure is the product of flow rate and puck resistance (dose, grind, basket size).

### 4.2.5. Flow

Fast flow → short contact time → lower overall extraction (brighter, more acidic, less bitter).

Slow flow → long contact time → higher extraction (richer body, more bitterness).

# 5. Calibration based on Taste

Now we get to the interesting stuff. 

# 6. The Ideas behind Shot styles

# 7. How to read the GM Graph