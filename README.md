# Ansible Role: cmk_agent

Ansible role for check mk agent installations

## Role Variables

For available variables see `defaults/main.yml`
```yaml
cmk_agent_cmkserver: cmk.dns.suffix
cmk_agent_site: cmk
cmk_agent_automation_pwd: create_password_in_cmk-ui_for_automation_user
cmk_agent_hostprefix: customerA # prefix all cmk-hosts with a prefix
```

## Notes

Currently supported base distributions:
- Debian