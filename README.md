 🗄️ VaultBox – Secure Cloud File Storage

VaultBox is a full-stack secure file storage system built with Node.js, AWS S3, and DynamoDB. It allows users to register, authenticate, and manage personal files on the cloud via a clean web interface. Designed with scalability, security, and simplicity in mind.. 

---

## 🚀 Features

-  **JWT Authentication** – User login and signup with secure token-based access
-  **AWS S3 Storage** – All files are uploaded to an S3 bucket with pre-signed URLs
-  **File Management** – Upload, list, download, and delete files from your personal vault
-  **Metadata Tracking** – DynamoDB stores per-user file data (filename, upload time, etc.)
-  **Modern UI** – Clean, responsive HTML + Bootstrap interface with dark navbar
-  **System Design Ready** – Designed with production cloud architecture in mind

---

## 🧰 Tech Stack

| Layer         | Technology               |
|---------------|---------------------------|
| Frontend      | HTML, CSS, Bootstrap      |
| Backend       | Node.js, Express          |
| Auth          | JWT (JSON Web Token)      |
| Tools         | Multer, AWS SDK v3, dotenv|
| Database      | AWS DynamoDB              |
| Cloud Storage | AWS S3                    |

---
### 🔍 Environment Variables (`.env`)
```env
PORT=5000
JWT_SECRET=your_secret
S3_BUCKET_NAME=your-bucket-name
AWS_REGION=ap-south-1
AWS_ACCESS_KEY_ID=your-access-key
AWS_SECRET_ACCESS_KEY=your-secret-key


