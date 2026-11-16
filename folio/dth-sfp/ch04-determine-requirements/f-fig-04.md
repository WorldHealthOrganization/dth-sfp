![Fig. 4. Example workflow depicting the process of reporting substandard and falsified medical products (p. 30 / PDF p. 42)](media/fig-4-sf-reporting-workflow.svg)

*Source: WHO, Digital transformation handbook for reporting substandard and falsified medical products, 2025, Fig. 4 (L1 section `who-iris/library/9789240120747-eng/sections/sec-024-43-develop-business-processes-and-workflows.md`; PDF crop `who-iris/library/9789240120747-eng/figures/vfig-p042.png`, PDF page 42). Drawn by `scripts/figures/as-drawn.ts` from the as-drawn BPMN 2.0 transcription `figure-data/fig-4-sf-reporting-workflow.bpmn`, transcribed from the PDF's vector layer with the printed layout, colours and wording. Mapped to `dpi-h-ra` ArchiMate view `Track and Trace through DHSC Components (DTH SC Fig. 24)` (`id-bea56e01c8345fbc803dee47a17ccfd3`).*

> [!WARNING]
> **Source Figure Review Findings (`litlfred/dth-sfp#1` §3):**
> - **F2: Fig. 4 omits the third WHO SF category ('unregistered/unlicensed medical products', p. ix & p. 1).**
> - **F5: Fig. 4 contains 5 BPMN 2.0 defects (step 2 repeats gateway 1; gateway 1 has an unlabelled bypass to End; gateway 5 is labelled 'Select type of report' rather than a question; step numbers 6-8 repeat on both branches; symbols deviate from Annex 3). Preserved as the L1 source figure and redrawn cleanly in bp:sf-rep-001 (processes/SF-REP-001.bpmn).**
