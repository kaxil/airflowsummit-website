---
title: "Scaling Airflow for Data Productivity at Instacart"
slug: scaling-airflow-for-data-productivity-at-instacart
speakers:
 - Anant Agarwal
track:
 - Use cases
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

In this talk, we'll discuss how Instacart leverages Apache Airflow to orchestrate a vast network of data pipelines, powering both our core infrastructure and dbt deployments. As a data-driven company, Airflow plays a critical role in enabling us to execute large and intricate pipelines securely, compliantly, and at scale.

We'll delve into the following key areas:

a. High-Throughput Cluster Management: We'll explore how we manage and maintain our Airflow cluster, ensuring the efficient execution of over 2,000 DAGs across diverse use cases.

b. Centralized Airflow Vision: We'll outline our plans for establishing a company-wide, centralized Airflow cluster, consolidating all Airflow instances at Instacart.

c. Custom Airflow Tooling: We'll showcase the custom tooling we've developed to manage YML-based DAGs, execute DAGs on external ECS workers, leverage Terraform for cluster deployment, and implement robust cluster monitoring at scale.

By sharing our extensive experience with Airflow, we aim to contribute valuable insights to the Airflow community.