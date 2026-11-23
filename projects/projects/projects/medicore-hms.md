# MediCore Healthcare SaaS

**Stack:** Django REST Framework, PostgreSQL, React, WhatsApp Business API

## Problem
Hospitals, clinics, and pathology labs needed connected workflows for patient records, appointments, lab orders, reports, and reminders.

## My contribution
- Built DRF APIs and PostgreSQL models for the core healthcare workflows.
- Applied tenant isolation and role-based permissions for different healthcare personnel.
- Integrated WhatsApp and SMS workflows for report delivery and appointment reminders.
- Contributed to a React operational interface.

## Outcome
The application brought patient, appointment, and lab workflow capabilities into a multi-tenant product. No patient data, internal code, or unverified usage metrics are published here.

## Design considerations
- Scope data access by tenant and role in API operations.
- Validate inputs for patient and lab workflows.
- Keep communication integrations separate from core records and permission logic.

This is a high-level case study of professional work; the production repository is private.
