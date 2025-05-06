# Software Architecture Assignment
## Architectural Design Report: Slack-like System

### Requirements
1. Top-level architecture description
2. Detailed component breakdown
3. D2-based diagram in CI pipeline

### File Structure
   **`report.md`** - Architectural Design Report

   **`docs/`**  
     ├── `architecture.d2` - D2 diagram source code   
     └── `architecture.svg` - Auto-generated SVG diagram

   **`.github/workflows/diagram.yml`** - CI pipeline to load the D2 diagram


**Diagram Generation Process:**
1. Edit `docs/architecture.d2`
2. Push changes to `main` branch
3. CI pipeline generates updated SVG
4. Diagram auto-commits to repository
