## supply-chain-data-importer

**Enterprise Data File Generator & Validator** focused on Supply Chain.

### Overview
This project provides tools to generate clean, validated, and properly formatted import files for enterprise systems (Oracle, Microsoft Dynamics 365/CRM, and others). It targets real Supply Chain use cases such as inventory, purchase orders, shipments, and supplier data.

### Key Features (Planned)
- Generate Oracle-compatible flat files (SQL*Loader, External Tables)
- Generate Dynamics 365 / CRM import templates
- Strong data validation before export
- Schema and business rule enforcement
- Error logging and detailed rejection reports
- Configurable transformation rules

### Tech Stack
- Python 3.11+
- Pandas / Polars
- Pydantic for validation
- SQL (Oracle syntax knowledge)
- YAML configuration

### Project Structure
```
supply-chain-data-importer/
├── README.md
├── requirements.txt
├── .gitignore
├── src/
│   ├── generators/
│   ├── validators/
│   ├── transformers/
│   └── config/
├── data/
│   ├── input/
│   ├── output/
│   └── templates/
├── docs/
└── tests/
```

### Roadmap
- Phase 1: Oracle file generation (SQL*Loader format)
- Phase 2: Dynamics 365/CRM import file generation
- Phase 3: Advanced validation engine + business rules
- Phase 4: Multi-system support + audit reports

### Domain Focus
**Supply Chain** (Inventory, Procurement, Logistics, Suppliers)

---

*Part of a 4-project Data Engineering portfolio.*