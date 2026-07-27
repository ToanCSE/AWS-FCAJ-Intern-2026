---
title: "Worklog Week 5"
date: 2026-07-24
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:
* Integrate application logging with AWS CloudWatch Logs.
* Configure metric filters & alarms monitoring EC2 CPU usage and system events.

### Tasks Executed:
| Day | Task | Start Date | End Date |
| --- | --- | --- | --- |
| Mon | - Research AWS CloudWatch Logs SDK (`watchtower`) integration | 13/07/2026 | 13/07/2026 |
| Tue | - Add `watchtower` package and update `backend/services/logging_service.py` | 14/07/2026 | 15/07/2026 |
| Thu | - Configure log streaming for Face ID attempts, auth, and DB events to CloudWatch Log Group `/fav-web/backend` | 16/07/2026 | 17/07/2026 |
| Sat | - Provision CloudWatch Alarms triggering alerts when EC2 CPU utilization exceeds 80% threshold | 18/07/2026 | 19/07/2026 |

### Week 5 Achievements:
* Real-time application log streaming from EC2 to AWS CloudWatch Logs operational.
* Automated CPU utilization alerts and system monitoring in place.

![AWS CloudWatch Logging & Monitoring](/images/cloudwatch.png)
