# IT Security Incident & SLA Performance Dashboard

Analysis of IT security incident severity, SLA compliance, and resolution time across detection sources and response teams

**Live Dashboard:** https://public.tableau.com/app/profile/deep.kaur7386/viz/ITSecurityIncidentSLAPerformanceDashboard/ITSecurityIncidentSLAPerformanceDashboard

## Overview
Analysis of 3,000 IT security incident records covering severity classification, 
SLA compliance, resolution time, and workload distribution across five response teams 
(IAM Team, Incident Response Team, Network Security, Tier 1 SOC, Tier 2 SOC).

## Key Findings
- **Severity Distribution:** The majority of incidents are Low (1,180) or Medium (1,055) 
  severity, with Critical incidents making up a small but high-impact share (201, ~7%).
- **SLA Compliance:** SLA compliance drops sharply as severity increases — Critical 
  incidents met their SLA target only ~2% of the time and High incidents ~9%, compared 
  to ~95-97% for Medium and Low severity incidents, highlighting the operational challenge 
  of meeting tight response windows on the highest-impact events.
- **Resolution Time:** Average resolution time is consistent across incident types 
  (10.4-11.4 hours), with Privileged Account Misuse and Data Exfiltration Attempts taking 
  slightly longer due to the depth of investigation required.
- **Team Workload:** Incident volume is evenly distributed across the five response teams 
  (561-628 incidents each), indicating balanced staffing allocation.

## Tools Used
Excel (pivot tables, data exploration), Tableau Public (dashboard visualization)

## Data Source
Synthetic IT security incident dataset modeled on real-world SOC/incident management workflows
