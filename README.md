# **BioMinimal** 

An interactive showcase website engineered for the **2023 STAI Web Design Showdown** competition within the Senior division. Built around the core theme of **Genetic Engineering in Health Care**, the platform explores the implications, breakthroughs, and future visions of genetic modification through a highly optimized user experience.


## Design Philosophy & Core Vision

The project is built entirely upon a singular design maxim: **"Show less, gain more."** 

Rather than overwhelming the end-user with dense text blocks, the interface relies on clean typographical hierarchies, seamless structural navigation, and high-impact visual delivery to maximize user retention and informational clarity regarding modern health care transformations.


## Architecture & Project Structure

The project decouples behavioral automation scripts, layout components, asset streams, and design documentation rules into independent files and directories:

```text
├── Assets/                        # Visual presentation materials and iconography
├── pages/                         # Content sub-views and structural sub-pages
├── scripts/                       # Local programmatic functionality and dynamic UI behavior
├── styles/                        # Style definitions (CSS typography, grids, layout wrappers)
│
├── Content.txt                    # Compiled research data and text copy resources
├── Presentation PPt.pptx          # Competition review slide deck
├── References.pur                 # System conceptual layout maps
├── Rules.md / Rules.txt           # Regulatory event metrics and evaluation guidelines
├── Website Showdown STAI 2023.pdf # Event brief and technical specifications handbook
└── index.html                     # Core application gateway and landing dashboard
```

## Core Technical Highlights

- **Modular Web Stack:** Uses isolated global layouts (`styles/` and `scripts/`) to serve responsive, multi-page contexts efficiently from a central baseline code base.
- **Minimalist User Experience (UX):** Employs strict container controls to realize the "show less, gain more" intent, minimizing distractions and emphasizing target reading paths.
- **Academic Resource Tracking:** Integrates native reference files, competition specification logs, and structural design blueprints directly into the working directory for rapid verification.

## Local Execution

### 1. Prerequisites

Because this project runs natively within standard browser engines without external server dependencies, it can be tested inside any modern web browser environment.

### 2. Implementation

1. Clone the repository files to your local environment:

   ```bash
   git clone [https://github.com/bryanjooe/STAI-2023-Web-Design.git](https://github.com/bryanjooe/STAI-2023-Web-Design.git)
   ```

2. Navigate directly to the project root directory.

3. Open `index.html` inside your browser framework or spin up a localized developer port:

   ```bash
   # Quick local execution environment
   python -m http.server 8080
   ```

   > Open your browser and navigate to `http://localhost:8080` to explore the presentation workspace.
