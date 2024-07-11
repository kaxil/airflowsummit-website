---
title: "Weathering the Cloud Storms With Multi-Region Airflow Workflows"
slug: weathering-the-cloud-storms-with-multi-region-airflow-workflows
speakers:
 - Amit Chauhan
track:
 - Airflow & ...
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Cloud availability zones and regions are not immune to outages. These zones regularly go down, and regions become unavailable due to natural disasters or human-caused incidents. Thus, if an availability zone or region goes down, so do your Airflow workflows and applications… unless your Airflow workflows function across multiple geographic locations.

This hands-on session introduces you to the design patterns of multi-region Airflow workflows in the cloud, which can tolerate zone and region-level incidents. We will start with a traditional single-region configuration and then switch to a multi-region setting. By the end, we'll have a working prototype of a multi-region Airflow pipeline that recovers from region-level outages within a few seconds, with no data loss or disruption to the application layer.