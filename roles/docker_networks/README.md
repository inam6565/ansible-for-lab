# Docker networks role documentation

# docker_networks role

Purpose:
- Create persistent Docker networks for Phase 0 lab

Networks:
- ci_net
- registry_net
- app_net

Guarantees:
- Networks exist
- Subnets are predictable
- Idempotent behavior
