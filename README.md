# Oracle Fusion FBDI Templates

A collection of ready-to-use **File-Based Data Import (FBDI)** templates for Oracle Fusion Cloud ERP data migration.

## Overview

This repository contains FBDI spreadsheet templates and documentation for migrating data into Oracle Fusion Cloud modules. These templates follow Oracle's standard format and include field mappings, validation rules, and sample data.

## Modules Covered

| Module | Template | Status |
|--------|----------|--------|
| General Ledger (GL) | Journal Import | Available |
| Accounts Payable (AP) | Invoice Import | Available |
| Accounts Receivable (AR) | Invoice Import | Available |
| Fixed Assets (FA) | Asset Import | Available |
| Cash Management | Bank Statement Import | Coming Soon |

## Repository Structure

```
oracle-fusion-fbdi-templates/
|-- GL/
|   |-- JournalImport_template.csv
|   |-- GL_mapping_guide.md
|-- AP/
|   |-- InvoiceImport_template.csv
|   |-- AP_mapping_guide.md
|-- AR/
|   |-- InvoiceImport_template.csv
|   |-- AR_mapping_guide.md
|-- FA/
|   |-- AssetImport_template.csv
|   |-- FA_mapping_guide.md
|-- docs/
|   |-- FBDI_best_practices.md
|   |-- common_errors.md
|-- README.md
```

## How to Use

1. Download the template for your target module
2. Fill in data following the mapping guide
3. Save as CSV with UTF-8 encoding
4. Compress into a ZIP file
5. Upload via Fusion Cloud > Navigator > File Import
6. Run the ESS job for the respective module

## Key Features

- Pre-configured column headers matching Oracle's FBDI specification
- Field-level validation notes and data type requirements
- Sample data rows for reference
- Common error resolution guide
- Best practices for large-volume data loads

## Contributing

Contributions are welcome! If you have templates for additional modules or improvements to existing ones, please open a pull request.

## License

MIT License

## Author

**Lucky Malik** - Oracle Fusion Cloud Financials Consultant
- GitHub: [@luckymalik111](https://github.com/luckymalik111)
