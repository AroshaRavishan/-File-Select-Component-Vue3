# File Upload Component

This component provides a file upload interface that allows users to upload files either by clicking to select or by dragging and dropping them into the designated area. The component includes features such as file size validation, progress tracking, and a success indicator.

## Features

- **Drag and Drop**: Users can drag and drop files into the upload area.
- **Click to Upload**: Users can click the upload area to open the file selector.
- **File Size Validation**: Files larger than 10MB are not accepted.
- **Progress Bar**: Shows the upload progress as a percentage.
- **Success Indicator**: Shows a success message and icon when the upload is complete.
- **Supported File Types**: DOC, DOCX, PDF, TXT, PPT, PPTX, XLS, XLSX, ZIP, RAR, JPG, PNG, JPEG.

## Notes

- Replace 'YOUR_UPLOAD_URL' with your actual file upload URL.
- Supported file types and size limit are enforced in the handleFile function.
- The progress bar and success indicator provide feedback during the file upload process.
