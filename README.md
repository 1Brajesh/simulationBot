# Simulation Bot

**Live site:** https://1brajesh.github.io/simulationBot/

## L1 World Resource Map (main page)

An interactive world map of where the 20 physical-layer ("L1") resources are found: fresh water, land and soil, sunlight, climate, air and gases, crude oil, natural gas, coal, natural energy flows, iron ore, base metals, critical minerals, nuclear minerals, precious metals and gems, fertilizer minerals, industrial minerals, building materials, living things, oceans and seabed, and people. Pick a resource to shade its top countries, with each country's share of world reserves or production labeled with its source and year. Click a country to see which resources it ranks high in. A geography layer shows key chokepoints, straits and major rivers.

The map follows the bottom of the seven-layer world model. A layer switch flips between **L1 Raw** (20 resources), **L2 Extraction & harvesting** (14 items: drilling, mining, quarrying, crops, meat, fish, logging), **L3 Processing & manufacturing** (16 items: refining, LNG, power, steel, aluminum, refined metals, battery-mineral refining, chemicals, cement, silicon/solar, chips, enrichment, wood and paper, water treatment) and the cross-cutting **Labor** column (workforce, tertiary students). Country profiles flag L2-vs-L3 gaps (e.g. mines a lot of cobalt but refines little), and optional arrows link the top L2 extractors to the top L3 processors.

Measure tags use a distinct word per layer: **RESERVES** (still in the ground), **MINED** / **HARVESTED** (taken out that year: minerals, oil, gas and coal are mined; crops, meat, fish and timber are harvested; yearly mine figures shown under L1 use the same tag), **REFINED** / **MADE** (L3: metals and fuels are refined; steel, cement, chips, chemicals, power and paper are made), **CAPACITY** (what plants could handle), and **INTENSITY** (a strength value, not a share). Sunlight is shaded by average solar strength (GHI, kWh/m²/day) per country from the World Bank / ESMAP / Solargis "Global Photovoltaic Power Potential by Country" study (2020).

L2/L3 sources add: IEA Global Critical Minerals Outlook 2026 (refining shares by country), IGU World LNG Report 2025, SIA/BCG semiconductor fab capacity (2022), IEA PVPS, Cefic, FAOSTAT Forestry, World Bank/ILO and UNESCO UIS.

Sources: USGS Mineral Commodity Summaries 2026, Energy Institute Statistical Review of World Energy 2025, World Nuclear Association, FAO (AQUASTAT, FAOSTAT, Forest Resources Assessment 2025, SOFIA 2024), and UN World Population Prospects 2024. Sunlight, climate, natural energy flows and oceans are shown as qualitative layers because there is no clean country-share data for them. Map outlines come from Natural Earth via world-atlas. River lines are simplified.

`index.html` is a single self-contained file with no external runtime dependencies.

## Archive

See [`archive/`](archive/) for past versions: *The World Economy, Five Ways* and the original *World Economy Contraption*. Those are illustrative only, not forecasts and not financial advice.


Map styles: metals, minerals and energy (and their L2/L3 steps) are drawn as circles sized by share of world; land, water, forests, fish, crops, meat, timber, paper, population and labor use graded shading; sunlight is shaded by solar-strength value. Every share measure outlines the smallest set of countries reaching 80% of the world total.

Groups with several items (base metals, critical minerals, precious metals, fertilizer and industrial minerals, and grouped L2/L3 steps) open on an All view of small pies per country: pie area = average of the country's world shares across the items; slices = its share of each item. Chips above the map switch to a single item, with a RESERVES/MINED switch where both exist.
