# IoT Hub Audit Service

Centralized audit service for collecting, storing, and querying important system events across IoT Hub.

## Purpose

The Audit Service provides a centralized audit trail for important platform events.

## Responsibilities

- consume audit events from platform services
- persist normalized audit records
- provide audit search and filtering capabilities
- expose audit history to administrative users
- support system traceability and debugging

## Owned data

- audit records
- audit metadata
- searchable audit history

## Integrations

### Inbound
- audit-producing services across the platform

### Outbound
- administrative and diagnostic audit APIs

## Technology

- Django
- PostgreSQL
- Docker
