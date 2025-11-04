---
title: "Mathematical Framework for Modeling the Movement of Adult Spotted Lanternfly into Vineyards and Application for Optimal Control "
collection: talks
type: "Talk"
permalink: /talks/SLF3
venue: "Spotted Lanternfly Research and Technical Development Meeting"
date: 2024-10-16
location: "Wooster, OH, USA"
---
# Mathematical Framework for Modeling the Movement of Adult Spotted Lanternfly into Vineyards and Application for Optimal Control

**Jacob Woods¹, Fatma Seker, Benjamin Seibold¹, and Matt Helmus²**  
¹Department of Mathematics and ²Department of Biology, Temple University  
1805 North Broad Street, Philadelphia, PA 19122  
jacob.woods@temple.edu  

---

## ABSTRACT

The spotted lanternfly (*Lycorma delicatula*, SLF) is a plant hopper that primarily feeds on hosts such as the tree of heaven and grape vines. Hosts may succumb and die from the infestation, posing a significant concern for the agricultural industry; in particular, vineyards are at great risk. SLF can damage and even kill vines throughout a season. This, coupled with the emergence of adults—the time when SLF are most mobile—coinciding with grape harvest, makes the control of SLF very challenging in these landscapes. 

The SLF has been observed participating in a gliding-ascending cycle where the SLF “jumps” or is knocked off a host and moves randomly away for some time, eventually seeking out a new host, then finding a host, climbing up, and repeating the cycle.

We construct a model based on the gliding-ascending cycle of the SLF to capture how agents move around in a landscape of hosts. This model utilizes experimental data to help parameterize model functions describing the movement and preferences of SLF. Further, we reduce the model using assumptions based on SLF behavior to a Markov model for how SLF hops from host to host. We model SLF movement in three stages:

- **Feeding Stage:** SLFs spend most of their time on hosts feeding.  
- **Gliding Stage:** SLF glide pseudo-randomly away from hosts.  
- **Seeking Stage:** SLF head towards the most attractive host they see based on their current location.

We assume that SLF glide away from a host on average a distance proportional to the height with a fixed variance, and that a host’s attractiveness at a given location is based on its height, species, and distance from the host. This allows us to construct a host-hopping model on a given arrangement of hosts by parameterizing only the preference for each host type, the gliding variance, and the mean gliding distance.

Using satellite data and data from the NEON SERC database, we apply our host-hopping model to the Vineyards at Dodon, a Maryland-based vineyard.

We run our host-hopping model on the Vineyards at Dodon landscape digitized as described above for 70 days, representing the time from adult emergence until grape harvest. Compared to field observations, we see qualitatively similar distributions of SLF, with the population quickly invading and occupying the edge of the vineyard but rarely moving deeply into it.

We then examine control actions based on thresholds for a fixed initial population, analyzing how various thresholds affect the population over time in the vineyard. We find that thresholds that are too low fail to control SLF moving into the vineyard late in the season, while thresholds that are too high fail to prevent early-season damage by SLF entering the vineyard. All thresholds are tested for two different initial conditions, and we observe which threshold maximizes damage reduction in the vineyard compared to no control action.

We find that, for a given geometry, the relationship between threshold and damage reduction is non-trivial; for different initial conditions this relationship appears qualitatively distinct. This indicates that the optimal choice of threshold for control actions may be **context-dependent**.
