# AI Exposure Explorer

Static page, no build step. Upload this folder to a GitHub repository and enable GitHub Pages (Settings > Pages > Deploy from branch), or drop it on any static host.

- `index.html` is the page (loads d3 from cdnjs and fonts from Google Fonts)
- `ILO-logo.png` (optional): add your white ILO logo here, the same file used in the Shiny app's `www` folder, and it appears in the blue header. Without it the header simply shows no logo.
- `data.json`: 427 ISCO-08 occupations with task scores (2023 and 2025)
- `o6.json`: 2,541 Polish 6-digit occupations (summary)
- `j1-9.json`: model reasoning for ISCO-08 tasks, by major group
- `k1-9.json`: Polish tasks, scores and shortened reasoning, by major group

Sources: ILO Working Paper 140 (doi 10.54394/HETP0387); github.com/pgmyrek/2025_GenAI_scores_ISCO08 and github.com/pgmyrek/POLAND_2025_GenAI_scores_6digit_occupations.
