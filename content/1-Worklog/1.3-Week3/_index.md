---
title: "Worklog Week 3"
date: 2026-07-24
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:
* Provision EC2 Instance & Security Groups on AWS Console.
* Deploy Backend FastAPI Docker Container on EC2.
* Integrate AWS S3 Storage for raw images, log captures & vector embeddings via `boto3`.
* Deploy Frontend React/Vite to AWS S3 Static Website Hosting.

### Tasks Executed:
| Day | Task | Start Date | End Date |
| --- | --- | --- | --- |
| Mon | - Provision AWS S3 Buckets for media & static web hosting <br> - Integrate `boto3` SDK in `backend/services/s3_service.py` | 29/06/2026 | 30/06/2026 |
| Wed | - Update face enrollment and webcam log photo upload pipeline to write directly to S3 | 01/07/2026 | 01/07/2026 |
| Thu | - Launch Ubuntu EC2 Instance & configure Inbound Security Group rules (Ports 80/8000/22) | 02/07/2026 | 02/07/2026 |
| Fri | - SSH into EC2, build Docker image, and run `fav-web-backend` container with volume mounts | 03/07/2026 | 04/07/2026 |
| Sat | - Run `npm run build` targeting EC2 IP & upload static assets to S3 Website Hosting | 05/07/2026 | 05/07/2026 |

### Week 3 Achievements:
* FastAPI Backend running live on AWS EC2 (`http://52.63.251.110`).
* React Frontend live on AWS S3 Static Website Hosting.
* Automatic media uploads & face embeddings persisted to AWS S3.

![AWS EC2 Instance Management](/images/ec2.png)
![AWS S3 Storage Buckets](/images/s3.png)
