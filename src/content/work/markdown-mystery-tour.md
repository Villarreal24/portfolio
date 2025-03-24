---
title: Grupo Guia
publishDate: 2023-01-01 00:00:00
img: /assets/project-1.png
img_alt: Grupo Guia Alt
description: |
  We create a platform for the own company to sell apartments online!
tags:
  - Design
  - Development
  - Microservices
  - Testing
---

## Website and Infrastructure

> Project overview

I worked on a major project with a team of 5: 3 Fullstack developers (including me), 1 designer, and 1 project manager. The project was for a real estate company and covered all aspects of their business. Users can view properties for sale or rent, including new apartment buildings in pre-sale across multiple cities, not just Guadalajara.

The apartment buildings section is a key part of the project. Initially, users could only view buildings and request more information. Recently, we added a feature to reserve apartments online. Now, users can explore buildings, compare available units, and complete the entire process—including documentation, contracts, and payments—online.

### ERP System

I helped implement an ERP system for the company. This platform manages all market data and connects with other platforms like Wiggot using APIs and n8n. It includes modules for calculating commissions, evaluating investment profitability, and managing products related to real estate activities.

### Technical Implementations

- Frontend: Used Next.js (React.js) v16+ for better performance and SEO. Implemented server-side rendering (SSR) for specific pages to improve SEO.

- Backend: Built a custom API with Nest.js using microservices to support all company projects and websites.

- Database: Used PostgreSQL for data storage.

- Frontend Modules: Developed customer-facing and admin modules to streamline online data processing.

- Authentication: Implemented Single Sign-On (SSO) with Keycloak and managed user roles for permissions.

- CRM Integration: Connected the website with HubSpot CRM to manage leads and customer data effectively.

- Workflow Automation: Used n8n to connect APIs and services, ensuring smooth data transfer and accurate tracking.

- Storage: Stored documents, contracts, and photos in Amazon S3 buckets. Used .webp format for images to optimize loading times.

- Landing Pages: Created multiple landing pages in React.js for real estate developers, focusing on UX. Integrated tools like Google Analytics, Facebook Pixel, and Hotjar.

- Infrastructure: Used Amazon tools like Route 53, EC2, and ECS to manage projects securely and ensure smooth operation.

- API Connections: Connected to the Wiggot API via Nest.js microservices and n8n workflows for data exchange.

- Performance Optimization: Used server-side rendering (SSR) in Next.js for specific requests and tools like Redux Persist with memo and callback functions to cache data.
