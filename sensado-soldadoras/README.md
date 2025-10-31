# Sensado Soldadoras - Hardware (KiCad)

Repositorio de diseños de hardware (KiCad) para el sistema de sensado.

## Estructura
- kicad/: archivos fuente del proyecto KiCad (.kicad_pro, .kicad_sch, .kicad_pcb, librerías)
- outputs/: archivos de fabricación
  - gerbers/, om/, pickplace/, pdf/
- mechanical/: modelos 3D y mecánica (STEP, STL, etc.)
- docs/: documentación, datasheets, fotos

## Buenas prácticas
- Versionado de HW por tags: hw-v1.0, hw-v1.1.
- Adjuntar Gerbers, BOM y Pick&Place en cada Release.
- Usar Git LFS para binarios pesados (STEP/PDF/ZIP).

## Generar outputs
- Exporta Gerbers, BOM (CSV) y Pick&Place desde KiCad y colócalos en outputs/.
- Exporta esquemáticos y PCB a PDF a outputs/pdf/.

