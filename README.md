# Smart-campus-helpdesk-mini-project-2
Smart Campus Helpdesk – Django REST API
Project Overview----------------------------
Smart Campus Helpdesk is a Django REST Framework based backend project developed to manage campus complaint tickets efficiently.
It allows authenticated users to create, view, update, delete, and manage complaint tickets with features like filtering, searching, ordering, pagination, JWT authentication, and caching.

Features Implemented---------------------------
✅ Django project & app setup
✅ PostgreSQL database integration
✅ Ticket model with proper fields
✅ CRUD APIs for tickets
✅ JWT-based authentication
✅ Admin login (Session Authentication)
✅ Pagination for ticket listing
✅ Filtering by category and status
✅ Ordering by priority and created date
✅ Search by title and description
✅ Redis / Local Memory Caching

Tech Stack-----------------
Python
Django
Django REST Framework
PostgreSQL
JWT (SimpleJWT)
Redis / LocMem Cache
django-filter

smart_campus/--------------
│
├── manage.py
├── smart_campus/
│   ├── settings.py
│   ├── urls.py
│
├── tickets/
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   ├── urls.py

Ticket Model Fields---------------
id (Auto)
title
description
category (classroom / hostel / network)
priority (low / medium / high)
status (open / in_progress / closed)
created_at
updated_at

Key Concepts Used------------------
Function Based Views
ModelSerializer
Query Parameters Handling
Q Objects for search
JWT Authentication
Pagination using PageNumberPagination
Cache Integration
RESTful API Design

Learning Outcomes------------------------------------
Built complete REST API using Django REST Framework
Implemented secure authentication using JWT
Integrated PostgreSQL database
Applied filtering, searching, ordering, pagination
Implemented caching for performance optimization
Understood API request-response lifecycle
