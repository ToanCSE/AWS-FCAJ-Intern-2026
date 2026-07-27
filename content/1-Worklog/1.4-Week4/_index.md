---
title: "Worklog Week 4"
date: 2026-07-24
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:
* Provision and connect AWS RDS PostgreSQL database (Free Tier).
* Configure Security Group rules linking EC2 Backend to RDS PostgreSQL.
* Update SQLAlchemy `DATABASE_URL` config to dynamically support both local SQLite and Cloud RDS.
* Run initial database migrations and seed default admin user (`admin` / `123456`).

### Tasks Executed:
| Day | Task | Start Date | End Date |
| --- | --- | --- | --- |
| Mon | - Launch AWS RDS PostgreSQL Database Instance via AWS Console | 06/07/2026 | 06/07/2026 |
| Tue | - Configure RDS Security Group Inbound Rule allowing Port 5432 strictly from EC2 IP | 07/07/2026 | 07/07/2026 |
| Wed | - Add `psycopg2-binary` driver to `backend/requirements.txt` | 08/07/2026 | 08/07/2026 |
| Thu | - Refactor `backend/services/db_models.py` to parse `DATABASE_URL` dynamically | 09/07/2026 | 10/07/2026 |
| Sat | - Test automatic schema creation and default admin seeding upon container startup | 11/07/2026 | 12/07/2026 |

### Week 4 Achievements:
* EC2 Backend successfully connected to AWS RDS PostgreSQL.
* Production data (Users, Posts, Knowledge, Games, Music, Logs) securely persisted on RDS.

![Streaming Music Library Module](/images/music.png)
![Gaming Hub Module](/images/games.png)
![Multimedia Social Feed Module](/images/feed.png)
