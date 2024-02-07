# multipart-upload
This repository contains a Node.js application designed to facilitate efficient transfer of large video files between Google Drive directories. The application utilizes Google Drive APIs for both downloading and uploading operations, implementing chunked uploading mechanisms to ensure resilience and efficiency for large files.

# Features:

1: **Download from Google Drive**: The application allows users to specify a specific Google Drive directory from which to download a large video file.
2: **Upload to Google Drive**: Simultaneously with the download process, the application initiates the uploading of the downloaded file to another Google Drive directory.
3: **Chunked Uploading**: To handle large file sizes efficiently, the application implements a chunked uploading mechanism, breaking the file into smaller parts for resilient and efficient transfer.
4: **Progress Monitoring**: The application provides an endpoint to monitor the status of both the download and the chunked upload processes. This endpoint offers visibility into the progress of each chunk, enabling users to track the overall transfer progress.

# Usage:

