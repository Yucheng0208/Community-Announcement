# Announcement Generation and Download

This is a simple web application that allows users to generate announcements and download them as DOCX files.

## Features

- Fill in announcement content
- Preview announcement
- Download announcement as a DOCX file

## Instructions

1. **Fill in Announcement Content**
    - Enter the community name, announcement title, and announcement content in the form.
    - Click the "Preview Announcement" button to see a preview of the announcement.

2. **Preview Announcement**
    - After filling in the form, click the "Preview Announcement" button to view the announcement preview below.

3. **Download Announcement**
    - Click the "Download Announcement (DOCX)" button to download the announcement as a DOCX file.

## Technical Details

- Uses the [docx](https://www.npmjs.com/package/docx) library to generate DOCX files.
- Uses [FileSaver.js](https://github.com/eligrey/FileSaver.js/) to download files.

## Code Structure

- `index.html`: The main HTML file containing the form and JavaScript scripts.
- `docx@7.1.0`: Library used to generate DOCX files.
- `FileSaver.min.js`: Library used to download DOCX files.

## Preview Screenshot

![Preview Screenshot](screenshot.png)

## Contribution

Issues and contributions are welcome. Please contact us via [GitHub Issues](https://github.com/your-repo/issues).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
