---
title: "Empowering Collaborative Data Workflows with Airflow and Cloud Services"
slug: empowering-collaborative-data-workflows-with-airflow-and-cloud-services
speakers:
 - Stanisław Smyl
 - Hoa Nguyen
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
---

Productive cross-team collaboration between data engineers and analysts is the goal of all data teams, however, fulfilling on that mission can be challenging given the diverse set of skills that each group brings. In this talk we present an example of how one team tackled this topic by creating a flexible, dynamic and extensible framework using Airflow and cloud services that allowed engineers and analysts to jointly create data-centric micro-services to serve up projections and other robust analysis for use in the organization. The framework, which utilized dynamic DAG generation configured using yaml files, Kubernetes jobs and dbt transformations, abstracted away many of the details associated with workflow orchestration, allowing analysts to focus on their Python or R code and data processing logic while enabling data engineers to monitor the pipelines and ensure their scalability.