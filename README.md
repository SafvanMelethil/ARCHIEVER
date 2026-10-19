# Monthly File Archiver

A browser app that builds a monthly Excel archive of pharmacy files in three sheets: **Special-urgent**, **Offer Dispatch** and **Transfer**.

## How to use
1. Choose the month.
2. Say whether there is a previous archive for that month. If yes, upload it and new rows are added to it.
3. Choose the day and upload that day's files (Excel or CSV, one or more).
4. For every sheet: choose who sent it, which archive sheet it belongs to, and give a WH (or pharmacy) where the file has none.
5. Add another date, or press **No, I'm done** and generate the archive (.xlsx).

Material codes are found anywhere in the sheet: any 6-digit number starting with 1–5, regardless of the column header.

Output columns: `S.no · Pharmacy · Material Code · Qty · Wh · Who send the file · Date · File Name`, plus a **File Log** sheet listing every file added.

## Privacy
Everything runs in your browser. Files are never uploaded to any server.

## Hosting
This is a single `index.html`. To publish with GitHub Pages: repository **Settings → Pages → Deploy from a branch → main / (root)**.
