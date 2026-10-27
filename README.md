# 3D Bas Relief Generator 🏺

Web app completa per la generazione in tempo reale di bassorilievi 3D a partire da qualsiasi immagine 2D (foto, loghi, motivi ornamentali, stencil).
Ottimizzata per la **fresatura CNC su legno/metallo**, la **stampa 3D (FDM / Resina)** e l'**incisione laser**.

Ispirata al funzionamento di [Triverse 3D Relief Generator](https://triverse.ai/3d-relief-generator).

---

## ✨ Funzionalità

- **100% Client-Side nel Browser**: Nessuna API remota richiesta, nessun costo per credito, zero problemi di CORS o token esauriti. Funziona istantaneamente sia online che offline.
- **Mesh 3D Solida e Watertight (Manifold al 100%)**: Crea un solido completamente chiuso con base posteriore piatta e bordi laterali saldati, subito pronto per lo slicer (Cura, Bambu Studio, PrusaSlicer, Fusion 360, ArtCAM, Aspire).
- **Controllo Parametrico Real-time**:
  - **Relief Depth (mm)**: Altezza del rilievo in millimetri.
  - **Base Thickness (mm)**: Spessore della tavola di fondo.
  - **Width (mm)**: Larghezza fisica dell'oggetto finale.
  - **Smoothness**: Filtro di levigatura e rimozione del rumore dell'immagine.
  - **Compressione / Contrasto**: Regolazione dinamica delle ombre e delle curve di altezza.
  - **Appiattisci Fondo Scuro (Cutout)**: Rende il nero della silhouette a livello zero per medaglie e sagome pulite.
  - **Inverti Profondità**: Passaggio istantaneo da bassorilievo a stampo/negativo.
- **Shader e Materiali di Visualizzazione PBR**:
  - Aged Gold (Oro antico)
  - Bronzo
  - Argento lucido
  - Dark Iron (Ferro battuto)
  - Argilla / Calco
- **Esportazione Diretta**:
  - **Download STL binario watertight**: File 3D compatto e pronto per la fresa CNC o stampante 3D.
  - **Esporta Heightmap (PNG 16-bit)**: Mappa di profondità grayscale per laser e software CAM.
