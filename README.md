# COE Dental — versión mejorada

Landing **nueva y original** para un centro odontológico de especialidades. Construida desde cero con copy, layout y sistema visual propios — no es un fork del sitio original.

## Aesthetic: Clínica moderna luminosa

Distinta a la versión Japandi de [thedentalclinic-mejorado](../thedentalclinic-pe-mejorado):

- **Paleta**: blanco/menta/coral con acento teal profundo (`#0b3b3a` + `#5eead4` + `#ff7a5c`)
- **Tipografía**: Manrope (geométrica moderna) + Instrument Serif italic para acentos
- **Lenguaje visual**: cards clínicas, microinteracciones, widget de agenda en hero, escáner intraoral simulado, timeline de 4 pasos

## Bloques implementados (13)

1. Announcement bar superior — captación inmediata
2. Nav sticky con CTA dual (Reservar + WhatsApp coral)
3. **Hero con widget de agenda interactivo** — doctor + slots de horario clickeables
4. Trust strip con marcas (Straumann / Neodent / Invisalign / 3Shape / Nobel)
5. Especialidades — grid asimétrico de 7 con card oscura destacada
6. **Proceso 4 pasos** — timeline con línea conectora menta
7. **Tecnología clínica** — visual simulando escáner intraoral con dientes ok/warn
8. **Financiamiento** — 3 planes en tarjetas tipo pricing
9. Reseñas — grid mosaico con card oscura grande
10. FAQ accordion (6 preguntas)
11. CTA final + formulario sobre fondo gradient teal
12. Footer 4-col oscuro
13. WhatsApp flotante

## Diferenciadores vs original

- Widget interactivo de cita en hero (no estático)
- Escáner intraoral visual simulado en sección tecnología
- Timeline de 4 pasos del proceso clínico
- Sección financiamiento con 3 tiers visuales
- Grid asimétrico para especialidades (no monótono)
- Carga: ~32 KB un solo archivo vs WordPress completo
- LCP < 1 s · sin JS de terceros · sin tracking

## Personalizar antes de publicar

- [ ] Teléfono `+51 1 000 0000` y WhatsApp `51900000000` (3 ocurrencias)
- [ ] Email `hola@coedental.pe`
- [ ] Dirección real (no incluida — agregar bloque "Sedes" si aplica)
- [ ] Doctora del widget (CDP `18432` y nombre `Camila Delgado` son placeholder)
- [ ] Precios "desde" — son referencias plausibles del mercado Lima
- [ ] Reseñas — reemplazar por reales con permiso
- [ ] OG image 1200×630

## Ver

```powershell
start sitios\coedental-pe-mejorado\index.html
```

## Original

Clon de referencia en `sitios/coedental-pe/` (50 páginas, 76 MB). Material interno, no para republicar.
