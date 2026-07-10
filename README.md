# Credit Card Studio

Studio 3D / WebGL per progettare e animare carte di credito.

- Scena multi-card con selezione a click e rinomina delle carte
- Rotazione ad asse libero (azimuth) per carta, in versi speculari
- Timeline stile After Effects con keyframe per ogni valore (GSAP + custom ease)
- Finitura patinata (soft-touch matte) a livello di materiale
- Pipeline di post-processing: bloom, god rays, radial light, vignette, aberrazione cromatica, grana, color grade
- Controllo formato/aspect-ratio del canvas ed export PNG ad alta risoluzione

## Uso
File singolo autoconsistente: apri `index.html` in un browser moderno. three.js e GSAP sono caricati da CDN.

## Deploy (Vercel)
Progetto statico: nessuna build. Basta puntare Vercel a questa cartella; `index.html` viene servito alla root.
