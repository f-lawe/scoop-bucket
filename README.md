# Flawe Scoop bucket

[![Tests](https://github.com/f-lawe/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/f-lawe/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/f-lawe/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/f-lawe/scoop-bucket/actions/workflows/excavator.yml)

Some usefull extra apps for [Scoop](https://scoop.sh), the Windows command-line installer.

## Manifest list

| Name                                                  | Version | Description                                                                  |
|-------------------------------------------------------|---------|------------------------------------------------------------------------------|
| [cmctl](https://cert-manager.io/docs/reference/cmctl) | 1.13.3  |Easily manage your certificates on a Kubernetes cluster running cert-manager |
| [oh-my-posh](https://ohmyposh.dev)                    | 19.8.3  | A prompt theme engine for any shell                                          |

## How do I install these manifests?

Run the following:

```pwsh
scoop bucket add f-lawe https://github.com/f-lawe/scoop-bucket
scoop install f-lawe/<manifestname>
```

## How do I contribute?

If you feel that an app should be in this list, or a manifest should be updated, just open an issue!
