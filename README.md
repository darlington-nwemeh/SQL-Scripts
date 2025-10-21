# SQL Scripts Repository

A growing collection of reusable SQL scripts for database development and data engineering tasks.

## 📘 Overview
This repository provides small, modular SQL utilities to simplify everyday operations — from data formatting to transformation logic.

### Current Contents
- **`fn_format_phone_number.sql`** — A PL/pgSQL function that formats phone numbers into a standardized representation for consistency across datasets.

## 🛠️ Supported Platform
- PostgreSQL (PL/pgSQL)

## 🚀 Usage
1. Open your SQL client (psql, DBeaver, etc.).
2. Run the script in your target database:
   ```sql
   \i fn_format_phone_number.sql
   ```
3. Call the function as needed:
   ```sql
   SELECT fn_format_phone_number('1234567890');
   ```

## 📂 Structure
```
SQL-Scripts/
├── fn_format_phone_number.sql
└── README.md
```

## 💡 Future Additions
- Data validation functions
- String manipulation utilities
- Common ETL helper procedures
- Cross-database compatible syntax variants (T-SQL, MySQL)


**Author:** [Darlington Nwemeh](https://github.com/darlington-nwemeh)
