# Práctica Formativa Obligatoria 2 - Prompt Engineering en Agentes de IA

**Estudiante:** Asunción María Ayelén  
**Tecnicatura:** Desarrollo de Software — IFTS N.° 29

**Enlace de Producción:** https://<TU_DEPLOY_VERCEL>.vercel.app

## Descripción del Proyecto

KHAYEN es un proyecto de diseño de autor desde Misiones, Argentina, basado en sustentabilidad textil, upcycling y tintes naturales de descarte como palta y uva. Esta práctica formativa exploró cómo diferentes agentes de IA interpretaban directivas de “anarquía visual”, asimetría, bloques de color pleno y animaciones fluidas no lineales sin perder usabilidad.

La propuesta visual se construyó sobre una paleta rígida y disruptiva: Verde Selvática #B4C136, Ocre Mostaza #D8B837 y Terracota #BE5941.

## Arquitectura del Repositorio

- `index.html`
- `prompt.html`
- `prompt.txt`
- `agente-1/`
  - `khayen-landing.html`
- `agente-2/`
  - `khayen.html`
- `agente-3/`
  - `index.html`

## Objetivo de la Práctica

El objetivo principal fue testear cómo distintos agentes de IA generan soluciones visuales y de interacción ante un prompt de alta precisión que solicitaba:

- identidad sustentable y de upcycling,
- una estética asimétrica y anárquica,
- bloques de color pleno con la paleta KHAYEN,
- animaciones orgánicas y fluidas,
- preservación de usabilidad y accesibilidad.

## Prompt Exacto Utilizado

```markdown
Eres un asistente creativo y técnico llamado KHAYEN-BOT. Tu tarea es generar una propuesta visual web para la marca KHAYEN —diseño de autor desde Misiones, Argentina— fomentando sostenibilidad (upcycling textil) y uso de tintes naturales de descarte (palta y uva). Sigue estas directrices con precisión:

1) Concepto y tono:
- Marca: KHAYEN — artesanal, experimental, sustentable, con raíz regional.
- Tono: contemporáneo, experimental pero usable; mezcla de “anarquía visual” comedida y estructura UX clara.
- Público objetivo: consumidores conscientes entre 22–45 años, interesados en diseño único y prácticas eco.

2) Composición visual:
- Prioriza asimetría intencionada: bloques desplazados, márgenes irregulares, tipografía con jerarquías contrastadas.
- Emplea bloques de color pleno (no degradados principales) con la siguiente paleta exacta:
  - Verde Selvática: #B4C136
  - Ocre Mostaza: #D8B837
  - Terracota: #BE5941
- Acompaña con neutros cálidos para zonas de texto y lectura.
- Texturas: sugerir sutiles texturas tipo tela o fibras como fondo de secciones.

3) Tipografía y legibilidad:
- Usa tipografía con contraste entre display experimental para títulos y sans-serif legible para cuerpos.
- Asegura contraste suficiente para accesibilidad WCAG AA en texto de cuerpo.

4) Interacciones y animación:
- Animaciones fluidas y no lineales: micro-interacciones con easing orgánico, transformaciones suaves y ritmos asimétricos.
- Evita parpadeos y efectos que interfieran con la lectura.
- Prioriza rendimiento: animaciones impulsadas por transform/opacity y limitadas a 60fps razonable.

5) Contenido y estructura:
- Portada con hero asimétrico que comunique upcycling y tintes naturales.
- Sección “Proceso” con texto sobre tintes de palta y uva y filosofía de suprarreciclaje.
- Sección “Colección” con tarjetas modulares asimétricas.
- Footer con contacto y manifiesto de sustentabilidad.

6) Accesibilidad y rendimiento:
- Prioriza HTML semántico y navegación por teclado.
- Imágenes optimizadas y carga perezosa.
- CSS crítico inline para primer render.

7) Entregables:
- HTML estático funcional, CSS modular y animaciones con CSS/JS mínimo.
- Comentarios claros en el código explicando decisiones de diseño.

8) Restricciones:
- No uses elementos que produzcan flash o movimiento que provoque mareo.
- Mantén todas las paletas de color exactamente según los hex provistos.
- La estética debe sugerir “anarquía visual” sin destruir la usabilidad.

Genera: (A) una página index.html de portada; (B) una landing de producto tipo “lookbook”; (C) un fichero prompt.html que actúe como visor estilizado del prompt y variantes. Entrega el código completo y listo para desplegar en Vercel.
```

## Capturas de Pantalla

- Portada Principal
<div style="display:flex;flex-wrap:wrap;gap:8px;align-items:flex-start">
  <img src="assets/screenshot-portada.png" alt="Portada Principal - KHAYEN" width="450" style="display:inline-block;border:1px solid #ddd;padding:4px">
</div>

- Prompt
<div style="display:flex;flex-wrap:wrap;gap:8px;align-items:flex-start">
  <img src="assets/prompt.png" alt="Portada Principal - KHAYEN" width="450" style="display:inline-block;border:1px solid #ddd;padding:4px">
</div>

- Landing 1 (Codex)
<div style="display:flex;flex-wrap:wrap;gap:8px;align-items:flex-start">
  <img src="assets/screenshot-1.png" alt="Landing Agente Codex" width="450" style="display:inline-block;border:1px solid #ddd;padding:4px">
</div>

- Landing 2 (Open Code)
<div style="display:flex;flex-wrap:wrap;gap:8px;align-items:flex-start">
  <img src="assets/screenshot-2.png" alt="Landing Agente Open Code" width="450" style="display:inline-block;border:1px solid #ddd;padding:4px">
</div>

- Landing 3 (Claude 3.5 Sonnet)
<div style="display:flex;flex-wrap:wrap;gap:8px;align-items:flex-start">
  <img src="assets/screenshot-3.png" alt="Landing Agente Claude 3.5 Sonnet" width="450" style="display:inline-block;border:1px solid #ddd;padding:4px">
</div>

> Nota: Reemplaza las rutas `screenshots/*.png` por las capturas reales exportadas desde cada carpeta de agente.

## Bitácora Técnica

- Se evaluó la interpretación de cada agente sobre directivas de anarquía visual y uso estricto de paleta.
- Se comparó la fidelidad a los colores KHAYEN, la coherencia en la asimetría y la claridad en la experiencia.
- El objetivo fue lograr una entrega lista para despliegue en Vercel con estructura web estática.

## Créditos de IA

Este README y la formulación de prompts de alta precisión se desarrollaron con la colaboración estratégica de Gemini como Inteligencia Artificial de asistencia. Todo el contenido fue verificado y adaptado manualmente para ajustarse a los criterios académicos y a la visión del proyecto.
