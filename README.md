
# Manga Migration Kit (Doki/Kotatsu to Tachiyomi/Mihon)


## 🛠️ How it works
This repository uses a **GitHub Action** to:
1.  Install **Protocol Buffers** compiler (`protoc`).
2.  Compile the `schema.proto` into a Python class on the fly.
3.  Execute `main.py` to convert your backup with mathematical precision.

## Usage
1.  **Fork/Copy this Repo**.
2.  **Upload your Backup**:u can see my backup.zip
    remove it and put ur kotatsu/doki backup in same (backup.zip) format
3.  **Run**: Actions -> **Migration Pipeline**.
4.  **Download**: The artifact `converted_backup`.

## Changes
The Category and Structural Flag Fixes: Kotatsu's absolute category_id values mapping matrices (1, 2, 3, 4) were bound to Mihon's relative array elements
Custom multi-tab item linkage filters, protective typecast variables, and deduplication memory tracking layers.
Integrates explicit high-capacity string-buffer decoding. It reads the raw uncompressed JSON directly into high-memory blocks so that it anle to process up to 1,798 structural tab entries
