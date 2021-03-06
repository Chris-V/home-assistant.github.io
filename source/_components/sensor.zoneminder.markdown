---
layout: page
title: "ZoneMinder Sensor"
description: "Instructions how to integrate ZoneMinder sensors within Home Assistant."
date: 2016-10-13 22:57
sidebar: true
comments: false
sharing: true
footer: true
logo: zoneminder.png
ha_category: Sensor
---


The `ZoneMinder` sensor platform let you monitor the current state of your zoneminder install including the number of events and the current state of the cameras.

<p class='note'>
You must have the [ZoneMinder component](/components/zoneminder/) configured to use those sensors.
</p>

To set it up, add the following information to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
sensor:
  platform: zoneminder
```