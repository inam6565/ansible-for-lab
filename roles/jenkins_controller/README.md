# Jenkins controller role documentation

# jenkins_controller role

Purpose:
- Deploy Jenkins controller as Docker container

Guarantees:
- Persistent Jenkins data
- Correct UID/GID mapping
- Attached to ci_net
- Restart-safe

Out of scope:
- Pipelines
- Plugins
- Docker socket access
