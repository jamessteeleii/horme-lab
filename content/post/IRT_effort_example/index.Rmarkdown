---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Actual Effort in Cognitive Tasks"
subtitle: "Can Item Response Theory help with operationalisation?"
summary: "Item Response Theory assumes latent abilities, and varying difficulties for items... both could be useful, given my definition, for operationalising actual effort"
authors: []
tags: []
categories: []
date: 2022-01-24T16:06:15Z
lastmod: 2022-01-24T16:06:15Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# _Conceptual definition of actual effort_
In my [article](https://www.hormelab.com/what_is_effort/) I define actual effort as follows:

> "Effort; _noun_;
That which must be done in attempting to meet a particular task demand, or set of task demands, and which is determined by the current task demands relative to capacity to meet those demands, though cannot exceed that current capacity."

And more specifically following Markus[^1] Set Theoretical approach as:

>"Effort (concept);
$\ E_{A}(i, t, C_{A}, D_{A}, w, T_{Any})$ is the actual effort for any individual $\ i$ at time $\ t$ where $\ C_{A}(i, t, x_{C})$, and $\ D_{A}(i, t, x_{D})$ are the actual capacity and actual demands respectively, and $\ x_{C}$ and $\ x_{D}$ are the magnitudes of those respectively for individual $\ i$ at time $\ t$, where $\ w$ denotes all possible states of affairs (i.e. combinations of $\ i, t, C_{A}$, and $\ D_{A})$, and $\ T_{Any}$ denotes the boundary conditions noting it as intensional to all possible types of tasks."

And which is expressed as a derived ratio, given that capacity and demands have natural origins (capacity can be zero, as can demands, but neither can be less than zero):

$$\ D_{A} \leq C_{A} \Rightarrow E_{A} = \frac{ 
D_{A}}
{C_{A}} \times 100%$$

$$\ D_{A} > C_{A} \Rightarrow E_{A} = 100%$$

Where the ratio is expressed as a percentage (%). 

Now, the $| T_{Any}$ argument is important for what I am about to present. The conceptual definitions I have developed are what I refer to as deliberately agnostic of the type of task being performed. However, it's not all that easy to apply the definition to all kinds of tasks given that in many we haven't got good operationalisations of $\ C_{A}$ and $\ D_{A}$. Sure, for tasks typical to my alma mater of research, resistance training, it's pretty simple. Take a physical task such as this, in essence lifting a weight... here's how I gave an example of the definition in play:

>"In a physical task the role of differential demands and capacity are easily considered in that actual effort is determined by the task demands relative to the current capacity to meet task demands. As such, if two individuals were attempting to pick up the same specific absolute load (e.g. 80 kg) the stronger of the two would initially require less actual effort to complete this task. If they had both performed prior tasks that had resulted in a reduction in their maximal strength, then each would require a greater actual effort to complete the task than compared with when their capacity was not reduced. And further, if both continued performing repetitions of this task their maximal strength might continue to reduce insidious to continued attempts to maintain a particular absolute demand, and thus require an increasingly greater actual effort with every individual or continued attempt to meet the task demands. Correspondingly, if the absolute task demands were increased then both individuals would also require greater actual effort to complete the task. Yet for both, the continued attempted performance of the task with fixed absolute demands and insidious reduction of capacity or the increase of absolute demands, task performance would be capped by their maximum capacity at which maximum effort is required. With training though that maximum strength might be increased such that a given absolute task demand now represents relatively less and so requires less actual effort. Further, biomechanical alterations to the task might reduce the absolute demands and thus the actual effort."

So, let's say an individual did try to lift a load that was 80 kg. And let's say that the maximum load they could lift was 100 kg. Well, it's pretty simple to calculate the actual effort required:

$$\ D_{A} = 80, C_{A} = 100$$
$$\ E_{A} = \frac{ 
D_{A}}
{C_{A}} \times 100%$$
$$\ 80 = \frac{ 
80}
{100} \times 100$$

So, the amount of actual effort required to lift the load is 80%. Nice and simple. 

But what about cognitive tasks? Sure, we can conceivably apply my definition to such tasks is we assume that tasks have demands, and that we have some capacity to meet them. In fact, we could draw similar examples as above for such tasks... again, here's what I note:

>"Similar examples could be provided for cognitive tasks. For example, if two individuals were attempting to hold a fixed number of items in their working memory, the one who has the larger working memory of the two would require less actual effort to complete this task. However, both individuals would again require greater actual effort to do so in the presence of lingering reduction in cognitive capacity from prior tasks, or from continued attempts to meet the task demands, or from increased absolute task demands (i.e., more items to be held in working memory). Again, training may also improve maximal capacity. Also, cognitive processing alterations (i.e., heuristics; Shah and Oppenheimer, 2008) might reduce task demands and thus the actual effort."

The problem however, is actually measuring the capacity being used to perform cognitive tasks, and the demands of those tasks. We have an operationalisation problem. 

```{r cars}
summary(cars)
```


```code snippet
```

```{r general_options, cache=FALSE}
library(dplyr)
library(tidyr)
library(tibble)
library(stringr)
library(ggplot2)
library(GGally)
library(mirt)
library(brms)
cores <- 4
iter <- 3000
warmup <- 1000
control <- list(adapt_delta = 0.95)
options(width = 160)
theme_set(theme_default())
```

[^1]: Markus, K. A. (2008). Constructs, concepts and the worlds of possibility: Connecting the measurement, manipulation, and meaning of variables. Measurement: Interdisciplinary Research and Perspectives, 6(1-2), 54–77. https://doi.org/10.1080/15366360802035513
[^2]: Though, not too many attempts so as to avoid any potential cumulative fatigue impacting the estimation of their 'true' maximum. Normally it's between 3-5 attempts after a warmup at a knowingly submaximal load.
