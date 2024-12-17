# david-ruiz-capstone-ddr14
David Ruiz | LEGO Capstone | DDR14

# What to build next... a LEGO Ideas presentation
![DHS logo](./images/LEGO.png)

## Analysis of LEGO data from Rebrickable, to help guide builders to choose which theme to use when creating for a LEGO Ideas submission

## TABLE OF CONTENTS
* [Executive Summary](#executive-summary)
* [Motivation](#motivation)
* [Data Source](#data-source)
* [Analytical Approach](#analytical-approach)
* [Tools Used](#tools-used)
* [Additional Information](#additional-information-was-found-at)
* [Power BI Story](#power-bi-story)
* [Canva Presentation](#canva-presentation)

### Executive Summary
LEGO hosts the website ideas.lego.com where users can upload personal/custom built sets, where they are then voted on by LEGO fans alike in hopes the set will ultimately be produced and sold by LEGO. Using data from Rebrickable.com, I’ve created some guidance for builders to know which set themes have better track records to guide them towards themes most likely to get picked up by LEGO.

### Motivation
I’ve been a fan of LEGO since I was a child. After taking a ~20-year break, I got back into LEGO ~6 years ago at 33 years old and have loved my reintroduction. Set designs and overall quality have only gotten better since I started my hiatus, which drove my interest to look further into this powerhouse of a company. I explored the following:

- Look into all LEGO sets, regardless of theme, over a time span. Identify any contributing factors linked to years/decades where set count decreased vs increased. 
- Look into theme diversity to identify set counts per theme to understand what Lego is more likely (and less likely) to produce from Lego Ideas. Goal to identify dominance to assert concentration.
- Using the top 10 themes identified above, look into theme popularity over time via set count, identifying annual and decade-based theme progression. 
- Identify themes that have endured the tests of time, answering which themes will likely maintain relevance. 
- Which themes have the top/bottom available resale sets on ReBrickable? This shows which themes are valuable enough to re-sell, giving further insight into which themes to concentrate on or avoid. 
- Identify sets produced based on volume of pieces. Divide sets into groups of 1 - 50, 51 – 250, and 251+. Looking at trends in piece count over time to understand if piece count could be a contributing factor to eligibility.

### Data Source
To answer these questions, I used the following data retrieved from [Rebrickable](https://rebrickable.com/downloads/)
- colors
- elements
- inventories
- inventory_minifigs
- inventory_parts
- inventory_sets
- minifigs
- part_categories
- part_relationships
- parts
- sets
- themes
- lego_power_bi (created from above tables for use in Power BI)

### Analytical Approach
#### Minimum Viable Product (MVP)
- Slide deck via Canva
- Bar and Line Plots created using Python
- Dashboard via Power BI to allow LEGO theme deep dives with images and custom interactivity
- The intended audience is LEGO fans, but more specifically, fans looking to submit designs to LEGO Ideas

#### Known Issues and Challenges
The data I found was pretty sound, not much cleaning necessary, but there are a couple data points I’ll need to add:
- I determined decade using the ‘year’ column in ‘sets’ data frame
- I designated a set size using ‘num_parts’ column in ‘sets’ data frame

### Tools Used
- `Python/Pandas` - for exploration and aggregation of the data

- `Power BI` - for creating interactive dashboard

- `Canva` - for slide presentation

- `Git` - for version control

### Additional information was found at:
- [Lego Wiki](https://en.wikipedia.org/wiki/Lego)
- [Bionicle Wiki](https://en.wikipedia.org/wiki/Bionicle)
- [Rebrickable](https://rebrickable.com/)
- [Lego Insights](https://brickinsights.com/)
- [Ideas Tracker](https://ideas-tracker.com/)

### Power BI Story
The purpose of this dashboard is for builders to select a theme, then select a set from that theme. Once selected an image of the set will display, a table will show a list of all parts and quantities necessary for that set, and a matrix shows images of each piece in that set. The purpose for this dashboard is for a LEGO fan to be able to know which pieces they need to build different sets. They can then get the free digitial instruction guide directly LEGO.com.
- [David Ruiz | LEGO Capstone](https://app.powerbi.com/view?r=eyJrIjoiZjJkODM3NmItYjU3Ny00NDJkLWFhMGEtNzExMjkxMjdlOTQxIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9)

### Canva Presentation
- [David Ruiz | LEGO Capstone](https://www.canva.com/design/DAGZeAFWRwA/zkQgeHS4y1iivvCVyU6JYg/edit?utm_content=DAGZeAFWRwA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)