---
title: "Auto"
weight: 3
description: >
  This page presents roadway and automobile performance metrics.
---

### Speed

{{% plotly_line id="myChart1" csvfile="content/docs/auto_speed.csv" title="CMP Network Average Auto Speed" %}}

* This represents the first time in the past decade when overall average roadway speeds have improved between CMP updates
* Average arterial travel speeds have increased 33% in the AM peak and increased 36% in the PM peak
* On freeways the increases were 46% and 42% in AM and PM peak respectively
* The overall increases in speeds are a reversal in the trend of declining roadway performance observed during most part of this decade

### Level of Service




### Reliability

{{% plotly_line id="myChart2" csvfile="content/docs/auto_reliability.csv" title="CMP Network Average Auto Reliability (BTI)" tf="tf2" %}}

* A new metric for measuring roadway reliability is introduced in this CMP update called the Buffer Time Index (BTI)
* This is calculated as the amount of extra travel time (expressed as a percent of average travel time) that the travelers need to additionally budget so that they have a 95% chance of arriving on time
* Like auto speed, reliability has improved significantly from 2019 to 2021
* Note that a lower value of BTI indicates higher reliability

