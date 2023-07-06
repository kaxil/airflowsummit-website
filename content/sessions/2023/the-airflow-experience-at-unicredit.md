---
title: "The Airflow experience at UniCredit"
slug: the-airflow-experience-at-unicredit
speakers:
 - Jan Pawłowski
 - Jędrzej Matuszak
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
track: Use cases
---

Representing the Murex Reporting team at UniCredit we would like to present our journey with Airflow, and how over the past two years it enabled us to automate and simplify our batch workflows. Comparing to our previous rigid mainframe scheduling approach, we have created a robust and scalable framework complete with a CI/CD process, bringing our time to market of scheduling changes down from 3 days to 1. Basing our solution on DAG networks joined by ExternalDagSensors and an array of custom-built plugins (such as static time predecessors or external task sensors) we were able to replicate the scheduling of our overnight ETL processes (consisting of approx. 8000 tasks with many-to-many dependencies) in Airflow, satisfying our bank reporting SLAs without performance regression while gaining massively improved process visibility and control. Our presentation will illustrate our journey and explore some of these customizations, which venture outside of Airflow's core functionalities.