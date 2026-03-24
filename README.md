# Arch-Render AI Toolkit 🏗️🎨

> 📢 **Join our [Project Discussion](https://github.com/Angmargirls/arch-render-ai-toolkit/discussions/1) to learn more about our long-term vision!**

---

### 🌟 Project Overview
**Arch-Render AI Toolkit** is an open-source middleware designed to bridge the gap between traditional architectural design (BIM/CAD) and generative AI rendering workflows. 

We are building a logic-driven engine that extracts spatial relationships and material metadata from architectural files (like IFC) and translates them into high-fidelity, structurally accurate prompts for AI diffusion models.

### ✨ Key Features
* **BIM Metadata Extraction**: Automated parsing of IFC/OBJ files to identify wall materials, glazing ratios, and spatial context.
* **AI Prompt Engineering**: Using LLMs to convert raw technical data into cinematic architectural photography prompts.
* **Consistency Control**: Ensuring that AI-generated visuals respect the original design intent and structural logic.

### 🚀 Roadmap & Status
- [x] **Project Scaffolding**: Repository initialized and community discussion opened.
- [x] **Core Architecture (Mar 15)**: Implemented modular logic for `MetadataParser` and `PromptEngine`.
- [ ] **Phase 1: API Integration**: Connect OpenAI Codex/GPT-4 to automate linguistic optimization of prompts. (Awaiting Grant)
- [ ] **Phase 2: Geometry Engine**: Deep integration with `ifcopenshell` for real-time 3D geometry analysis.
- [ ] **Phase 3: CLI Tooling**: Release a command-line interface for architects to batch-process rendering strategies.

### 🛠️ Tech Stack
* **Language**: Python 3.9+
* **BIM Processing**: `ifcopenshell`, `pyvista`
* **AI Integration**: OpenAI Codex / GPT-4 API
* **Format Support**: IFC, OBJ, JSON
[![Flag Counter](https://s01.flagcounter.com/count2/pQ54/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_3/labels_1/pageviews_1/flags_0/percent_0/)](https://info.flagcounter.com/pQ54)
🗺️ Roadmap
The arch-render-ai-toolkit aims to continuously bridge the gap between architectural data and generative AI.

Phase 1: Core Foundation (Q1 - Q2 2026) [Active]
[x] Implement initial metadata extraction for OBJ file formats.

[ ] Expand support for IFC (Industry Foundation Classes) data parsing.

[ ] Standardize geometry-to-text data mapping.

Phase 2: AI-Powered Intelligence (Q3 2026) [Target: OpenAI API Integration]
[ ] Integrate Codex/GPT-4 to automatically transform 3D metadata into professional architectural prompts.

[ ] Develop an automated "Style Refiner" that suggests lighting and material prompts based on building typology.

[ ] Implement BIM-aware prompt engineering to maintain design consistency across multiple views.

Phase 3: Ecosystem & Plugins (Q4 2026 & Beyond)
[ ] Release lightweight plugins for Rhino/Grasshopper and Revit.

[ ] Enable cloud-based batch processing for large-scale architectural scenes.

[ ] Build a community-driven library of architectural visualization "logic blocks."
