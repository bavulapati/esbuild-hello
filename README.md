# Getting started with ESBUILD along with flatpak

Sample usage of ESBUILD with flatpak.
The goal of this experiment is to understand how can we pull npm dependencies.

## Usage

```
flatpak run org.flatpak.Builder build org.flatpak.EsbuildHello.yml --force-clean --install --user
flatpak run org.flatpak.EsbuildHello 

```

