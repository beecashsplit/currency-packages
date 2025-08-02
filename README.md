🐝beecashsplit-currency-packages
beecashsplit-currency-packages is a collection of downloadable asset packages (images + configuration files) used by the BeeCashSplit app to dynamically load local currencies depending on the user’s region.

These packs allow the app to remain lightweight and adaptable, downloading only the assets needed based on the user’s country or currency.

📦 Folder Structure
Each currency pack follows this structure:

currency-packages/
├── packages.json                 # Lista pacchetti disponibili
├── europa/
│   ├── config.json              # Configurazione Euro
│   └── images/
│       ├── banknotes/
│       │   ├── 500_euro.png
│       │   ├── 200_euro.png
│       │   ├── 100_euro.png
│       │   ├── 50_euro.png
│       │   ├── 20_euro.png
│       │   ├── 10_euro.png
│       │   └── 5_euro.png
│       └── coins/
│           ├── 2_euro.png
│           ├── 1_euro.png
│           └── centesimi/
│               ├── 50_cent.png
│               ├── 20_cent.png
│               ├── 10_cent.png
│               ├── 5_cent.png
│               ├── 2_cent.png
│               └── 1_cent.png
└── india/
    ├── config.json              # Configurazione Rupie
    └── images/
        ├── banknotes/
        │   ├── 2000_rupee.png
        │   ├── 500_rupee.png
        │   ├── 200_rupee.png
        │   ├── 100_rupee.png
        │   ├── 50_rupee.png
        │   ├── 20_rupee.png
        │   └── 10_rupee.png
        └── coins/
            ├── 10_rupee.png
            ├── 5_rupee.png
            ├── 2_rupee.png
            └── 1_rupee.png
