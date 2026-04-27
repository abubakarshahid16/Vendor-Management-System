# Vendor Management System

A procurement-focused web project for managing vendors, contracts, purchase orders, and departmental budget visibility.

This repository is positioned as a **vendor-governance and procurement workflow system** rather than a generic CRUD exercise.

## Problem this project solves

Organizations that work with many vendors often struggle with:

- scattered vendor records
- poor visibility into contract status
- disconnected purchase-order tracking
- weak budget awareness across departments
- inconsistent procurement processes

This project addresses that by organizing vendor operations into a structured system with clear business entities and workflow pages.

## What this project does

The system is designed around:

- vendor registration and profile management
- contract lifecycle tracking
- purchase-order handling
- department budget visibility
- database-level integrity through triggers and stored procedures

## Live demo

- GitHub Pages demo: <https://abubakarshahid16.github.io/Vendor-Management-System/>

## Visual preview

![Vendor dashboard preview](docs/screenshots/dashboard-preview.png)

![Vendor registration preview](docs/screenshots/registration-preview.png)

## Main functional areas

- **Vendor management**: store vendor identity, contact, and profile data
- **Contract management**: track contract timing and status
- **Purchase order tracking**: connect vendors with purchasing activity
- **Budget visibility**: expose department-level allocation and usage
- **Data integrity support**: use database logic for consistency and validation

## Tech context

The repository contents indicate a stack centered on:

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js and Express
- Database: MySQL
- Database logic: triggers and stored procedures

## Repository contents

- interface HTML pages for core workflows
- a system/database diagram in Draw.io format
- a written project report
- a presentation deck

Representative files:

- `homepage.html`
- `contract.html`
- `purchase_order.html`
- `performance_evaluation.html`
- `VENDOR_REGISTRATION_FORM.HTML`
- `db_project (1).drawio`
- `Detailed Project Report (2).docx`

## Why this project matters

- It demonstrates business-process modeling for procurement operations.
- It shows database-oriented system design rather than only UI work.
- It reflects workflow thinking across vendors, contracts, budgets, and orders.
- It is useful as a portfolio piece for business applications and information systems.

## Industrial positioning

A stronger production-style version would likely add:

- structured backend source organization
- complete database schema and migration files
- authentication and role-based access
- audit trails for procurement actions
- deployment documentation
- workflow approvals and notifications

This means the repo is best positioned as a **procurement system design and application prototype** with solid business-domain relevance.
