---
title: "Pedestrians & Bicycles"
weight: 5
description: >
  This page presents non-motorized performance metrics.
---

### Volume

{{% plotly_bar id="myChart2" csvfile="content/docs/bike_volumes.csv" title="Bicycle Volumes" style="style2"%}}

* SFCTA collects multimodal counts at key locations
* Between 2019 and 2021, bicycle counts reduced significantly by about 30% and 50% during AM and PM peaks respectively

{{% plotly_bar id="myChart1" csvfile="content/docs/ped_volumes.csv" title="Pedestrian Volumes" style="style2"%}}

* Between 2019 and 2021, pedestrain counts reduced by about 70% across AM and PM peaks periods


### Safety

{{% plotly_bar id="myChart3" csvfile="content/docs/bikeped_fatalities.csv" title="Pedestrian and Bicycle Fatalities" bmode="stack"%}}

* Safety for pedestrians and cyclists are key measures of non-motorized transportation performance, and a critical policy priority for the city of San Francisco
* The City and County of San Francisco adopted Vision Zero as a policy in 2014, committing to build better and safer streets, educate the public on traffic safety, enforce traffic laws, and adopt policy changes that save lives
* While pedestrian fatalities decreased between 2019 and 2020, there was an increase in bicycle fatalities in the same period
* Overall, the total non-motorized fatalities were lower in 2020 than 2018 and 2019

{{< tip >}}
Explore a dynamic map of bicycle and pedestrian safety data.
{{< /tip >}}

<div id="wrap">
    <iframe id="scaled-frame" src="https://safety.sfcta.org/"></iframe>
</div>