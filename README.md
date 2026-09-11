<img width="1919" height="1142" alt="image" src="https://github.com/user-attachments/assets/76670573-491c-48c7-83d7-160b98c9ff22" />


<img width="1919" height="1137" alt="image" src="https://github.com/user-attachments/assets/574dcfdc-ce42-4c64-8f62-c407f25950b1" />

<img width="1919" height="1137" alt="image" src="https://github.com/user-attachments/assets/96f55ac0-e250-413f-96cb-0f4857ccbd47" />

<img width="1919" height="1140" alt="image" src="https://github.com/user-attachments/assets/1d56446e-9fa0-405d-84cc-a2c74f9b2e46" />

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
