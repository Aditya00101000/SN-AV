# SN-AV

Should the data be in JSON instead of TSV?
Use TSV when:

You need to quickly view or process the data using tools like Excel, LibreOffice, or awk, grep, cut.

You prefer simplicity and human-readability.

You are dealing with flat/tabular data with no nested structure.

Use JSON when:

You are developing applications (web/mobile/backend) that need structured or hierarchical data.

You want better compatibility with programming languages (e.g., JavaScript, Python, etc.).

You plan to load the data into NoSQL databases or send it over APIs.

