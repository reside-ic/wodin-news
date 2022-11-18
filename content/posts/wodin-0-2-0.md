---
title: "Lots of small interface tweaks"
date: 2022-11-17T17:10:12Z
version: ["wodin v0.2.0"]
tags: ["Update"]
---

While working towards getting stochastic models running, we've made a number of relatively smaller interface improvements that smooth over a number of rough edges.

* Sum of squares is now shown in the Run tab if you have a "fitting" app and it is possible to compute it
* All plots have x axis labels; these show Time for plots over time, and the parameter being varied in the other sensitivity plots
* Sensitivity will not lock up the browser as badly if the model run is slow, and will display progressively as it computes each iteration
* Long labels are not truncated, particularly in the sensitivity plots
* It is possible to display plots with a log-y axis (this setting will be automatically shared across all plot types and saved with the session)
* A slightly nicer workflow for creating a new session based on the contents of your current saved session
