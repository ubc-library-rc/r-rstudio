---
layout: default
title: Exercises
nav_order: 5
---

# Exercise 1

### Calculate

- 1+1
- 4-9
- 19/3
- 14*6
- 4^3

### Assign values to variables
- a <- 4
- a     
- b <- 5
- b

**Question:** What do you notice in the Environment pane?

### Calculate
- c <- 6 + a
- c
- d <- a + b + c
- d
- c==d

# Exercise 2
Finding max, min, and average of GDP (in millions USD) of Europen countries in each year for all the years before 2000

- Filter observations of European countries before 2000
- Use mutate to create a GDP variable (measured in millions USD)
- Group by year
- Summarize the min, mean, max, and range of GDP


# Exercise 3

Make a timeplot of `gdpPercap` for countries in Americas with population above 15m (points should represent the size of population)

Hints:

- Use filter function to limit the selection of data to Americas, pop > 15000000
- Use ggplot, geom_point, and geom_line to make a graph

