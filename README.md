## Why this tool?

Comparing Excel files sounds simple until you need it for real work:

- **Online tools** often upload spreadsheets to a remote server. That is a poor fit for price lists, customer data, or internal catalogs.
- **Generic file diff tools** treat workbooks like opaque binaries or flat text. They rarely understand *records*, *keys*, or *moved rows*.
- **Microsoft Spreadsheet Compare** is excellent when available — but it ships only with specific Office editions, not with every license.

This project focuses on a practical middle ground:

1. **Privacy first** — all processing is local. Nothing is sent over the network.
2. **Business-oriented comparison** — strict cell mode *and* smart/key-based matching when rows shift.
3. **Price awareness** — optional analysis of value changes, not only “cell A ≠ cell B”.
4. **Usable output** — reports in XLSX, CSV, TXT, and JSON for audit trails and further work.
5. **Accessible UI** — Greek and English, no scripting required for everyday use.

Original workbooks are opened read-only in spirit: the tool never writes back to File A or File B.
