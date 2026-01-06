# Lab directories role documentation

# lab_directories role

Purpose:
- Create consistent filesystem layout for Phase 0 lab

Creates:
- /opt/devops-lab
- Service subdirectories (jenkins-vm, registry-vm, app-runtime-vm, docs)

Guarantees:
- Directories exist
- Correct ownership
- Idempotent behavior
