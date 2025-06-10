Digital Boatwright Library

A curated, open-source library of classic small boat plans digitized for modern CAD and CNC workflows.


---

🚀 Overview

The Digital Boatwright Library project seeks to preserve and modernize out-of-copyright or public-domain sailboat and small boat designs. Plans are recreated in SolidWorks and exported into formats useful for builders today: CNC-ready DXFs, STLs for 3D printing, 2D drawings, and rich documentation.

Whether you're restoring maritime heritage or crafting your own weekend sailer, this library aims to be a central resource for accessible, accurate digital boat plans.


---

📁 Directory Structure

Digital-Boatwright-Library/
├── .gitignore
├── LICENSE
├── README.md                ← You are here
├── docs/                    ← Contributor guides and style
│   ├── CONTRIBUTING.md
│   └── STYLE_GUIDE.md
├── boats/                   ← Each boat gets its own folder
│   └── Example_Boat_Name/
│       ├── Source/          ← Original scans, research notes
│       ├── CAD/             ← SolidWorks files, models
│       ├── CNC_Files/       ← Flat-pattern DXFs, nesting diagrams
│       ├── Docs/            ← Instructions, renders, BOM
│       └── License.txt
└── tools/
    └── import_helpers/
        └── scan_to_dxf_guide.md


---

🛠 Getting Started

1. Clone the Repository

git clone https://github.com/YourUser/Digital-Boatwright-Library.git

2. Open a Boat Project

Each folder inside boats/ contains one digitized boat design. Start with:

cd boats/Example_Boat_Name/

Open the CAD/SW_Assembly.sldasm in SolidWorks. You'll find:

Parametric 3D hull and parts

Cross sections or lofted surfaces

Ready-to-export DXFs for CNC


3. Add a New Boat

See docs/CONTRIBUTING.md to add your own digitized plan. Each project includes:

Original plan scans (ideally public domain)

Modeled parts with real dimensions

Documentation and build instructions



---

📜 License

This repository is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

> Individual boat folders may include additional or more specific license files depending on source materials.




---

🤝 Contributing

We're always looking for:

Boat lovers who can model classic plans

Educators and students preserving maritime design

Engineers and tinkerers creating CNC kits or models


See docs/CONTRIBUTING.md to learn how to:

Submit a new plan

File an issue or request

Share your work with credit



---

🌍 Our Mission

To preserve the craftsmanship of small boat design and make it accessible to a new generation of makers, builders, and dreamers.

Fair winds, and happy modeling! ⛵

