# Python Text Extract
Extracts text from a pdf and exports it to text files.

# Usage
python text-extract.py <input_path> <output_directory> (optional)<excluded_pages>

## Arguments
- input_path: The path to a pdf file you want to parse
- output_directory: The directory where the pages will be extracted. There will be one file per page.
- excluded_pages: Optional. You can pass a list of pages/page ranges to exclude. E.g. 1,2,5-10. Numbering starts at 1