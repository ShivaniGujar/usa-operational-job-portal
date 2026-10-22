# 01 - Project Overview

## 1. Purpose
Build a full-stack web application for planning, assigning, monitoring,
and reporting operational jobs.

## 2. Business problem
The source apprenticeship report identifies challenges including
fragmented job tracking, manual planning errors, limited status visibility,
coordination difficulties, and historical reporting needs.

## 3. Project objectives
- Centralize operational units and job records.
- Support draft creation and controlled plan activation.
- Track execution progress and hindrances.
- Provide searchable operational reports.
- Apply secure access control and automated testing.

## 4. Proposed users
- Administrator: manages reference data and access.
- Planner: creates and activates job plans.
- Supervisor: monitors assigned work and hindrances.
- Viewer: reads permitted dashboards and reports.

These roles are proposed for this new implementation and will be
validated as requirements are developed.

## 5. Technology decisions
- React + TypeScript + Vite for the frontend.
- Java 21 + Spring Boot for the backend.
- MySQL for persistent relational data.
- Spring Data JPA and Flyway for persistence and migrations.
- GitHub for source control and collaboration.

## 6. Initial scope
Units, departments, users, jobs, drafts, plan activation, execution
tracking, hindrances, reporting, authentication, and tests.

## 7. Delivery deadline
30 October 2026.

## 8. Development approach
Build in small increments, test changes, document decisions, and commit
working progress to GitHub daily.
