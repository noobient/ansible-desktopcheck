# bviktor.desktopcheck

## Synopsys

This role determines if the host is a desktop system.

## Parameters

N/A

## Examples

```yml
- include_role:
    name: bviktor.desktopcheck
```

## Return Values

| Key | Type | Example | Description |
|---|---|---|---|
| `target_is_desktop` | boolean | `true` | Indicates if the host is a desktop or not. |

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/lint.yml) |
| AlmaLinux 8 | ❌ | N/A |
| AlmaLinux 9 | ❌ | N/A |
| Fedora 37 | ❌ | N/A |
| Ubuntu 18.04 | ✅ | [![Ubuntu 18.04](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-18.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-18.04.yml) |
| Ubuntu 20.04 | ✅ | [![Ubuntu 20.04](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-20.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-20.04.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-22.04.yml) |
