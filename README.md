# noobient.desktopcheck

## Synopsys

This role determines if the host is a desktop system.

## Parameters

N/A

## Examples

```yml
- include_role:
    name: noobient.desktopcheck
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
| Fedora 40 | ❌ | N/A |
| Fedora 41 | ❌ | N/A |
| Ubuntu 20.04 | ✅ | [![Ubuntu 20.04](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-20.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-20.04.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-desktopcheck/actions/workflows/ubuntu-22.04.yml) |
| Ubuntu 24.04 | ✅ | [![Ubuntu 24.04](https://github.com/noobient/ansible-galaxy-thirdparty/actions/workflows/ubuntu-24.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-thirdparty/actions/workflows/ubuntu-24.04.yml) |
