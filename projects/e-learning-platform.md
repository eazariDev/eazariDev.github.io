---
layout: project
type: project
image: img/e-learning-platform/log.png
title: "E-learning-platform"
date: 2025
published: true
labels:
  - Python
  - Django
  - Redis
  - Docker
summary: "A modern, scalable, and extensible web-based e-learning platform built with Django."
---
<div align="center">

<img class="img-fluid" src="../img/e-learning-platform/log.png" width="30%" style="position: relative; top: 0; right: 0;" alt="Project Logo"/>
</div>

## Overview

E-learning platform is a modern, scalable, and extensible web-based e-learning platform built with Django, Django REST Framework, Channels, and Docker. It supports course creation, student enrollment, real-time chat, and secure media handling—all containerized for seamless deployment.

## Features

- 🧑‍🏫 Instructor & student workflows
- 🧵 Real-time chat using Django Channels + Redis
- 🎓 Course creation, enrollment, and progress tracking
- 🖼️ Media uploads and secure content access
- 🧱 Modular Django apps (courses, students, chat)
- 🐳 Full Dockerized setup with Nginx, PostgreSQL, Redis
- ⚙️ ASGI + Daphne for async support

|     | Component         | Details                                                                                                                            |
| :-- | :---------------- | :--------------------------------------------------------------------------------------------------------------------------------- |
| ⚙️  | **Architecture**  | <ul><li>Monolithic Django backend</li><li>ASGI with Channels</li><li>PostgreSQL + Redis</li><li>nginx reverse proxy</li></ul>      |
| 🔩  | **Code Quality**  | <ul><li>Modular Django apps</li><li>Good use of settings structure</li><li>Consistent dependency versions</li></ul>                |
| 🔌  | **Integrations**  | <ul><li>PostgreSQL</li><li>Redis (caching + Channels)</li><li>nginx</li><li>daphne</li></ul>                                       |
| 🧩  | **Modularity**    | <ul><li>Separate Django apps: courses, students, chat</li><li>Logical separation of static/media/configs</li></ul>                 |
| ⚡️  | **Performance**   | <ul><li>Redis caching layer</li><li>uwsgi for WSGI</li><li>daphne for ASGI</li></ul>                                               |
| 🛡️ | **Security**      | <ul><li>Environment-based secrets via `python-decouple`</li><li>nginx SSL config present</li><li>Prod config in settings</li></ul> |
| 📦  | **Dependencies**  | <ul><li>Django 5.0.4</li><li>Channels</li><li>DRF</li><li>Redis</li><li>Pillow</li></ul>                                           |
| 🚀  | **Scalability**   | <ul><li>Containerized via Docker</li><li>ASGI for real-time features</li><li>Decoupled db/cache services</li></ul>                 |


Source: <a href="https://github.com/eazariDev/e-learning-platform">eazariDev/e-learning-platform</a>
