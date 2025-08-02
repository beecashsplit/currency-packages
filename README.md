🐝beecashsplit-currency-packages
beecashsplit-currency-packages is a collection of downloadable asset packages (images + configuration files) used by the BeeCashSplit app to dynamically load local currencies depending on the user’s region.

These packs allow the app to remain lightweight and adaptable, downloading only the assets needed based on the user’s country or currency.

📦 Folder Structure
Each currency pack follows this structure:

beecashsplit-currency-packages/ ├── packages.json
├── europe/ │ ├── manifest.json
│ └── images/ │ ├── 50000_unit.png # 500€ │ ├── 20000_unit.png # 200€ │ ├── 10000_unit.png # 100€ │ └── ... (tutti i tagli) └── india/ ├── manifest.json
└── images/ ├── 10000_unit.png # 100₹ ├── 5000_unit.png # 50₹ ├── 2000_unit.png # 20₹ └── ... (tutti i tagli)
