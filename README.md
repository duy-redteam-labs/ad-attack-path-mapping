# AD Attack Path Mapping (Safe, Logic-Based)

## Overview
Model privilege relationships in the AD lab as a graph:
- User/Group memberships
- Permissions (share/local admin where applicable)
- Identify shortest privilege paths (logic only)
- Produce prioritized hardening checklist

## Scope (Lab-only)
Uses data from your own AD lab only.

## Tech Stack
- Export scripts (PowerShell)
- Graph: Graphviz (.dot) or similar

## Deliverables
- Graph files + rendered images: docs/diagrams/
- Write-up: docs/reports/
- Hardening checklist: docs/reports/

## Status
- [ ] Data export
- [ ] Graph generation
- [ ] Path analysis
- [ ] Hardening checklist
