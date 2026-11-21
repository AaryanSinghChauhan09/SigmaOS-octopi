# SigmaOS-octopi

SigmaOS integration component for **Octopi package manager**.

## Commands

```bash
sigmaos-octopi install   # install package + deploy defaults
sigmaos-octopi deploy    # copy config templates to $HOME
sigmaos-octopi status    # binary/package/config report
sigmaos-octopi reset     # remove deployed config
sigmaos-octopi open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
