---
title: "Worklog Week 6"
date: 2026-07-24
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:
* Optimize AI Face Recognition API performance using RAM embedding caching.
* Upgrade dual authentication architecture (HttpOnly Cookie + Bearer Token Header Fallback).
* Standardize CORS Whitelist & Content Security Policy (CSP).

### Tasks Executed:
| Day | Task | Start Date | End Date |
| --- | --- | --- | --- |
| Mon | - Implement `load_embeddings_into_cache()` in `backend/ai_core/src/recognizer.py` pre-loading face vectors into RAM at startup | 20/07/2026 | 20/07/2026 |
| Tue | - Return `token` in `/auth/login` payload and attach `Authorization: Bearer <token>` in `frontend/src/services/api.js` | 21/07/2026 | 21/07/2026 |
| Wed | - Relax `connect-src` in `frontend/index.html` & `backend/middleware/csp.py` to support cross-domain API calls | 22/07/2026 | 22/07/2026 |
| Thu | - Add S3 static website origin to `DEV_ORIGINS` CORS whitelist in `backend/main.py` | 23/07/2026 | 23/07/2026 |
| Fri | - Optimize Vite frontend bundling with `manualChunks` in `vite.config.js` reducing main bundle size to 133 kB | 24/07/2026 | 26/07/2026 |

### Week 6 Achievements:
* Face ID recognition API response times significantly improved via RAM caching.
* Cross-domain authentication issues between S3 Frontend and EC2 Backend fully resolved.
* Vite build optimization and bundle chunking achieved.
