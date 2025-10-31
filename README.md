# Hardware Monorepo (KiCad)

Este repositorio agrupa múltiples proyectos de hardware.

## Proyectos
- sensado-soldadoras/: Módulo de sensado (KiCad), con kicad/, outputs/, mechanical/, docs/.

## Flujos
- Versionar releases por proyecto usando tags por convención, por ejemplo: sensado-soldadoras-hw-v1.0 o hw-v1.0 si el repo contiene un único proyecto activo.
- Subir Gerbers/BOM/PickPlace y PDFs a cada Release.
- Usar Git LFS (configurado en .gitattributes) para binarios.
