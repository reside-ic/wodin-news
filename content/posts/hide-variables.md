---
title: "Hide Variables"
date: 2022-12-09T09:35:28Z
version: ["wodin v0.3.0"]
tags: ["Feature"]
---

If you're working on a complex model there are often variables that need to exist in the model that are needed to solve your model, but are not that interesting. Worse - sometimes these variables make your graph unreadable because they're on a really different scale (e.g., the number of susceptible individuals in a disease that never reaches a very high level in a population).

As of wodin 0.3.0, you can now select variables to show from below the editor, on the Code tab:

{{< image
src="/wodin-news/img/hide-variables-select.gif"
alt="Animation showing hiding variables in Wodin" >}}

Deselecting variables here will hide them from the plots -- even from being shown in the legend -- as well as from downloaded data and from being selected as candidates for fitting.  You can reselect the variables at any time and they will reappear immediately, so you can use this feature to declutter your plots to focus just on the things you care about at the moment.

{{< image
src="/wodin-news/img/hide-variables-run.gif"
alt="Animation showing running model with hidden variables" >}}
