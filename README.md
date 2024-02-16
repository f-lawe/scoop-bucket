# Flawe Scoop bucket

[![Tests](https://github.com/f-lawe/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/f-lawe/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/f-lawe/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/f-lawe/scoop-bucket/actions/workflows/excavator.yml)

Some usefull extra apps for [Scoop](https://scoop.sh), the Windows command-line installer.

## Manifest list

| Name                                                  | Description                                                                  |
|-------------------------------------------------------|------------------------------------------------------------------------------|
| [cmctl](https://cert-manager.io/docs/reference/cmctl) | Easily manage your certificates on a Kubernetes cluster running cert-manager |
| [oh-my-posh](https://ohmyposh.dev)                    | A prompt theme engine for any shell                                          |

## How do I install these manifests?

Run the following:

```pwsh
scoop bucket add flawe https://github.com/f-lawe/scoop-bucket
scoop install flawe/<manifest>
```

## How do I contribute?

If you feel that an app should be in this list, or a manifest should be updated, just open an issue!
