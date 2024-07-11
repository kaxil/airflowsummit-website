---
title: "Airflow at Ford: A Job Router Training Advance Driver Assistance Systems"
slug: airflow-at-ford-a-job-router-training-advance-driver-assistance-systems
speakers:
 - Serjesh Sharma
 - Vasantha Kosuri-Marshall
track:
 - Use cases
images:
 - /images/sessions/2024/ford-driver-assistance.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Ford Motor Company operates extensively across various nations. The Data Operations (DataOps) team for Advanced Driver Assistance Systems (ADAS) at Ford is tasked with the processing of terabyte-scale daily data from lidar, radar, and video. To manage this, the DataOps team is challenged with orchestrating diverse, compute-intensive pipelines across both on-premises infrastructure and the GCP and deal with sensitive of customer data across both environments The team is also responsible for facilitating the execution of on-demand, compute-intensive algorithms at scale through. To achieve these objectives, the team employs Astronomer/Airflow at the core of its strategic approach. This involves various deployments of Astronomer/Airflow that integrate seamlessly and securely (via Apigee) to initiate batch data processing and ML jobs on the cloud, as well as compute-intensive computer vision tasks on-premises, with essential alerting provided through the ELK stack. This presentation will delve into the architecture and strategic planning surrounding the hybrid batch router, highlighting its pivotal role in promoting rapid innovation and scalability in the development of ADAS features.