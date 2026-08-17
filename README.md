# example.com lab

Tiny playground to compare **Cursor Origin** (`origin` CLI) vs **GitHub** (`gh` CLI).

This is not a real site — just IANA's reserved `example.com` as a dummy domain.

| Host | Repo | Clone |
| --- | --- | --- |
| Origin | `tomcoustols/example-com-lab` | `https://origin.cursor.com/tomcoustols/example-com-lab.git` |
| GitHub | `lawmight/example-com-lab` | `https://github.com/lawmight/example-com-lab.git` |

## Why example.com?

[RFC 2606](https://www.rfc-editor.org/rfc/rfc2606) reserves `example.com` for documentation. Safe dummy, no accidental production DNS.

## CLI smoke test

```bash
origin repo view tomcoustols/example-com-lab
gh repo view lawmight/example-com-lab
```
