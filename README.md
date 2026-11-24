# Company CI Jobs

## Purpose

This repository contains reusable CI job definitions
and their Ansible implementations.

## Responsibilities

- Company-wide reusable CI jobs.
- Code quality scanning.
- Security scanning.
- Technology-specific build jobs.
- Reusable Ansible playbooks and roles.

## Configuration Ownership

This repository is maintained by the Platform Engineering team.

Application teams consume the jobs but do not own their
central implementations.

## Zuul Integration

This repository is intended to be registered as an
untrusted project with restricted configuration loading.

Only approved job definitions will be loaded.

## Related Repositories

- company-zuul-config
- payment-service
