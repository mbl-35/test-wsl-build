# wsl-alpine-docker

Docker & docker-compose lite WSL development environment.

## Versions alpine-docker

| produit   | 3.20.0   |
| --------- | -------- |
| alpine    | 3.20.0   |
| docker    | 26.1.3   |
| d-compose | 2.27.0   |
| git       | 2.45.2   |
| python    | 3.12.3   |

## Quick Start

Install (wslctl)[https://github.com/mbl-35/wslctl] via scoop, then:

```powershell
PS> wslctl registry update
PS> wslctl create srsrns/alpine-docker:3.20.0
PS> wslctl exec alpine-docker-3.20.0
```
