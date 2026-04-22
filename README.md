Lanmodulin Engineering for Acidic Mining Conditions

Overview

This project focuses on the rational engineering of lanmodulin to maintain structural stability and lanthanide-binding capacity under highly acidic conditions (target ~pH 2.5), relevant to mining environments.

The work is conducted independently using a reproducible computational pipeline integrating structural biology, protonation modeling, and protein flexibility analysis.

Problem Statement

Lanmodulin is a high-affinity lanthanide-binding protein; however, its functionality is expected to be compromised under extreme acidic conditions due to:

a. Protonation of acidic residues (Asp, Glu)
b. Disruption of electrostatic interactions
c. Destabilization of metal-binding sites

Currently, there are few validated variant optimized for low pH environments relevant to biomining or metal recovery.

Hypothesis

Targeted mutations informed by structural dynamics and extremophile protein characteristics can improve lanmodulin stability and preserve functional geometry under acidic conditions.

Approach

The project follows a structured in silico pipeline:

1. Structure Acquisition
-Retrieval of lanmodulin structures from RCSB Protein Data Bank
2. Protonation Modeling
-Simulation of low pH environments using H++
3. Preprocessing
-Custom Python scripts for structural cleaning and compatibility
4. Flexibility Analysis
-Residue-level fluctuation analysis using CABSflex 2.0
5. Residue Classification
-Identification of mutation candidates:
-Binding site residues
-Structural core
-Surface / flexible regions
6. Comparative Analysis
Reference to extremophilic systems such as Methylacidiphilum fumariolicum
7. Iterative Mutation Design (in progress)
-Rational selection of candidate mutations
8. Structure Prediction & Validation (planned)
-Using AlphaFold and downstream analysis
9. Docking Simulations (planned)

Current Status
-Protonation simulations across pH range (6 → 2.5) (completed)
-Initial flexibility profiles (RMSF) (generated)
-Preliminary identification of high-variability regions
-Data organization and quantitative analysis (in progress)

Key Challenges
-Maintaining lanthanide coordination under protonated conditions
-Distinguishing local flexibility from global destabilization
-Avoiding disruption of functional binding sites
-Lack of experimental validation (current stage is fully computational)

Repository Structure

lanmodulin-project/
│
├── research-log/        # Structured experimental logs (Markdown)
├── data/                # Raw and processed structural data
├── scripts/             # Python preprocessing and analysis tools
├── mutants/             # Designed variants and associated outputs
└── README.md

Reproducibility

All steps are documented through:

1.Version-controlled research logs
2.Explicit parameter tracking
3. Script-based preprocessing

The workflow is designed to be fully reproducible and auditable.

Author

Undergraduate researcher (final year) conducting independent work in computational protein engineering, with a focus on metal-binding proteins and extremophile-inspired design.

Project Goals (Short-Term)
1. Quantitative comparison of residue-level flexibility across pH conditions
2. Identification of 3–5 high-confidence mutation candidates
3. Structural validation of designed variants

Project Goals (Mid-Term)
1.Stability assessment of mutants
2. Comparative structural analysis versus wild type
3. Preparation of results for academic evaluation (scholarships / graduate applications)

Contact / Collaboration

Open to academic discussion, feedback, and potential collaboration in computational protein design and biomining applications.
Mail: nicolasvassellati@gmail.com
