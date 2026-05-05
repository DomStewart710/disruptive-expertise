---
title: Disruption of U.S. Interstate System on Cities
layout: base
header-title: Essays
---
header-image: image/us-interstate-map.jpg

# The Disruption of the U.S. Interstate System on Cities

# Who got Affected by Highways
The construction of the interstate system within cities was often synonymous with "slum clearance" and urban renewal, strategies that intentionally targeted poor and minority neighborhoods. Influential planners like Robert Moses advocated for highways to go "right through cities and not around them," viewing the massive infrastructure as a tool to raze areas designated as "blighted". This policy led to the displacement of more than one million people and 475,000 households nationwide, with neighborhoods of color bearing a disproportionate share of the destruction. For instance, the expansion of I-95 in Miami decimated the vibrant Black community of Overtown, reducing its population from 40,000 to just 8,000. Similarly, I-94 in St. Paul divided the Rondo neighborhood, shuttering 300 businesses and displacing 600 families.

# Immediate Effects of the Highways
Beyond immediate demolition, highways were frequently used as tools of racial segregation, creating physical buffers that isolated communities of color from white areas. In Atlanta, planners designed I-20 specifically to serve as a boundary between Black and white residents, reinforcing racially determined neighborhood limits. These "concrete walls and asphalt no man’s lands" not only severed community cohesion but also led to long-term economic decline, loss of local tax bases, and severe health disparities, such as increased asthma hospitalization rates in neighborhoods bordering major interchanges.

# The Destruction of the Urban Core
While the system gutted urban cores, it simultaneously fueled the rise of the modern suburb. The 1956 Act predicated 90 percent federal funding on the condition that highways connect emerging suburbs to downtown centers where commuters worked and shopped. According to Land Use Theory, the introduction of high-speed "rays" reduced commuting times, which lowered population density in the center and increased the demand for suburban space. Empirical research indicates that each new highway passing through a central city reduced its population by about 18 percent between 1950 and 1990.
This mass migration, often termed "white flight," was facilitated by the ease of travel the interstates provided. As white residents utilized the "beautiful new highways" to escape diversifying urban centers, they were often assisted by discriminatory practices like redlining and restrictive covenants that were common in the newly accessible suburban ring. Best causal estimates suggest that "white flight" accounts for roughly 20 percent of total suburban growth during the postwar period.

# Conclusion
In conclusion, the U.S. interstate highway system achieved its goal of connecting the nation, but at the cost of the viability and social fabric of its cities. What were intended as arteries of commerce and defense often became agents of displacement and segregation, creating an automobile-dependent suburban model that remains the dominant feature of the American landscape today. Modern urban planning is now increasingly focused on remediating these harms through highway removals and "capping" projects intended to reconnect neighborhoods severed decades ago

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-stack.html cards=cards %}