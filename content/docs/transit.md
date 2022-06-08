---
title: "Transit"
weight: 4
description: >
  This page presents transit performance metrics.
---

### Speed

{{% plotly_line id="myChart1" csvfile="content/docs/transit_speed.csv" title="CMP Network Average Transit Speed" %}}

* Compared to 2019, the average transit speed (collected for buses only) in 2021 increased 15% in the AM Peak and 24% in the PM Peak
* Like roadway speeds, most of the increase in transit speeds may be attributable to overall lower levels of demand
* Improved transit speeds may be attributable also to increased deployment of transit priority lanes, and to less delay resulting from fewer boardings and alightings, during COVID-19

### Reliability

{{% plotly_line id="myChart2" csvfile="content/docs/transit_reliability.csv" title="CMP Network Average Transit Reliability (CV)" tf="tf2" %}}

* Transit travel time reliability is measured in terms of transit speed variability as the coefficient of variation (CV)
* Reliability has worsened (variability has increased) since 2019 despite improvements in average transit speed
* While transit was slightly less reliable in 2021, the overall improvements in transit speeds far offset this effect

### Auto-Transit Speed Ratio

{{% plotly_line id="myChart3" csvfile="content/docs/transit_ratio.csv" title="CMP Network Auto-Transit Speed Ratio" %}}

* The ratio of auto to transit speeds is calculated to assess the competitiveness of transit with driving
* A ratio of 2 would indicate that, for a particular segment, on-board transit travel time is twice that of auto travel time
* The average auto-transit speed ratio increased between 2019 and 2021
* Both average auto and transit speeds improved this year but auto speeds improved more than transit speeds which resulted in transit being less competitive relative to auto
